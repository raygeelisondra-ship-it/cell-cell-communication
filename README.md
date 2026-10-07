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

## OmniPath Findings
* OmniPath provides curated directional signaling data showing the relationship between the extracellular ligand PYY and its cognate receptor NPY2R.

---

## STRING Network Interpretation
* **Network Overview:** The STRING network links PYY and NPY2R to downstream intracellular proteins, including inhibitory G-protein subunits (GNAI1, GNAI2) and pathway effectors.
* **Interpretation:** STRING highlights functional associations—meaning these proteins participate in shared biological processes—rather than automatically proving direct physical contact.

---

## IntAct Validation
* **Interaction Data:** IntAct provides experimental records confirming direct physical binding between interacting components in the signaling pathway.

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
