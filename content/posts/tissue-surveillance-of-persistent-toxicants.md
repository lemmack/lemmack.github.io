---
title: "Tissue Surveillance of Persistent Toxicants"
date: 2025-11-27T16:34:00-05:00
draft: false
---

# Introduction

There's a gap in public health surveillance that I believe will eventually have to be addressed if we want the march of progress in population health to continue. Current surveillance relies heavily on biological fluids (blood serum and urine) to monitor population exposure to environmental contaminants. While these matrices effectively capture recent exposures and water-soluble compounds, they frequently fail to reflect the total body burden of persistent toxicants.

This gap exists because many critical pollutants do not remain in circulation; they sequester in specific tissue compartments over a lifetime, and they can be tricky to measure. Lipophilic compounds like PCBs and pesticides partition into adipose tissue, mercury builds up in nervous tissue, lead accumulates in the skeleton, and so on. Consequently, relying solely on fluid biomonitoring creates a pharmacokinetic blind spot, risking a significant underestimation of the toxicological drivers behind chronic diseases, and especially those with long latency periods such as neurodegenerative disorders and renal pathology.

Recent post-mortem analyses underscore the urgency of addressing this gap. [Studies have confirmed](https://doi.org/10.1021/acs.est.4c09458) the presence of per- and polyfluoroalkyl substances (PFAS a.k.a. "forever chemicals") in human brain tissue, adding quantitative evidence to growing concerns about blood-brain barrier penetration by these compounds. Furthermore, [the detection of black carbon](https://doi.org/10.1186/s12989-018-0250-8) in airway macrophages serves as a dosimeter for lifetime particulate exposure that ambient air monitors cannot replicate. These findings suggest that the body acts as a historical archive, recording exposures that fluid analysis misses entirely.

# Addressing Post-Mortem Bias

A valid epidemiological criticism of autopsy-based surveillance is selection bias. In public health, we often face the "[Healthy Worker Effect](https://doi.org/10.1093/occmed/49.4.225)," where the working population is healthier than the general public. With autopsy studies, we face the inverse. The population that undergoes autopsy is inherently skewed towards the elderly, the chronically ill, and those with multiple comorbidities.

If we only sample from hospital deaths, we risk measuring the toxic burden of the sick rather than the baseline burden of the population. This "denominator problem" can lead to overestimating associations between toxicants and specific diseases if not carefully managed.

## Mitigating Bias: The Trauma Gold Standard

To resolve this, a robust tissue surveillance program must prioritize specific categories of donors that serve as better proxies for the living, healthy population.

**Sudden Accidental Deaths**
One approach to reducing selection bias is to prioritize forensic autopsies of sudden, accidental deaths (e.g., motor vehicle accidents) over typical hospital autopsies. These individuals are often younger and healthier prior to the event, and their tissue burden may better approximate the general population than samples from end-stage disease. However, this population introduces its own biases: it skews male and young, concentrates geographically near urban trauma centers, and may be confounded by factors associated with accidental death (such as substance use in some motor vehicle cases). These limitations would need to be addressed through careful stratification and sensitivity analyses.

**Living Tissue Banks (Surgical Waste)**
We can also move beyond post-mortem sampling by utilizing "surgical waste" from living patients.
* **Bariatric Surgery:** This provides high-volume adipose tissue samples from a living population, allowing for real-time monitoring of lipophilic compounds. However, bariatric patients represent a metabolically distinct subpopulation, and findings may not generalize to the broader population without appropriate adjustment.
* **Orthopedic Surgery:** Procedures like hip replacements provide bone fragments that can be analyzed for lead and strontium accumulation. This population skews elderly and may over-represent certain socioeconomic groups with access to elective surgery.

By stratifying samples between "disease-related deaths" and "accidental deaths," researchers could control for the healthy donor effect and build a more accurate model of population-level exposure.

# Minimally Invasive Tissue Sampling (MITS)

To progress public health surveillance, we must move beyond the snapshot provided by blood samples and access the archive stored in tissues. This does not require a return to widely practiced complete autopsies. The emergence of Minimally Invasive Tissue Sampling (MITS), which utilizes needle biopsies to collect samples from key organs, offers a scalable, cost-effective, and culturally acceptable alternative. MITS is currently being used mostly for post-mortem analysis of infectious cases, but in theory could be adapted to analysis of persistent toxicants with a little ingenuity.

Scaling MITS for toxicological surveillance does face one significant operational hurdle: the 'fixative' problem. Standard MITS protocols, like those used in infectious disease, typically rely on formalin-fixed paraffin-embedded (FFPE) tissues. While excellent for preserving cell structure for microscopes, formalin can cross-link proteins and even contaminate samples with trace metals, rendering them less ideal for precise chemical analysis.

A dedicated 'MITS-Tox' protocol would likely require fresh-frozen samples. This introduces a cold-chain logistics challenge, as biopsy cores would need to be flash-frozen in liquid nitrogen or stored at -80°C immediately after collection. While more demanding than a jar of formalin, this infrastructure already exists in many biobanks and research hospitals; it simply needs to be standardized for the field.

By integrating toxicological screening into MITS protocols, epidemiological data collection can evolve to capture the true burden of environmental toxicity. This shift could strengthen the evidence base for associations between chronic exposure and non-communicable diseases, ultimately driving more effective environmental health policy. To be clear, I am not sure if MITS-Tox is the best solution, but it is the first one that comes to mind since it would involve repurposing a system that already exists.

## The Engineering Challenge: Chemical Purity vs. Preservation

Scaling MITS for toxicological surveillance faces a significant operational hurdle: the 'fixative' problem. Standard protocols rely on formalin-fixed paraffin-embedded (FFPE) tissues. While formalin is excellent for preserving visual structure for pathologists, it is often fatal for analytical chemists trying to measure trace concentrations of toxicants.

To accurately quantify the body burden of a pollutant, the sample must remain chemically pristine. Formalin introduces three major sources of error.

### 1. Contamination and Leaching
In toxicology, we are often measuring parts per billion (ppb). At these concentrations, formalin fixation introduces two opposing sources of error: [contamination and leaching](https://doi.org/10.1002/etc.4709).
**Contamination (False Highs)**
Standard commercial formalin is can be "dirty" from a chemical perspective.
* **Trace Metals:** Formalin buffers frequently contain trace amounts of zinc, copper, and even lead from industrial manufacturing and storage. Studies have found that copper concentrations in formalin-fixed brain tissue [can increase by approximately 37%](https://doi.org/10.1007/s10534-010-9359-4) compared to fresh-frozen samples, likely due to contamination from the fixative. If you submerge a tissue sample in this solution, you lose the ability to distinguish between the metal that was in the tissue and the metal that was in the jar.
* **Plasticizers:**  Formalin is often stored in plastic containers that leach phthalates and bisphenols. This makes it difficult to accurately measure these specific endocrine disruptors in the tissue, as background contamination from storage can overwhelm the true signal.
**Leaching (False Lows)**
The opposite problem is equally serious. Formalin is an aqueous solution, and over time, soluble elements diffuse out of the tissue and into the surrounding fluid.
* **Time-Dependent Loss:** Studies of formalin-fixed brain tissue have documented substantial leaching that increases with storage duration. Concentrations of arsenic, cadmium, magnesium, and rubidium in the formalin can [increase more than 100-fold](https://doi.org/10.1007/s12011-007-8051-1) over years of storage, representing material lost from the tissue itself.
* **Differential Effects:** The magnitude of leaching varies considerably by element. Iron concentrations in fixed brain tissue can decrease by approximately 40%, and zinc by as much as 77%, while nickel and chromium show minimal leaching. This inconsistency means there is no simple correction factor; each analyte behaves differently.
The net effect is bidirectional error that varies by compound, tissue type, and storage duration, making quantitative comparisons across studies nearly impossible.

### 2. Extraction Efficiency
To measure a toxicant, you must first extract it from the tissue matrix. Formalin works by cross-linking proteins, effectively turning the tissue into a rubbery, resistant material.
* **Incomplete Digestion:** When labs try to digest this fixed tissue to release the stored heavy metals or pesticides, the cross-linked matrix resists breakdown. This often leads to an incomplete release of the toxicant, resulting in a "false low" reading.
* **Lipid Trapping:** For lipophilic compounds (like PCBs), the hardening of the tissue can physically trap the fat droplets within the protein mesh, preventing solvents from washing the toxicants out for analysis.

### 3. The "Wet Weight" Variable
Toxicology relies on precise math: *nanograms of toxin per gram of tissue*.
Formalin alters the physical mass of the sample by dehydrating cells and changing the water content over time. A sample stored in formalin for a month will have a different weight than fresh tissue. This skews the denominator in the calculation, introducing a mathematical error margin that is unacceptable for high-precision surveillance.

### The Fresh-Frozen Necessity
To solve these quantification issues, a dedicated "MITS-Tox" protocol would likely require fresh-frozen samples. This avoids chemical contamination and preserves the native mass of the tissue. While this necessitates a cold chain (dry ice or liquid nitrogen), it is the only method I can presently think of to ensure that the number on the final lab report reflects the true burden inside the patient.

# Mapping the Total Exposome

The ultimate goal of this surveillance is to operationalize the "exposome." [First proposed](https://doi.org/10.1158/1055-9965.epi-05-0456) by cancer epidemiologist Christopher Wild in 2005, the exposome encompasses the totality of human environmental exposures from conception onwards. It is the environmental complement to the genome.

Currently, our ability to measure the exposome is unbalanced. We have excellent tools for measuring the external exposome (via air monitors and water testing) and decent tools for measuring the transient internal exposome (via blood and urine biomarkers). However, we almost entirely lack data on the *cumulative* internal exposome.

This data gap cripples our ability to draw causal links between environment and disease. If we attempt to correlate a lifetime of exposure with a chronic disease using only a blood sample taken at the time of diagnosis, we are effectively trying to reconstruct a movie from a single frame.

MITS offers one possible bridge. But regardless of the method, by banking tissue we gain access to a biological record of cumulative exposures that is shaped by ongoing processes of uptake, redistribution, metabolism, and elimination.

## From Prediction to Observation

For decades, environmental health policy has relied heavily on risk assessment modeling. Agencies estimate human risk based on factory emissions data and animal studies, mathematically predicting what the body burden *should* be.

This approach will not be sufficient forever. To continue making progress, we need to complement predictive modeling with direct empirical observation. We do not need to rely solely on estimates of whether "forever chemicals" are crossing the blood-brain barrier or whether microplastics are accumulating in the liver. With a standardized, ethically sourced MITS-Tox network (or some other solution), we could measure these burdens directly, though translating such measurements into causal understanding of disease would remain a separate challenge.

The infrastructure for this exists in our hospitals and biobanks. The technology for analysis exists in our mass spectrometry labs. All that is missing is the mandate to look where the toxicants actually hide.

# History and Implementations

## National Human Adipose Tissue Survey (NHATS) (1970-1989)

This program was conducted between 1970-1989 by the EPA of the United States as the main study making up the [National Human Monitoring Program](https://doi.org/10.17226/1787). It collected adipose tissue samples from surgeons and medical examiners across the U.S. to monitor the prevalence of lipophilic toxic substances. It provided critical baseline data on the body burden of persistent organic pollutants like PCBs and organochlorine pesticides. It was **discontinued in 1989** as the focus shifted to the National Health and Nutrition Examination Survey (NHANES) which relies on blood and urine samples (more convenient but missing important tissue data).

It's important to note that NHATS was not discontinued because it failed scientifically. It was discontinued in 1989 largely due to budget cuts and a bureaucratic shift toward 'easier' fluids-based monitoring.

In fact, a 1991 National Academy of Sciences report strongly recommended continuing and redesigning the program, noting that fluid monitoring was insufficient for persistent pollutants. The report observed that funding "up to $25–50 million per year suggested by heads of other agencies could be put to good use" for a comprehensive tissue monitoring program, a fraction of what we spend on healthcare for the diseases these pollutants may exacerbate. That level of funding never materialized, and the program has remained dormant for over thirty years.

### The Policy Failure: Surveillance vs. Modeling

But the discontinuation of NHATS in 1989 wasn't just a budgetary decision; it was related to a philosophical shift in environmental health policy. During the 1980s and 90s, regulatory agencies like the EPA moved away from *biological surveillance* (empirical observation) and toward *risk assessment modeling* (theoretical prediction).

**The "Prediction" Fallacy:** The prevailing logic was that if we knew how much pollution was coming out of factories (emissions data) and we applied mathematical models of transport and fate, we could calculate human exposure without needing to measure it physically. This approach assumed we knew all the variables.

**Why Models Failed:** History has shown this singular reliance on modeling to be an error.
* **PFAS:** Predictive models failed to anticipate the bioaccumulation of perfluorinated compounds because the chemistry was novel and the uptake pathways were not yet understood. We only found them because we physically looked.
* **PBDEs:** Flame retardants [rose in human tissue for years](https://doi.org/10.1021/es035082g) while regulators assumed they were safe, simply because there was no surveillance net to catch the trend early.

Restarting a tissue archive is an admission that models are insufficient. We cannot predict the behavior of 80,000+ industrial chemicals; we must return to the empirical standard of measuring what is actually inside us.

## Child Health and Mortality Study (CHAMPS) (2015 - Present)

Established in 2015 by the Bill & Melinda Gates Foundation (with sites becoming operational in 2016-2017), CHAMPS is a global health surveillance network dedicated to determining the definitive causes of death in children under five and stillbirths in high-mortality regions within Sub-Saharan Africa and South Asia. Moving beyond standard verbal autopsies, CHAMPS utilizes a "ground truth" protocol that combines clinical records with Minimally Invasive Tissue Sampling (MITS), which are then reviewed by a multidisciplinary panel to assign a precise cause of death. While the network currently prioritizes infectious diseases and malnutrition, its established infrastructure for collecting and banking solid organs seems to me like a potential candidate for future environmental toxicological surveillance.