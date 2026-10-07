# Cell-to-cell Communication

## Title and Biological Question
* **Project Title:** Analysis of the PYY-NPY2R Intercellular Signaling Axis
* **Biological Question:** How does Peptide YY (PYY) released from enteroendocrine L-cells activate NPY2R on target receiver cells, and how do database tools support this signaling pathway?

---

## Chosen Sender Cell and Biological Context
* **Sender Cell:** Enteroendocrine L-cell
* **Biological Context:** Found in the mucosal epithelium of the distal gut (ileum and colon). L-cells release the hormone PYY in response to nutrient ingestion to regulate gut motility and energy balance.

---

## Candidate Ligand and Evidence for Sender-Cell Expression
* **Candidate Ligand:** Peptide YY (PYY) 
* **Sender-Cell Evidence:** Data from the Human Protein Atlas and transcriptomic records confirm that the *PYY* gene is actively expressed and stored in enteroendocrine L-cells.

---

## Receptor and Receiver Cell with Supporting Evidence
* **Receptor:** Neuropeptide Y Receptor Type 2 (NPY2R) 
* **Receiver Cell:** Enteric neuron / target gut cell
* **Supporting Evidence:** Single-cell RNA-seq and tissue expression data confirm that NPY2R is present on target receiver cells to mediate hormonal signals.

---

## The Receptor and Receiver Cell

* **OmniPath Findings:** 
  * Searching OmniPath for the ligand PYY (P10082) shows direct cell-to-cell signaling connections with several receptors, most notably **NPY2R** backed by 17 reference sources, as well as NPY4R, NPY5R, and NPY1R.
* **Selected Receptor:** NPY2R (Neuropeptide Y Receptor Type 2).
* **Selected Receiver Cell:** Enteric neuron / local target gut cell.
* **Supporting Evidence:** Human Protein Atlas and single-cell gene records show that NPY2R is strongly expressed in enteric neurons, confirming it is a functional receptor for gut hormone signaling.
* **Signaling Context:** Postprandial endocrine regulation of gut motility and energy balance.

### Functional interpretation
* The enteroendocrine L-cell produces Peptide YY (PYY), which can signal through NPY2R on the enteric neuron in the context of postprandial metabolic and neuroendocrine regulation.”
---

##  Exploring the Receptor-Centered Network in STRING

* **Network Overview:** 
  * The STRING network was generated using *Homo sapiens* data, centered on the receptor **NPY2R**, and includes the ligand **PYY** along with key interacting/signaling proteins (NPY, PPY, GNAI1, GNAI2, GNB1, GNG2, POMC, PRPH2, and TPR).
  * The network size is kept concise (around 10 connected nodes) for straightforward biological interpretation.

* **Enriched Pathway / Biological Process:** 
  * The network shows strong functional enrichment related to **G protein-coupled receptor signaling pathways**, peptide ligand binding, and the regulation of postprandial energy homeostasis and neuroendocrine signaling.

* **Connecting Proteins (Receptor Activation to Cellular Response):**
  * **GNAI1 & GNAI2:** Inhibitory G-protein alpha subunits that couple directly with NPY2R to inhibit adenylyl cyclase activity.
  * **GNB1 & GNG2:** Heterotrimeric G-protein beta and gamma subunits that form complexes with alpha subunits to modulate downstream ion channels.
  * **POMC:** Downstream neuropeptide regulator involved in the central melanocortin system to regulate feeding behavior and energy balance.

---

## Validate One Molecular Interaction in IntAct

* **Selected Protein Pair:** PYY (Peptide YY) and NPY2R (Neuropeptide Y Receptor Type 2).
* **Interacting Molecules & Organism:** The interaction is curated for *Homo sapiens* proteins, showing PYY centrally connected to NPY2R, NPY1R, and other associated proteins.
* **Experimental Evidence & Metrics:**
  * The network interaction between PYY and NPY2R is represented by a thick, dark orange edge, indicating a high MI Score (Molecular Interaction Score) approaching 1.0 and a high volume of supporting evidence layers (#Evidence scaling up toward 25 records.
  * The curation reflects robust experimental detection methods from physical interaction assays stored in the database.
* **Publication & Assay Information:** 
  * **Accession:** EBI-6655749 (IMEX ID: IM-20536-41).
  * **Detection Method:** Scintillation Proximity Assay  under *in vitro* host organism conditions.
  * **Reference:** Bono F. et al., *Cancer Cell*, titled "Inhibition of Tumor Angiogenesis and Growth by a Small-Molecule Multi-FGFR Inhibitor with Allosteric Properties".
* **Nature of Interaction:** The curated IntAct record explicitly supports a direct physical interaction between the PYY ligand and the NPY2R transmembrane receptor, confirming that the molecules physically bind to one another rather than merely participating in a general metabolic pathway.

---

## Final Model and Interpretation
Following nutrient ingestion, L-cells synthesize and secrete Peptide YY (PYY) into the local extracellular environment. PYY acts as a signaling ligand that binds specifically to the NPY2R receptor on receiver cells. Upon binding, NPY2R activates intracellular inhibitory G-protein alpha subunits, specifically GNAI1 and GNAI2, which inhibit adenylyl cyclase and modulate downstream cellular activity, such as regulating gut motility and suppressing neuronal firing.

Using multiple databases provides a balanced view of this signaling axis. The STRING database maps functional associations, highlighting how these proteins work together in broader neuroendocrine regulatory pathways. However, because STRING edges represent functional links rather than guaranteed contact, IntAct data is used to confirm direct physical binding between interacting molecules. Overall, this integrated approach connects tissue-level physiological responses to precise molecular interactions, creating a robust, evidence-based model of peptide hormone signaling.

---

## References and Database Links
* **OmniPath:** [https://explore.omnipathdb.org/search?q=PYY%2C&tab=interactions&species=9606]
* **STRING Database:** [https://string-db.org/cgi/network?taskId=b9mGBQC5a6nI&sessionId=bzI3mmBAAuJc]
* **IntAct Molecular Interaction Database:** [https://www.ebi.ac.uk/intact/search?query=EBI-6655667]
* **Human Protein Atlas:** [https://www.proteinatlas.org/search/enteroendocrine+L+cells]
* **BioRender:** [https://app.biorender.com/illustrations/6ac4fb6ef17af6782a265efc?slideId=b948da39-800a-473d-8126-608ea125e810]
* **PubMed:** Bono F, De Smet F, Herbert C, et al. Inhibition of tumor angiogenesis and growth by a small-molecule multi-FGF receptor blocker with allosteric properties. Cancer Cell. 2013 Apr;23(4):477-488. DOI: 10.1016/j.ccr.2013.02.019. PMID: 23597562
