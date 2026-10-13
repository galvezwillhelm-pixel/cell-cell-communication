# Individual Cell-to-Cell Communication Laboratory

## Proposed Skeletal Muscle–Liver Cell-to-Cell Communication Through IL-6

### Biological Question

How can a skeletal muscle cell communicate with a hepatocyte through interleukin-6 (IL-6) during exercise, and what signaling pathway may mediate the cellular response?

---

## 1. Chosen Sender Cell and Biological Context

### Sender Cell
**Skeletal muscle cell (myocyte)**

### Biological Context
**Exercise and skeletal muscle contraction**

Skeletal muscle cells can function as signaling cells by producing and releasing myokines. In this investigation, skeletal muscle is the selected sender cell and exercise is the biological context.

---

## 2. Candidate Ligand and Evidence for Sender-Cell Expression

### Signaling Molecule
**Interleukin-6 (IL-6)**

### Official Gene/Protein Name
**IL6**

A peer-reviewed source reports that skeletal muscle fibers express and release IL-6 during and after exercise. This supports IL-6 as a signaling molecule produced by the selected skeletal muscle sender cell.

### Type of Signaling

**Endocrine-like signaling**

The proposed communication is endocrine-like because IL-6 released from skeletal muscle can enter the circulation and act on a distant tissue such as the liver.

### Evidence

The supporting peer-reviewed source is:

*Skeletal muscle as an endocrine organ: PGC-1α, myokines and exercise.*

### Evidence File

`figures/01_sender_cell_evidence.jpg`

---

## 3. Receptor and Receiver Cell

### Receiver Cell
**Hepatocyte (liver cell)**

### Receptor System

- **IL6R** – Interleukin-6 receptor
- **IL6ST** – Interleukin-6 signal transducer (gp130)

IL-6 binds IL6R, while IL6ST/gp130 functions as the signal-transducing receptor component.

Human Protein Atlas evidence supports IL6R expression in hepatocytes, making the hepatocyte a biologically reasonable receiver cell.

### Checkpoint Model

The skeletal muscle cell produces and releases IL-6, which can signal through the IL-6 receptor complex involving IL6R and IL6ST on hepatocytes in the context of exercise-related communication.

### Supporting Evidence

`hpa_receptor_expression.jpg`

---

## 4. OmniPath Findings

OmniPath was used to examine the intercellular signaling roles and relationships of IL-6 and its receptor components.

The following relationships were identified:

- **IL6 → IL6R**
- **IL6 → IL6ST**
- **IL6R → IL6ST**

The OmniPath results support IL6 as a signaling ligand and IL6R as a receptor. The results also provide directed signaling relationships involving IL6, IL6R, and IL6ST.

These database relationships support the proposed ligand-receptor system. However, database annotations do not by themselves prove that signaling occurs between the selected cell types under every physiological condition.

### Main Evidence File

`figures/02_omnipath_evidence.png`

### Additional Evidence

`omnipath_relationships.jpg`

---

## 5. STRING Network Interpretation

STRING was used to investigate proteins associated with the IL6 receptor-centered signaling system.

The resulting network contained **11 proteins and 34 edges**.

Important proteins relevant to the proposed signaling pathway include:

- **IL6R**
- **IL6ST**
- **JAK1**
- **JAK2**
- **STAT3**

The proposed intracellular signaling sequence is:

**IL6R/IL6ST → JAK1/JAK2 → STAT3 → gene expression**

### Enriched Biological Process

**Interleukin-6-mediated signaling pathway**

**GO:0070102**

**FDR: 2.70 × 10⁻¹²**

This enriched process is consistent with the proposed IL-6 signaling mechanism.

### STRING Interpretation

STRING associations represent functional protein associations and do not automatically prove direct physical binding or establish pathway direction. Therefore, the STRING network was interpreted together with OmniPath, IntAct, and biological knowledge.

### Main Evidence File

`figures/03_string_network.jpg`

### Additional Evidence

`string_enrichment.jpg`

---

## 6. IntAct Validation

The molecular interaction examined in IntAct was:

**IL6 – IL6R**

### IntAct Record

**Accession:** EBI-9007446

**Interaction Type:** Physical association

**Detection Method:** Pull down

**Experimental Context:** In vitro

**Positive Interaction:** Yes

**Publication PMID:** 11238858

The IntAct record provides experimental evidence supporting a physical association between IL6 and IL6R. The evidence was obtained using a pull-down detection method in an in vitro experimental context.

The interaction should be interpreted within its experimental context and does not by itself prove that the interaction occurs specifically between skeletal muscle cells and hepatocytes during exercise.

### Main Evidence File

`figures/04_intact_evidence.jpg`

### Additional Evidence

`intact_interaction_viewer.jpg`

---

# 7. Final Cell-to-Cell Communication Model

The proposed communication pathway is:

**Skeletal muscle cell**

↓

**IL-6**

↓

**Extracellular space / circulation**

↓

**IL6R + IL6ST (gp130) on hepatocyte**

↓

**JAK1 / JAK2**

↓

**STAT3**

↓

**Nucleus**

↓

**Altered gene expression**

↓

**Acute-phase response**

### Final Model Figure

`figures/05_final_model.jpg`

---

## 8. Interpretation of the Final Model

During exercise, contracting skeletal muscle cells can produce and release interleukin-6 (IL-6), which acts as a myokine. In the proposed model, IL-6 is released from skeletal muscle and travels through the circulation to a hepatocyte. The hepatocyte is a reasonable receiver because IL6R expression is supported in hepatocytes. IL-6 binds to IL6R and signals through the IL6ST (gp130) receptor component. This activates intracellular signaling involving JAK1, JAK2, and STAT3, which can influence gene expression in the nucleus. The expected cellular response is an acute-phase response, including increased production of acute-phase proteins. OmniPath supports signaling relationships involving IL6, IL6R, and IL6ST, while STRING identifies proteins associated with IL-6 signaling and shows enrichment of the interleukin-6-mediated signaling pathway. IntAct provides experimental evidence for an IL6–IL6R physical association detected using a pull-down method in an in vitro experimental context. These databases support important parts of the proposed pathway, although database associations do not prove that every interaction occurs specifically in skeletal muscle-to-hepatocyte communication under every condition. Therefore, the final diagram represents an evidence-supported biological model with some steps remaining as inference.

---

# 9. Questions and Answers

### 1. What sender cell did you choose, and in what tissue or biological context does it act?

The sender cell selected was the **skeletal muscle cell (myocyte)**. The biological context is **exercise**, particularly during skeletal muscle contraction. Skeletal muscle can function as a signaling tissue by producing and releasing myokines such as IL-6.

### 2. What signaling molecule did you identify, and what evidence supports its production or presentation by the sender cell?

The signaling molecule identified was **interleukin-6 (IL-6), encoded by the IL6 gene**. Evidence from a peer-reviewed source shows that skeletal muscle fibers can express and release IL-6 during and after exercise. Therefore, IL-6 is a biologically reasonable signaling molecule produced by the selected sender cell.

### 3. What receptor receives the signal, and which receiver cell did you select?

The selected receiver cell is the **hepatocyte (liver cell)**. The receptor system consists of **IL6R** and **IL6ST (gp130)**. IL-6 binds IL6R, while IL6ST functions as the signal-transducing receptor component. Human Protein Atlas evidence supports IL6R expression in hepatocytes.

### 4. What type of cell-to-cell signaling is represented?

The proposed communication is primarily **endocrine-like signaling**, because IL-6 released from contracting skeletal muscle can enter the circulation and act on a distant tissue such as the liver.

### 5. Which proteins in your STRING network appear most relevant to the receptor-associated response?

The most relevant proteins are **IL6ST, JAK1, JAK2, and STAT3**. IL6ST is part of the IL-6 receptor system, while JAK1 and JAK2 are associated with intracellular signal transmission. STAT3 is an important downstream signaling protein that can influence gene expression.

### 6. What enriched pathway or biological process is consistent with your proposed mechanism?

The most relevant enriched process was the **interleukin-6-mediated signaling pathway (GO:0070102)**. The STRING analysis showed an **FDR of 2.70 × 10⁻¹²**, providing strong statistical support that the network is associated with IL-6 signaling.

### 7. What did IntAct show for the molecular interaction you examined? What type of evidence was reported?

IntAct record **EBI-9007446** showed an interaction between **IL6 and IL6R**. The interaction was classified as a **physical association** and was detected using a **pull-down** method in an **in vitro** experimental context. The record was associated with **PMID 11238858**.

### 8. Which parts of your final model are strongly supported, and which parts remain an inference?

The production and release of **IL-6 by skeletal muscle during exercise** is supported by published evidence. The IL6–IL6R interaction is supported by IntAct experimental evidence, while OmniPath supports signaling relationships involving **IL6, IL6R, and IL6ST**. STRING also supports the association of the selected proteins with IL-6 signaling. However, the complete skeletal muscle → IL-6 → hepatocyte → JAK1/JAK2 → STAT3 → acute-phase response sequence represents an integrated biological model. The exact occurrence and strength of every step specifically between these chosen cells and under the selected exercise conditions remain an inference.

### 9. What cellular response is expected in the receiver cell, and why?

The expected response in the hepatocyte is **altered gene expression associated with the acute-phase response**, including increased production of acute-phase proteins. This is consistent with the proposed IL-6 signaling pathway through IL6R/IL6ST and downstream JAK-STAT3 signaling.

---

# 10. References and Database Sources

### Human Protein Atlas
Used to examine protein expression and support the choice of the receiver cell.

### OmniPath
Used to examine intercellular signaling roles and signaling relationships.

### STRING
Used to examine functional protein associations and pathway enrichment.

### IntAct
Used to examine the curated IL6–IL6R molecular interaction and its experimental evidence.

### Peer-Reviewed Source

*Skeletal muscle as an endocrine organ: PGC-1α, myokines and exercise.*

---

# 11. Evidence Files

The repository contains the following primary evidence files:

1. `figures/01_sender_cell_evidence.jpg`
2. `figures/02_omnipath_evidence.png`
3. `figures/03_string_network.jpg`
4. `figures/04_intact_evidence.jpg`
5. `figures/05_final_model.jpg`

Additional supporting screenshots:

- `hpa_receptor_expression.jpg`
- `omnipath_relationships.jpg`
- `string_enrichment.jpg`
- `intact_interaction_viewer.jpg`

---

# 12. Database Interpretation Note

Database presence is evidence, not proof that an interaction occurs in every cell type or physiological condition.

Expression of a ligand or receptor does not by itself prove that signaling occurs between the chosen cells.

A STRING association does not automatically represent direct binding or pathway direction.

An IntAct record should be interpreted together with its experimental method, experimental context, and publication information.

The final model therefore separates observations supported by databases and published evidence from biological inferences made by integrating those observations.
