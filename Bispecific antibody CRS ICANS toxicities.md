# Bispecific toxicity: grade fast, treat by agent

For current T-cell-engaging bispecific antibodies, cytokine release syndrome (CRS) is the defining toxicity. It is frequent, early and mostly low grade. Talquetamab has the highest rate at **76%**, followed by teclistamab at **64%**, elranatamab at **58%**, tarlatamab at **57%** and linvoseltamab at **46%**. Grade ≥3 CRS stays at about **0.2–2%**, and most events cluster around the step-up doses. ICANS is much less common (**1–10%**), but it arrives later and less predictably. With tarlatamab and epcoritamab the median onset is about **16 days** after starting therapy. Infections, not CRS, are the main cause of non-relapse death with the myeloma agents (fatal infections **4–7%** with BCMA agents). Talquetamab adds a distinct GPRC5D syndrome: taste loss, skin and nail changes, and weight loss in **50–80%**, much of it persistent. Identification rests on ASTCT grading, the 10-point ICE score and first ruling out infection. Management escalates antipyretics → dexamethasone and/or tocilizumab → ICU-level steroids, with agent-specific twists: tocilizumab is used early in myeloma, dexamethasone first for tarlatamab and blinatumomab, and steroids are deferred for tebentafusp. The UVA Health guideline (approved 06/06/2025) remains broadly sound. However, at least fourteen items have been overtaken by 2025–2026 label changes and consensus, most importantly:
- **tarlatamab's Sept 14, 2026 drop to 6–8 h of post-dose monitoring**
- **epcoritamab's April 2026 removal of mandatory admission**
- **the March 2026 Tec-Dara approval**
- a **blinatumomab grade 2 ICANS rule that now requires interruption**
- tocilizumab limits looser than the bispecific consensus

A CARTOX-style tool can fill a real gap: no society or manufacturer bispecific app exists. It should be built as an offline progressive web app around three things: a yes/no grading wizard, an agent selector that drives label-specific rules, and weight-based dose calculators.

## CRS hits most patients early and mildly; ICANS is rarer and can arrive late

Every approved T-cell engager produces CRS through the same mechanism, T-cell activation and a cytokine surge dominated by IL-6. Incidence, timing and severity, however, vary enough between agents that one generic "watch for 48 hours" rule does not fit. The table below uses current US labeling as of September 2026. Where a label moved to a larger pooled safety population, the older pivotal-trial figure is superseded and noted.

| Agent (target, route) | CRS any grade | CRS grade ≥3 | Median CRS onset | ICANS | Median ICANS onset | Required post-dose monitoring (current label) |
|---|---|---|---|---|---|---|
| Teclistamab mono (BCMA, SC) | 64% (pooled N=448) | 0.2%* | 2 days | 6% | 4 days | 48 h after step-up doses 1 and 2 |
| Teclistamab + daratumumab SC | 60% | 0% | — | 1.1% | 2 days | REMS; step-up D1/D3/D7* |
| Elranatamab (BCMA, SC) | 58% | 0.5% | 2 days | 3.3% | 3 days | 48 h after SUD1, 24 h after SUD2 |
| Linvoseltamab (BCMA, IV) | 46% | 0.9% | 11 h from end of infusion | 8% | 1 day | 24 h after SUD1 and SUD2 |
| Talquetamab (GPRC5D, SC) | 76% | 1.5% | 27 h | 9% | 2.5 days | 48 h after every step-up dose |
| Tarlatamab (DLL3, IV) | 57% (pooled N=473) | ~1.9% | 16 h | 10% | 16 days | 6–8 h on C1D1/C1D8, then 48 h within 1 h of care with a caregiver |
| Epcoritamab (CD20, SC), LBCL | 51% | 2.5% | 24 h (21 h after first 48 mg) | 6% | 16.5 days from start | Clinician decides inpatient vs outpatient after first 48 mg |
| Glofitamab (CD20, IV) | 70% | 4.2% | 14 h after 2.5 mg | 4.8% | — | Mandatory 24 h admission after 2.5 mg |
| Mosunetuzumab IV (CD20) | 44% (FL) | 2.5% | 5 h after C1D1 | 1% (FL) | 17 days | No routine admission |
| Mosunetuzumab SC (CD20) | 30% | 2.1% | 17 h (C1D1); 62 h (C1D8) | 3.1% | — | No routine admission |
| Blinatumomab (CD19, continuous IV) | 7–16% | — | 2 days | 7.5% | within 2 weeks | Admit first 9 days (R/R) or 3 days (MRD/consolidation) of C1 |
| Tebentafusp (gp100, IV) | 89% | 0.8% | day of infusion | — | — | ≥16 h after first 3 infusions |

\*Figures flagged for verification against the PI; see the note below.

Sources: [Tecvayli label](https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=54e0f974-ccee-44ea-9254-40e9883cee1e&audience=professional); [Elrexfio label 2026](https://www.accessdata.fda.gov/drugsatfda_docs/label/2026/761345s007lbl.pdf); [Lynozyfic label](https://www.accessdata.fda.gov/drugsatfda_docs/label/2025/761400s000lbl.pdf); [Talvey label](https://www.accessdata.fda.gov/drugsatfda_docs/label/2025/761342s016lbl.pdf); [Imdelltra HCP safety](https://www.imdelltrahcp.com/safety/neurological-events-icans); [Epkinly label](https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=d7836711-b677-412d-bf2d-0f7c8444103a); [Columvi label](https://www.accessdata.fda.gov/drugsatfda_docs/label/2026/761309s007lbl.pdf); [Lunsumio label](https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=2ef0cf38-101c-4681-98fe-c05dc9ead443); [Lunsumio VELO label](https://dailymed.nlm.nih.gov/dailymed/fda/fdaDrugXsl.cfm?setid=6a2b6dc2-48bd-4da7-a611-bc6bae2893c8&type=display); [Blincyto label](https://dailymed.nlm.nih.gov/dailymed/lookup.cfm?setid=38b482a8-960b-4591-9857-5031ecb830aa); [Kimmtrak HCP](https://www.kimmtrakhcp.com/); [BC Cancer tebentafusp](https://www.bccancer.bc.ca/drug-database-site/Drug%20Index/Tebentafusp_monograph.pdf).

Note on verification: most label figures were extracted through automated summaries of FDA and DailyMed documents. The teclistamab grade 3 figure of 0.2% (the original MajesTEC-1 figure was 0.6%), the Tec-Dara step-up days and the teclistamab first-treatment-dose monitoring wording all need a direct check against the PI before they go into the app.

### Myeloma agents: step-up doses carry the risk, and each agent has a different clock

With the myeloma bispecifics, CRS is concentrated in the step-up phase. For teclistamab, CRS follows **37%** of first step-up doses, 32% of second step-up doses, 20% of first full doses and only **2.5%** of later doses ([Tecvayli label](https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=54e0f974-ccee-44ea-9254-40e9883cee1e&audience=professional)). Talquetamab breaks this pattern. Its CRS peaks at the **second** step-up dose (44%) rather than the first (29%), and on the biweekly schedule risk stays substantial through the third step-up dose (33%) and the first 0.4 mg/kg dose (30%) ([Talvey label](https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=9001355e-003d-4d4e-b4ce-337e0fd14952&audience=professional)). An app that shows "highest risk = first dose" for every agent would therefore be wrong for talquetamab.

Timing matters as much as rate. Linvoseltamab is given IV, and its CRS starts a median **11 hours** after the infusion ends. That explains why its label requires only 24-hour admissions ([Lynozyfic label](https://www.accessdata.fda.gov/drugsatfda_docs/label/2025/761400s000lbl.pdf)). The subcutaneous BCMA agents peak at about two days, which is why their labels use 48-hour admissions.

ICANS is rare with these agents but shows up later than CRS. The median onset is **4 days** for teclistamab and **3 days** for elranatamab, often after a 48-hour admission has ended, which argues for caregiver instructions and home neurological checks rather than hospital-only surveillance.

Broader label "neurologic toxicity" runs **54–60%** across all four agents. Most of it is headache and neuropathy, not ICANS. Teclistamab also carries a **0.4%** rate of fatal neurotoxicity, including Guillain-Barré syndrome and status epilepticus ([Tecvayli label](https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=54e0f974-ccee-44ea-9254-40e9883cee1e&audience=professional)).

All four myeloma agents still require a REMS and mandatory inpatient step-up. This differs from CAR-T, whose REMS the FDA removed in June 2025 ([AABB](https://www.aabb.org/news-resources/news/article/2025/06/30/fda-eliminates-rems-for-approved-car-t-cell-therapies)). An August 2026 label-concordance review found no 2026 change allowing outpatient step-up ([GlobalRPh](https://globalrph.com/2026/08/can-bispecific-antibodies-move-safely-into-the-outpatient-clinic-a-label-concordant-framework-for-clinicians/)).

### Tarlatamab: a short monitoring window before a later median onset

Tarlatamab moved to full approval in November 2025 on the basis of DeLLphi-304, where median overall survival was **13.6 vs 8.3 months** versus chemotherapy (HR 0.60) ([ASCO Post](https://ascopost.com/issues/august-25-2025/potential-new-second-line-standard-of-care-emerges-in-small-cell-lung-cancer/)).

On **September 14, 2026** the FDA cut the required monitoring after the C1D1 (1 mg) and C1D8 (10 mg) doses from 22–24 hours to **6–8 hours** from the start of infusion. Patients must still stay within one hour of an appropriate healthcare setting with a caregiver for 48 hours in total, and must have a vital-signs assessment on Days 2 and 9 ([Amgen/PR Newswire](https://www.prnewswire.com/news-releases/fda-approves-reduced-monitoring-time-for-first-two-doses-of-imdelltra-302877593.html); [Imdelltra HCP dosing](https://www.imdelltrahcp.com/starting-imdelltra/dosing-and-administration)).

Under the pooled label population (n=473):
- CRS occurs in **39%** of patients after C1D1 and 32% after C1D8, but only 5% after C1D15.
- Median onset is **16 hours**, so the new 6–8-hour window closes before the typical CRS begins.
- In the DeLLphi-304 48-hour monitoring cohort, the median time to CRS intervention was **27 hours** after the last dose ([OncLive](https://www.onclive.com/view/dellphi-304-data-reinforce-role-of-tarlatamab-as-second-line-soc-in-small-cell-lung-cancer)).

In practice, most tarlatamab CRS will now start at home or in a hotel. The quality of the caregiver plan, the Day 2 check and after-hours triage now determines safety more than the infusion-chair observation does.

Tarlatamab ICANS (10%) also behaves differently from myeloma ICANS. Its median onset is **16 days**, with a range extending to 862 days ([Imdelltra HCP safety](https://www.imdelltrahcp.com/safety/neurological-events-icans)), and ICANS is more common in patients with brain metastases (**9.0% vs 4.0%**, same source). Tarlatamab ICANS is not a step-up-only risk.

## Grading hinges on ASTCT criteria, the ICE score, and ruling out infection first

Every current label, the IMWG myeloma consensus, the Crombie CD3×CD20 consensus and the UVA guideline use the same ASTCT (Lee 2019) grading ([NCI PDQ ASTCT table](https://www.ncbi.nlm.nih.gov/books/NBK577671/table/CDR0000805706__100/); [Crombie, Blood 2024](https://ashpublications.org/blood/article/143/16/1565/514709/Consensus-recommendations-on-the-management-of)).

CRS grading starts from fever ≥38 °C. The grade is set by whichever of hypotension or hypoxia is worse:

| CRS grade | Hypotension | Hypoxia |
|---|---|---|
| 1 | None | None |
| 2 | Fluid-responsive, no vasopressor | Low-flow O2 ≤6 L/min or blow-by |
| 3 | One vasopressor (± vasopressin) | High-flow nasal cannula, facemask, non-rebreather or Venturi mask |
| 4 | Multiple vasopressors | Positive pressure (CPAP, BiPAP or intubation) |

Two grading rules are easily missed at the bedside, and an app should enforce both:
- Once antipyretics or anticytokine therapy have been given, **fever is no longer required** to keep a grade.
- Fever, hypotension and hypoxia count toward CRS only when they are "not attributable to any other cause" ([NCI PDQ](https://www.ncbi.nlm.nih.gov/books/NBK577671/table/CDR0000805706__100/)).

ICANS grading combines the 10-point ICE score with four other domains: level of consciousness, seizures, motor findings, and raised intracranial pressure or cerebral edema. The ICE score covers orientation (4 points), naming three objects (3), following commands (1), writing a sentence (1) and counting back from 100 by tens (1) ([EBMT/EHA handbook](https://www.ncbi.nlm.nih.gov/books/NBK584157/table/ch27.Tab1/)).

| ICANS grade | ICE score | Other findings (any one) |
|---|---|---|
| 1 | 7–9 | Awakens spontaneously |
| 2 | 3–6 | Awakens to voice |
| 3 | 0–2 | Awakens only to touch; a rapidly resolving seizure; or focal edema on imaging |
| 4 | 0 | Unarousable; seizure >5 min; hemiparesis; diffuse edema, posturing, CN VI palsy, papilledema or Cushing's triad |

The worst domain sets the grade ([Crombie, Blood 2024](https://ashpublications.org/blood/article/143/16/1565/514709/Consensus-recommendations-on-the-management-of)).

The UVA guideline already reproduces both grading tables and the ICE tool (Tables 1, 4 and 5). It asks for an ICE score at least before each step-up dose, documented in the ICE Tool Flowsheet.

Grading only works once the cause has been identified correctly, and fever after a bispecific is not automatically CRS. Crombie is explicit: "for all patients with fever, alternative etiologies including infection, should always be considered" ([Crombie, Blood 2024](https://ashpublications.org/blood/article/143/16/1565/514709/Consensus-recommendations-on-the-management-of)). Critical-care reviewers go further and note that distinguishing CRS from septic shock "can be nearly impossible", so both are treated empirically ([EMCrit IBCC](https://emcrit.org/ibcc/cart/)).

The differential includes:
- neutropenic sepsis
- COVID-19 and opportunistic infection
- infusion reactions with the IV agents
- tumor flare with glofitamab (**12%**, with a median onset of 2 days) ([Columvi label](https://www.accessdata.fda.gov/drugsatfda_docs/label/2026/761309s007lbl.pdf))
- progressive multifocal leukoencephalopathy (PML) in patients with subacute neurological deficits (epcoritamab **0.4%**, six fatal; also reported with linvoseltamab and glofitamab) ([Epkinly label](https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=d7836711-b677-412d-bf2d-0f7c8444103a))

Not every neurological event is ICANS. With mosunetuzumab, headache (21%) and neuropathy (13%) far outnumber ICANS (1–2%) ([Lunsumio label](https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=2ef0cf38-101c-4681-98fe-c05dc9ead443)).

The third diagnosis to exclude is **IEC-HS**, the HLH-like syndrome defined by ASTCT in 2023 (Hines et al.). It typically appears as CRS is resolving, not at its peak, and it does not require fever. Its features are:
- ferritin >2× ULN (or >2× baseline) and/or rapidly rising
- new or worsening cytopenias
- hypofibrinogenemia or coagulopathy
- transaminitis or hemophagocytosis

([Hines 2023](https://digitalcommons.library.tmc.edu/cgi/viewcontent.cgi?article=4592&context=uthgsbs_docs)).

IEC-HS after bispecifics is rare (about **0.7%**) but carries about **58% mortality**. Cases have been reported with epcoritamab, mosunetuzumab, teclistamab and, in 2026, glofitamab ([Fresa et al., Haematologica 2026](https://haematologica.org/article/view/14122)). Treatment is anakinra with or without corticosteroids first, ruxolitinib second, and low-dose etoposide (50–100 mg/m², not HLH-94 dosing) or emapalumab for refractory disease. Tocilizumab is "specifically discouraged" when there is no concurrent CRS ([Hines 2023](https://digitalcommons.library.tmc.edu/cgi/viewcontent.cgi?article=4592&context=uthgsbs_docs)).

Glofitamab causes a fall in fibrinogen in **84%** of patients ([Columvi label](https://www.accessdata.fda.gov/drugsatfda_docs/label/2026/761309s007lbl.pdf)), so fibrinogen trends must be read against the patient's own baseline.

## Dexamethasone-first or tocilizumab-first depends on the agent

All sources agree on the general shape of CRS management; they disagree on where tocilizumab sits relative to dexamethasone.

**Myeloma (IMWG 2024):** give tocilizumab 8 mg/kg for grade ≥2 CRS, and consider it for grade 1 CRS that lasts more than 24–48 hours. Add dexamethasone 10 mg every 6 hours at grade 3. Consider anakinra for refractory grade 4 ([IMWG 2024](https://www.binasss.sa.cr/may24/52.pdf)).

**Lymphoma (Crombie 2024 CD3×CD20 panel):** leans steroid-first.
- Grade 1: antipyretics, then dexamethasone 10 mg for refractory or recurrent fever, often from a home prescription taken after a phone call with the team. Tocilizumab only if grade 1 persists beyond 48 hours.
- Grade 2: facility care with dexamethasone ≥10 mg every 12 hours. Add tocilizumab if CRS persists, the patient is high risk, or grade 2 CRS develops while already on steroid prophylaxis.
- Grade 3: dexamethasone 10 mg IV every 6 hours plus tocilizumab.
- Grade 4: dexamethasone 20 mg every 6 hours.
- Taper steroids rather than stopping them abruptly ([Crombie, Blood 2024](https://ashpublications.org/blood/article/143/16/1565/514709/Consensus-recommendations-on-the-management-of)).

**Tarlatamab label:** also steroid-first. Grade 2: consider dexamethasone 8 mg IV, with tocilizumab optional. Grade 3: dexamethasone 8 mg IV every 8 hours for up to 3 doses, and tocilizumab is recommended ([Imdelltra 2024 label](https://www.accessdata.fda.gov/drugsatfda_docs/label/2024/761344s000lbl.pdf)).

**Tebentafusp:** the opposite pattern. CRS is nearly universal and mostly grade 2 and fluid-responsive, so the approach is fluids first, with corticosteroids reserved for persistent or worsening grade ≥2 CRS ([BC Cancer monograph](https://www.bccancer.bc.ca/drug-database-site/Drug%20Index/Tebentafusp_monograph.pdf)).

The UVA guideline captures these distinctions correctly. Table 3 names dexamethasone as the preferred initial intervention for tarlatamab and blinatumomab and defers steroids for tebentafusp. Table 2 recommends *early* tocilizumab for patients with multiple myeloma, patients over 65, patients with cardiac or renal comorbidity, and epcoritamab patients already on daily steroids.

No randomized data compare the two sequences. Crombie concedes that "no data" exist on outcomes of grade 2 CRS managed without anticytokines ([Crombie, Blood 2024](https://ashpublications.org/blood/article/143/16/1565/514709/Consensus-recommendations-on-the-management-of)). The agent-specific choices therefore reflect expert judgment about each drug's CRS kinetics rather than trial evidence.

### Tocilizumab caps differ

Three sources set different tocilizumab ceilings:

| Source | Dose | Maximum doses |
|---|---|---|
| Actemra label | 8 mg/kg for patients ≥30 kg; no more than 800 mg per infusion; ≥8 h apart | Up to 3 additional doses (4 total) |
| ASCO 2021 (CAR-T) | Same dose and interval | 3 doses in 24 h; 4 total |
| Crombie bispecific consensus | Same dose and interval | **≤2 per CRS event and ≤3 in 6 weeks**; switch to anakinra beyond that |

Sources: [Actemra label](https://www.accessdata.fda.gov/drugsatfda_docs/label/2025/125276s147lbl.pdf); [CADTH table](https://www.ncbi.nlm.nih.gov/books/NBK604827/table/t12/); [Crombie, Blood 2024](https://ashpublications.org/blood/article/143/16/1565/514709/Consensus-recommendations-on-the-management-of).

Crombie also advises keeping **at least two doses of tocilizumab** available at the treating site at all times.

The myeloma labels and IMWG text retrieved for this report gave no maximum dose count. The Crombie cap therefore comes from the lymphoma consensus and is being extrapolated when applied to myeloma.

### ICANS is treated with steroids, not tocilizumab

ICANS management is more consistent across sources than CRS management:
- **Labels:** dexamethasone 10 mg IV every 6 hours for grade 2–3, and dexamethasone or methylprednisolone 1 g/day for grade 4 (for example, [Epkinly label](https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=d7836711-b677-412d-bf2d-0f7c8444103a); [Tecvayli label](https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=54e0f974-ccee-44ea-9254-40e9883cee1e&audience=professional)).
- **IMWG:** slightly softer at grade 2 (10 mg every 12 hours), escalating to anakinra if there is no improvement by 48 hours ([IMWG 2024](https://www.binasss.sa.cr/may24/52.pdf)).
- **Tocilizumab:** not effective for isolated severe ICANS and may worsen it ([Advanced Practitioner review](https://resources.advancedpractitioner.com/multiple-myeloma/focus-on-bsabs/management-of-adverse-effects-in-patients-with-multiple-myeloma-treated-with-bispecific-antibodies/)).

The UVA Table 6 regimen already matches the label standard: dexamethasone 10 mg every 6 hours from grade 2, levetiracetam 1,000 mg every 12 hours, neurology and EEG, then a structured taper. The seizure and raised-ICP tables (Tables 8 and 9) go beyond anything in the bispecific labels.

### Prophylactic tocilizumab: strong data, still off-label

The biggest management shift since the UVA guideline was written is prophylactic tocilizumab, which enables outpatient step-up in myeloma.

In 2024, IMWG called prophylactic tocilizumab "investigational and not recommended outside of a clinical trial" ([IMWG 2024](https://www.binasss.sa.cr/may24/52.pdf)). Two datasets have since challenged that position:
- **MajesTEC-1 prophylaxis cohort:** tocilizumab 8 mg/kg before the first teclistamab step-up dose cut CRS from **72% to 25%**, with no grade ≥3 events ([OncLive](https://www.onclive.com/view/updated-analysis-from-majestec-1-confirms-crs-reduction-with-prophylactic-tocilizumab-in-relapsed-refractory-myeloma)).
- **OPTec/OPTal trial (ASCO 2026, 15 US community sites, fully outpatient step-up):** CRS occurred in **8.9%** of teclistamab patients, with no grade ≥2 events and no CRS hospitalizations. There was one grade 5 sepsis, and grade ≥3 infections occurred in 18% ([AJMC](https://www.ajmc.com/view/results-show-giving-prophylactic-tocilizumab-reduces-crs-in-outpatient-delivery-of-teclistamab-talquetamab)).

A remote-monitoring series with wearables reported a **71%** reduction in hospitalization with only grade 1 CRS ([Blood 2025 abstract](https://www.sciencedirect.com/science/article/abs/pii/S0006497125054989)).

The practice is spreading, but it remains off-label: no FDA label includes it, and no formal consensus update replacing IMWG 2024 was found.

In lymphoma, a steroid-based analogue exists. At MGH, dexamethasone 4 mg twice daily for 3 days after each early glofitamab dose halved CRS (**32% vs 63%** historically) ([ScienceDirect 2025](https://www.sciencedirect.com/science/article/pii/S2950328025000822)).

## Beyond CRS: infections, cytopenias and on-target toxicities

The CRS and ICANS focus of the UVA guideline explicitly places infections, cytopenias and HLH "outside the scope". For myeloma bispecifics, however, those are where the deaths are.

| Agent | Serious infections | Grade 3–4 infections | Fatal infections | Other |
|---|---|---|---|---|
| Teclistamab monotherapy | 30% | 35% | 4.2% | — |
| Tec-Dara | 54% | 54% | 4.6% | — |
| Elranatamab | 42% | — | **7%** | — |
| Linvoseltamab | 42% | — | 4% | Two PML cases |
| Talquetamab | — | — | 1.5% | — |

Sources: [Tecvayli label](https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=54e0f974-ccee-44ea-9254-40e9883cee1e&audience=professional); [Elrexfio label](https://www.accessdata.fda.gov/drugsatfda_docs/label/2026/761345s007lbl.pdf); [Lynozyfic label](https://www.accessdata.fda.gov/drugsatfda_docs/label/2025/761400s000lbl.pdf); [Talvey label](https://www.accessdata.fda.gov/drugsatfda_docs/label/2025/761342s016lbl.pdf).

Other hematologic and immune effects:
- **Neutropenia:** 88% with teclistamab (70% grade 3–4) ([Tecvayli label](https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=54e0f974-ccee-44ea-9254-40e9883cee1e&audience=professional)).
- **Hypogammaglobulinemia:** 84% with Tec-Dara (same source).
- **IVIG threshold:** the 2026 Tecvayli label is the first myeloma bispecific label with a numerical IVIG target, keeping serum IgG **>400 mg/dL**. IMWG applies the same threshold across BCMA agents.
- **Standard IMWG prophylaxis bundle** ([IMWG 2024](https://www.binasss.sa.cr/may24/52.pdf)):
  - acyclovir or valacyclovir
  - TMP-SMX for PJP until CD4 >200/µL
  - CMV PCR monitoring, treating clinical disease only
  - entecavir for patients at HBV risk
  - vaccination before starting
- **Evidence for primary IVIG:** retrospective. In a five-center cohort, grade ≥3 infections did not fall significantly (35% vs 45%, p=0.37), but overall survival improved (HR 0.37) ([Blood Cancer J 2025](https://www.nature.com/articles/s41408-025-01282-0)).

Label-built interval extension (every 2 weeks, then every 4 weeks) is the other lever for reducing infections. All four myeloma labels now include it.

### Talquetamab's GPRC5D syndrome is a distinct management problem

GPRC5D is expressed in keratinized tissue, so talquetamab produces a toxicity cluster the BCMA agents do not ([Talvey label](https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=9001355e-003d-4d4e-b4ce-337e0fd14952&audience=professional)):

| Toxicity | Incidence | Median onset | Notes |
|---|---|---|---|
| Oral toxicity (dysgeusia 49%, dry mouth 34%, dysphagia 23%) | **80%** | 15 days | **65%** unresolved at last follow-up |
| Skin toxicity | 62% | 25 days | — |
| Nail disorders | 50% | — | — |
| Weight loss | 62% (29% grade 2) | 67 days (grade ≥2) | — |

Motor dysfunction including ataxia affects **10%** ([Talvey label](https://www.accessdata.fda.gov/drugsatfda_docs/label/2025/761342s016lbl.pdf)). In MonumenTAL-3, ataxia and balance disorders reached **12–15%**, compared with 0.4% on standard therapy ([OncLive](https://www.onclive.com/view/monumental-3-data-support-talquetamab-plus-daratumumab-pomalidomide-as-a-new-soc-in-r-r-myeloma)).

Label actions for oral toxicity and weight loss:
- grade 1–2: supportive care
- grade 3: withhold until grade ≤1
- grade 4: permanently discontinue

IMWG adds early emollients (urea 10% or ammonium lactate 12%), topical steroids, sodium lauryl sulfate–free toothpaste, nutrition support and dental review ([IMWG 2024](https://www.binasss.sa.cr/may24/52.pdf)). Its most effective lever is reducing dosing frequency.

Specific oral interventions (dexamethasone mouthwash, saliva substitutes) are widely used, but their evidence was not verified in this research.

### Tarlatamab's non-CRS profile

Tarlatamab's other toxicities are milder but frequent ([Imdelltra HCP safety](https://www.imdelltrahcp.com/safety/neurological-events-icans)):
- dysgeusia 34%
- fatigue 48%
- decreased appetite 38%
- infections 43%
- transaminase elevations around 40%

A clinician preprint proposes that the taste loss is linked to ASCL1 regulating both taste-bud differentiation and DLL3 expression ([medRxiv preprint](https://www.medrxiv.org/content/10.1101/2024.10.11.24315056v2.full.pdf)). That mechanism is unconfirmed.

## Fourteen points where the June 2025 UVA guideline has fallen behind

The UVA guideline's architecture is sound and should be preserved: ASTCT grading, separate outpatient and inpatient CRS tables, the dexamethasone taper, and the seizure and ICP tables. Its product references, however, predate a burst of 2025–2026 label activity. Its cited PIs date from August 2023 to November 2024. The table below lists every point where current labeling or consensus differs from or adds to the guideline, ordered roughly by patient-safety impact, for the guideline owners to consider.

| # | Topic | UVA guideline (06/06/2025) | Current label / consensus (Sept 2026) | Suggested consideration |
|---|---|---|---|---|
| 1 | **Tarlatamab C1D1/C1D8 monitoring** | App. B: outpatient step-up with 12 h infusion-center observation + 24 h clinic visit, or 24 h inpatient; within 1 h of UVA for 48 h | **Sept 14, 2026:** 6–8 h from start of infusion; within 1 h with a caregiver for 48 h; vital-signs check on Days 2 and 9 ([PR Newswire](https://www.prnewswire.com/news-releases/fda-approves-reduced-monitoring-time-for-first-two-doses-of-imdelltra-302877593.html)) | Decide whether to keep 12 h (conservative, label-compliant) or adopt 6–8 h. Either way, strengthen caregiver and home-vitals requirements, because median CRS onset (16 h) now falls after discharge. Remove the need for "extended infusion hours" for tarlatamab. |
| 2 | Tarlatamab incidence data | App. A: CRS 55%, onset 13.5 h, ICANS 9%, onset 29.5 days (2024 label, n=187) | Pooled n=473: CRS 57%, onset 16 h, ICANS 10%, onset **16 days** ([Imdelltra HCP](https://www.imdelltrahcp.com/safety/neurological-events-icans)) | Update App. A. Also verify whether the label's "monitor 22–24 h at next dose after grade ≥2 CRS/ICANS" survived the 2026 revision (unconfirmed). |
| 3 | Tarlatamab steroid dosing | Generic dexamethasone 10 mg (G1–2) / 10 mg q6h (G3) | Label: dexamethasone **8 mg** (G2, consider); 8 mg q8h ×3 (G3) ([2024 label](https://www.accessdata.fda.gov/drugsatfda_docs/label/2024/761344s000lbl.pdf)) | Add a tarlatamab-specific footnote to Table 3. |
| 4 | **Epcoritamab admission** | App. B: 23 h inpatient observation after first 48 mg (DLBCL) | **Apr 1, 2026:** clinician assesses inpatient vs outpatient monitoring; outpatients stay near a CRS-capable facility. EPCORE NHL-6: 13.6% of outpatients were hospitalized for CRS within a week ([AJMC](https://www.ajmc.com/view/label-change-helps-remove-barriers-to-broader-use-of-epcoritamab-in-dlbcl-sharman-says)) | Define UVA eligibility criteria for outpatient first full dose. |
| 5 | Epcoritamab indications and premedication | References June 2024 PI | FL + lenalidomide/rituximab approved Nov 2025 (CRS 24%, ICANS 0.8%). C1 premedication continues corticosteroid **3 days after each dose** ([Epkinly label](https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=d7836711-b677-412d-bf2d-0f7c8444103a)) | Add the R² regimen. Note that the post-dose steroids can delay and mask CRS onset. |
| 6 | **Teclistamab + daratumumab (Tec-Dara)** | Not present; teclistamab data from MajesTEC-1 (CRS 72.1%, ICANS 3%) | Approved **Mar 5, 2026** after ≥1 prior line; separate step-up (D1/D3/D7), then 3 mg/kg q2w → q4w; CRS 60% (all G1–2), ICANS 1.1%, grade 3–4 infections 54%, hypogammaglobulinemia 84%. Pooled monotherapy label now CRS 64%, ICANS 6% ([Tecvayli label](https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=54e0f974-ccee-44ea-9254-40e9883cee1e&audience=professional); [J&J](https://www.jnj.com/media-center/press-releases/johnson-johnson-announces-u-s-fda-approval-of-tecvayli-plus-darzalex-faspro-for-relapsed-refractory-multiple-myeloma-offering-a-potential-new-standard-of-care-as-early-as-second-line)) | Add a Tec-Dara row. Update App. A. Verify the current teclistamab first-treatment-dose monitoring wording (App. B says 48 h after *all* step-up doses). |
| 7 | **Linvoseltamab** | Absent | Approved July 2, 2025; IV; CRS 46%, onset 11 h after infusion; 24 h admission after SUD1 and SUD2; LYNOZYFIC REMS ([Lynozyfic label](https://www.accessdata.fda.gov/drugsatfda_docs/label/2025/761400s000lbl.pdf)) | Add to Apps. A and B if it is on formulary. |
| 8 | Mosunetuzumab SC | Absent | Lunsumio VELO approved Dec 22, 2025; CRS 30%, but C1D8 onset median **62 h** ([VELO label](https://dailymed.nlm.nih.gov/dailymed/fda/fdaDrugXsl.cfm?setid=6a2b6dc2-48bd-4da7-a611-bc6bae2893c8&type=display)) | Add. Home monitoring should cover about 72–96 h, not 48 h. |
| 9 | **Blinatumomab grade 2 ICANS** | Table 6: "continue blinatumomab" for G1–2 ICANS | Label (neuro section revised 4/2025; current 4/14/2026): **G2 ICANS → interrupt**, corticosteroids, restart at 9 mcg/day ([Blincyto label](https://dailymed.nlm.nih.gov/dailymed/lookup.cfm?setid=38b482a8-960b-4591-9857-5031ecb830aa)) | Revise the G2 exception. When restarting after an interruption of ≥4 h, re-premedicate with dexamethasone 20 mg (R/R). |
| 10 | **Tocilizumab limits** | Table 3: up to 3 doses/24 h, absolute maximum 4; the G1 row also says "repeat… up to 3 doses in 24 h" | Crombie: **≤2 per event, ≤3 per 6 weeks**, then anakinra. Actemra label and ASCO 2021 allow 4 total ([Crombie](https://ashpublications.org/blood/article/143/16/1565/514709/Consensus-recommendations-on-the-management-of)) | Align with Crombie at least for CD20 agents. Remove the repeat-dosing language from the G1 row. Add "keep ≥2 doses on site". UVA already escalates to anakinra after 2 doses, so the practical change is small. |
| 11 | IEC-HS | "Outside the scope"; Table 3 says only "assess for HLH/MAS" | Hines 2023 criteria; anakinra first; avoid tocilizumab without CRS; mortality about 58% after bispecifics ([Hines](https://digitalcommons.library.tmc.edu/cgi/viewcontent.cgi?article=4592&context=uthgsbs_docs); [Fresa 2026](https://haematologica.org/article/view/14122)) | Add a brief IEC-HS recognition box with ferritin, fibrinogen, cytopenia and liver-test triggers. |
| 12 | Prophylactic tocilizumab / outpatient myeloma step-up | Not addressed | OPTec: CRS 8.9% with outpatient teclistamab step-up; still off-label; IMWG 2024 "not recommended" not formally superseded ([AJMC](https://www.ajmc.com/view/results-show-giving-prophylactic-tocilizumab-reduces-crs-in-outpatient-delivery-of-teclistamab-talquetamab)) | Take an explicit institutional position (adopt, pilot or decline). Note that labels still mandate inpatient step-up. |
| 13 | ICANS surveillance after step-up | ICE before each step-up dose; afterwards "provider discretion" | Median ICANS onset 16 days (tarlatamab) and 16.5 days (epcoritamab) | Add a prompt for ICE or neuro checks at later visits for these agents. |
| 14 | Infection prophylaxis | Outside scope | Tecvayli label: IVIG to IgG >400 mg/dL; IMWG bundle; epcoritamab label *requires* PJP prophylaxis ([IMWG](https://www.binasss.sa.cr/may24/52.pdf); [Epkinly label](https://dailymed.nlm.nih.gov/dailymed/drugInfo.cfm?setid=d7836711-b677-412d-bf2d-0f7c8444103a)) | Cross-reference a companion infection guideline, or add an appendix. |

Two smaller housekeeping items also need attention:
- Glofitamab admission: App. B says "23 hours" of observation, while the label says during and for **24 hours** after the 2.5 mg dose ([Columvi label](https://www.accessdata.fda.gov/drugsatfda_docs/label/2026/761309s007lbl.pdf)).
- Several App. A incidence figures use trial rather than label denominators, for example glofitamab 63% versus the label's 70%.

The anakinra dose in the UVA guideline (8–10 mg/kg/day IV in divided doses) is at the high end of published ranges. Those ranges run from 100 mg twice daily ([MD Anderson CARTOX algorithm](https://www.mdanderson.org/documents/for-physicians/algorithms/clinical-management/clin-management-cytokine-release-web-algorithm.pdf)) to 12 mg/kg/day ([EMCrit](https://emcrit.org/ibcc/cart/)). No bispecific-specific standard exists, so this is a legitimate institutional choice rather than an error.

## A CARTOX-style app should combine a grading wizard, dose calculators and a wallet card

### What CARTOX is

CARTOX is MD Anderson's free iOS and Android reference for CAR-T toxicity. Its core pattern is that "users answer yes/no questions that lead to additional options, producing a diagnosis, toxicity level, and treatment recommendations within 30 seconds" ([Healio](https://www.healio.com/news/hematology-oncology/20190607/md-anderson-releases-free-car-tcell-therapy-toxicity-grading-and-management-app)).

- **Screens:** nine screens covering Home, Toxicity Grading, Toxicity Management, ICANS Grading, CRS Grading, Infection Prophylaxis, IEC-HS, CAPD and fungal content ([AppsHunter mirror](https://appshunter.io/ios/app/1464005828)).
- **Paper source:** the 35-page MD Anderson IEC algorithm. It names only CAR-T products and contains **no bispecific content** ([MD Anderson algorithm](https://www.mdanderson.org/documents/for-physicians/algorithms/clinical-management/clin-management-cytokine-release-web-algorithm.pdf)).
- **Update history:** iOS was refreshed to v2.6 around September 24, 2026, four years after v2.5. Android has stayed at the 2022 version ([App Store](https://apps.apple.com/us/app/cartox/id1464005828); [Google Play](https://play.google.com/store/apps/details?id=org.mdanderson.cartox&hl=en_US)).
- **Size and privacy:** the app is small (about 6 MB) and collects no data.

At UVA itself, a 2023 DNP project found that using CARTOX in simulation improved time from toxicity onset to intervention by **34%**, bringing it within 45 minutes against a 60-minute benchmark ([UVA LibraETD](https://libraetd.lib.virginia.edu/public_view/5q47rp903)). That project's author, Jessica Kassay-McAllister, is listed among the reviewers of the UVA bispecific guideline, which gives the project a ready local champion.

### The gap a bispecific tool would fill

No ASCO, ASTCT, IMWG or manufacturer bispecific app was found. What exists is scattered across several kinds of resource:
- MDCalc's separate ICE and ICANS calculators ([MDCalc](https://www.mdcalc.com/calc/10636/immune-effector-cell-associated-neurotoxicity-syndrome-icans-consensus-grading-adults))
- manufacturer HCP pages and EHR order-set guides ([Tecvayli order-set guide](https://www.bispecificsguide.com/documents/TECVAYLI_EHR_ORDER_SET_GUIDE.pdf))
- PDF guidance from the VA, Cancer Care Ontario, BC Cancer and NCODA ([VA PBM Jan 2026](https://www.va.gov/formularyadvisor/DOC_PDF/CRE_Bispecific_Antibody_CRS_and_ICANS_Neurotoxicity_Supportive_Care_Guidance_Jan_2026.pdf); [NCODA](https://www.ncoda.org/wp-content/uploads/2025/10/Bispecific-Antibody-Therapy-Resource-Guide.pdf))

### What the app should contain

Everything recommended below comes from the UVA guideline tables, current labels and the consensus papers cited above:

| Module | What it does | Content source |
|---|---|---|
| **Home tiles** | Six to eight large tiles: CRS, ICANS/ICE, Agents, Drugs & doses, Fever work-up / IEC-HS, Infection & other toxicities, ED card, About/version | CARTOX pattern |
| **Agent selector** | Chooses the agent and regimen (e.g., teclistamab mono vs Tec-Dara; talquetamab weekly vs biweekly). Shows the step-up schedule, premedication, admission hours, REMS flag, highest-risk dose, expected CRS and ICANS window, and label hold/discontinue rules | Labels; UVA Apps. A and B |
| **CRS wizard** | Yes/no path: temperature ≥38 °C (or already treated)? → hypotension? → vasopressors (one or more)? → oxygen device → grade. Then a *setting* toggle (home/infusion vs inpatient) routes to UVA Table 2 or Table 3, with agent exceptions for tarlatamab, blinatumomab, tebentafusp and myeloma | ASTCT; UVA Tables 1–3 |
| **ICE calculator + ICANS grader** | Five tap groups adding up to 10 points, plus consciousness, seizure, motor and ICP domains. The worst domain sets the grade, which links to UVA Table 6, the Table 7 taper, and Tables 8 and 9 | ASTCT; UVA Tables 4–9 |
| **Dose calculators** | Weight-based tocilizumab capped at 800 mg, with a per-event and 6-week dose counter warning at 2 and 3 doses. Dexamethasone ladder; methylprednisolone 1 g; anakinra; siltuximab 11 mg/kg; levetiracetam; lorazepam | Actemra label; Crombie; UVA |
| **Restart calculator** | Inputs agent, last dose and days since. Outputs continue, repeat step-up dose or restart. The tables differ by agent, and errors here are among the most likely to cause harm | Label restart tables |
| **Fever and red-flag card** | Culture/lab bundle; parallel febrile-neutropenia antibiotics; IEC-HS triggers (ferritin >2× baseline, falling fibrinogen, new cytopenias, CRS >7 days) | Crombie; Hines 2023 |
| **Other toxicities** | Infection prophylaxis bundle and IVIG threshold; GPRC5D grade actions and supportive checklist; tarlatamab dysgeusia, neutropenia and liver-test holds | Labels; IMWG |
| **ED / after-hours card** | One screen mirroring the patient wallet card: agent, "this may be CRS", do not delay tocilizumab or steroids, call the heme/onc attending first | UVA escalation rule; Crombie |
| **Patient home-monitoring sheet** | Vital signs every 4–8 h for ≥48 h after each step-up dose (72–96 h for SC agents with late onset); call for ≥100.4 °F; tarlatamab Day 2 and Day 9 visits | UVA App. C; labels |

### How it should be built

A **progressive web app** is the most easily deployable route to both iPhone and desktop from one codebase, and it avoids the Android version drift CARTOX suffered.

- **iOS installation:** since iOS 26, every site added to the Home Screen opens as a standalone web app by default ([Michael Tsai](https://mjtsai.com/blog/2025/10/03/web-apps-in-ios-26/)). Safari has no install prompt, so the app needs a short "Share → Add to Home Screen" help sheet. The page should include an `apple-touch-icon` and a manifest with `display: standalone` ([firt.dev](https://firt.dev/notes/pwa-ios/); [web.dev](https://web.dev/learn/pwa/installation)).
- **Offline use:** a service worker that precaches all content keeps the app working on wards with no signal. Service workers have been supported on iOS since 11.3 ([firt.dev](https://firt.dev/notes/pwa-ios/)).
- **Storage risk:** one secondary source reports that iOS evicts cached data after about seven days of disuse ([MagicBell](https://www.magicbell.com/blog/pwa-ios-limitations-safari-support-complete-guide)). This is unverified for Home Screen apps, so the app should fall back to a network fetch and should always display its content version date.
- **No patient data:** with no login and no protected health information, the app stays out of HIPAA scope. This matches CARTOX's "does not collect any data" privacy label.
- **Content as data:** agents, doses and rules should live in a versioned JSON file owned by the guideline pharmacists. A label change like the September 2026 tarlatamab update then becomes a same-day data edit rather than a four-year app-store cycle.
- **Every result screen** should carry a "last reviewed / UVA guideline version" footer and MDCalc's style of disclaimer that the tool "should not be the sole basis for care".

### "In the style of CARTOX" means the interaction model, not the brand

CARTOX's actual visual palette could not be verified in this research. More importantly, the new app should **not** use MD Anderson's name, logo or branding. What should be emulated is the interaction model: large tiles, a binary wizard, a grade result screen color-coded by grade with a single "Manage this grade" button, and short static dosing pages. UVA's own identity belongs on the app, along with its own guideline citation.

## Conclusion

The field has shifted in eighteen months from "admit everyone for step-up" toward "monitor briefly, then rely on the patient and caregiver at home". Tarlatamab's 6–8-hour window, epcoritamab's optional admission, subcutaneous mosunetuzumab without routine admission, and off-label outpatient myeloma step-up under prophylactic tocilizumab all push the first hours of CRS out of the hospital. The consequence for UVA is that the most dangerous moment is no longer in the infusion chair. It is the 2 a.m. phone call and the community ED visit, where a clinician unfamiliar with bispecifics must recognize CRS, grade it, rule out sepsis and give the right drug. That is exactly the scenario a CARTOX-style tool shortens, and it is where UVA's own simulation data showed a 34% gain.

The practical order of work is to update the guideline first and then build the app from it. The guideline owners should resolve the tarlatamab monitoring decision, the blinatumomab grade 2 ICANS exception, the tocilizumab cap and the missing agents (Tec-Dara, linvoseltamab, mosunetuzumab SC). Those decisions can then be encoded as versioned data in an offline web app, so that the next label change reaches the bedside within days rather than years. Two open questions deserve monitoring:
- whether the FDA follows its 2025 CAR-T decision by lifting REMS and inpatient step-up for myeloma bispecifics, which OPTec-style data make increasingly plausible
- whether IMWG formally reverses its 2024 stance on prophylactic tocilizumab

Either change would rewrite the agent cards overnight. That is why the app's content should be easy to update.
