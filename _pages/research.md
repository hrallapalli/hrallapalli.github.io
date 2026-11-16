---
permalink: /
title: "Research"
hide_title: true
---

<p class="lede">My research program exists at the intersection between engineering, molecular biology, and biophysics and is focused on developing imaging tools to report biological function in living subjects.</p>

## MRI-visible expression reporters for translational molecular imaging

Despite three decades of innovation, most gene expression MRI (GEMRI) strategies remain at the proof-of-principle stage. Key barriers include insufficient sensitivity at clinical field strength, reliance on bespoke pulse sequences or specialized chemistries, reliance on tissue-targeted delivery of exogenous agents, and a lack of demonstrated efficacy in species other than rodents. I discovered that the manganese (Mn<sup>2+</sup>) transport protein Zip14 can be applied as a robust MRI-visible gene expression reporter (i.e., GFP for MRI) to enable mesoscale neural tracing in vivo. I call this system Manganese Accumulation for Genetically Inducible Contrast (MAGIC) MRI.<sup><a href="https://doi.org/10.64898/2026.04.30.722028">1</a>,<a href="https://doi.org/10.1002/mrm.29993">2</a></sup> MAGIC can operate without exogenous agents, uses routine MRI pulse sequences, and is effective in both the rodent and primate brains, visualizing anterograde projections and retrograde connections over the whole brain. I confirmed that Zip14 transfection produces MAGIC specifically through increased cellular load of Mn<sup>2+</sup> using quantitative MRI parameter mapping and high-resolution in situ mass spectrometry. MAGIC can be amplified two- to five-fold using well-established Mn<sup>2+</sup> supplementation, which enabled MAGIC of the rhesus macaque brain on a clinical 3 Tesla MRI system. MRI is a translational modality, Mn<sup>2+</sup> is necessary for life across species, Zip14 is a human protein, and MAGIC is the first GEMRI system to cross the primate translational barrier. Taken together, MAGIC is becoming a clinically relevant molecular imaging platform.

<figure class="fig-narrow">
<img src="{{ '/assets/images/research/magic.jpg' | relative_url }}" alt="Schematic of AAV delivery of Syn-Zip14 to the caudate putamen, with MAGIC MRI and Zip14 histology in serial coronal sections of the mouse brain" loading="lazy">
</figure>

## Cellular resolution MRI

A frontier for brain MRI is achieving cellular specificity and eventually cellular resolution. Assigning signal to cell types can answer open questions in basic neuroscience and guide novel treatment strategies, yet there are no generally applicable procedures to determine the cell specificity of MRI contrast. Manganese-enhanced MRI (MEMRI) produces layer-specific contrast enabling in vivo visualization of cellular cytoarchitecture, particularly in the cerebellum, as Mn<sup>2+</sup> acts like a natural contrast agent that helps water protons relax faster and appear brighter on T1-weighted scans. By performing near single cell (30-50 µm isotropic) resolution imaging in vivo, I discovered that a single cell type was responsible for cerebellar Mn<sup>2+</sup> uptake.<sup><a href="https://doi.org/10.1016/j.neuroimage.2023.120198">3</a></sup> Quantifying the effects of selective ablation of Purkinje cells or Bergmann glia, I found that the Purkinje cells, not the Bergmann glia, are the primary source of enhancement in the Purkinje cell layer. This combination of high resolution and exquisite contrast led me to ask whether Mn<sup>2+</sup> transport could be genetically controlled to visualize cell populations and their function in living brains.

<figure class="fig-wide">
<img src="{{ '/assets/images/research/cellular-resolution.jpg' | relative_url }}" alt="In vivo MEMRI of the mouse cerebellum at 100, 80, and 50 µm isotropic and 50 and 30 µm in-plane resolution" loading="lazy">
</figure>

## High-throughput screening pipelines for mouse models of human medulloblastoma and Niemann-Pick Type C

Genetically engineered mouse models of sporadic cancers are critical for studying tumor biology and for preclinical testing of therapeutics, but the inherent heterogeneity of sporadic mouse models of medulloblastoma (MB) makes studies of tumor progression and preclinical drug trials difficult without an in vivo imaging readout. I developed an MRI-based pipeline producing high resolution, quantitative information about tumor progression and response to therapy in MB models. Sporadic MB was modeled by inducing expression of an activated form of the Smoothened gene in a small number of cerebellar granule cell precursors (aSmo), and animals were imaged with a protocol optimized for high-throughput. A semi-automated segmentation protocol measured tumor volume without significant deviation from expert manual annotation. Tumor centroids measured at early stages revealed the probable origin of aSmo MB tumors in the lateral cerebellum. I demonstrated the pipeline with a small-scale drug trial targeting tumor associated macrophages, which revealed high heterogeneity in aSmo MB growth, including many cases of spontaneous regression after early progression.<sup><a href="https://doi.org/10.1002/mrm.27904">4</a></sup>

<figure>
<img src="{{ '/assets/images/research/medulloblastoma.jpg' | relative_url }}" alt="Longitudinal MEMRI of a mouse model of medulloblastoma at 3, 8, and 13 weeks of age, with arrows marking the cerebellum and tumor" loading="lazy">
</figure>

Niemann-Pick Type C (NPC) is a rare genetic disorder characterized by progressive cell death, particularly in cerebellar Purkinje cells, with no known cure. Previous imaging studies of NPC mouse models revealed significant brain volume differences between mutant and wild-type animals but stopped short of volumetric comparisons of the cerebellar sub-regions, due in part to insufficient tissue-specific contrast from non-contrast-enhanced T2-weighted MRI. I presented longitudinal MEMRI data from cohorts of wild-type, heterozygote carrier, and homozygote mutant NPC mice. Deformation-based morphometry and MEMRI signal comparisons in the cerebellar cortex, white matter, and nuclei volume revealed significant volume reductions and aberrant sub-regional Mn<sup>2+</sup> uptake over time and across genotypes.<sup><a href="https://doi.org/10.1016/j.neuroimage.2020.116894">5</a></sup> These results motivated study of the cell-specific source of Mn<sup>2+</sup> uptake in the cerebellum.

<figure>
<img src="{{ '/assets/images/research/niemann-pick-c.jpg' | relative_url }}" alt="Cerebellar MEMRI of a wild-type mouse and a Niemann-Pick Type C mouse, showing volume reduction" loading="lazy">
</figure>
