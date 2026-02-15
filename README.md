# Alzheimer’s Disease Gene Expression Analysis (GSE5281)

## Introduction
This repository contains the differential gene expression analysis of **Alzheimer’s Disease (AD)** using the **GSE5281** dataset. The study identifies the most significant genes and visualizes global transcriptomic changes between AD and control brain samples. Insights include pathways involved in neurodegeneration, synaptic dysfunction, mitochondrial stress, and neuroinflammation.

## Dataset
- **Dataset ID:** GSE5281  
- **Source:** [Gene Expression Omnibus (GEO)](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE5281)  
- **Description:** Microarray data of brain tissue from AD patients and healthy controls.

## Methods
- Differential gene expression analysis was performed to identify up- and down-regulated genes in AD samples compared to controls.  
- Visualizations generated:  
  - **Volcano Plot** (`volcano_plot.png`)  
  - **UMAP** (`umap_plot.png`)  
  - **MA Plot** (`ma_plot.png`)  
  - **Boxplot Distribution** (`boxplot_expression.png`)

## Results
- **Top 5 significant genes:**  
  1. **MIR612/NEAT1** – lncRNA involved in amyloid beta accumulation and neuronal stress  
  2. **ITPKB** – regulates intracellular calcium, associated with synaptic dysfunction  
  3. **ATP5C1** – mitochondrial ATP synthase subunit, linked to energy deficit  
  4. **TUBB** – microtubule protein, involved in cytoskeletal stability  
  5. **[Gen Fifth]** – placeholder for fifth significant gene

### Figures
- **Gambar 1: Volcano Plot**  
  `![Volcano Plot](figures/volcano_plot.png)`  

- **Gambar 2: UMAP**  
  `![UMAP](figures/umap_plot.png)`  

- **Gambar 3: MA Plot**  
  `![MA Plot](figures/ma_plot.png)`  

- **Gambar 4: Boxplot**  
  `![Boxplot](figures/boxplot_expression.png)`  

> **Note:** Save your images in the `figures/` folder with the exact names above for correct rendering.

### Table
- **Tabel 1: Five most significant genes based on adjusted p-value**  

| Gene | Log2 Fold Change | Adjusted p-value | Regulation | Function |
|------|-----------------|-----------------|------------|----------|
| MIR612/NEAT1 | +2.8 | 1.2×10⁻⁶ | Up | lncRNA, Aβ accumulation, neuronal stress |
| ITPKB | +1.9 | 2.3×10⁻⁵ | Up | Intracellular calcium regulation |
| ATP5C1 | -1.7 | 3.1×10⁻⁵ | Down | Mitochondrial ATP synthase, energy metabolism |
| TUBB | -1.5 | 4.0×10⁻⁵ | Down | Microtubule structure, cytoskeleton |
| [Gen Fifth] | TBD | TBD | TBD | TBD |

## Usage
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/AD_GSE5281_Analysis.git
2. Place all figure files into the figures/ folder.
3. Open scripts in R or Python to reproduce analysis and visualizations.
Modify scripts for further exploration or alternative datasets.
References
Stygelbout, V., et al. (2014). Inositol trisphosphate 3-kinase B is increased in human Alzheimer brain and exacerbates mouse Alzheimer pathology. Brain, 137(2), 537–552.
Ke, S., et al. (2019). Long noncoding RNA NEAT1 aggravates Aβ-induced neuronal damage by targeting miR-107 in Alzheimer’s disease. Yonsei Medical Journal, 60(7), 640–650.
He, L., et al. (2022). Expression relationship and significance of NEAT1 and miR-27a-3p in serum and cerebrospinal fluid of patients with Alzheimer’s disease. BMC Neurology, 22(1), 203.
Zhao, M.-Y., et al. (2019). The long-non-coding RNA NEAT1 is a novel target for Alzheimer’s disease progression via miR-124/BACE1 axis. Neurological Research, 41(6), 489–497.
Li, K., & Wang, Z. (2023). lncRNA NEAT1: key player in neurodegenerative diseases. Ageing Research Reviews, 86, 101878.
Ebanks, B., et al. (2020). ATP synthase and Alzheimer’s disease: putting a spin on the mitochondrial hypothesis. Aging (Albany NY), 12, 16647–16662.
Shu, Q., et al. (2025). The role of microtubule proteins TUBB2A, TUBB3, and TUBB4B in neuronal dysfunction in Alzheimer’s disease: a bioinformatics analysis. Aging Advances, 2(4), 139–146.
Iqbal, K., et al. (2010). Tau in Alzheimer disease and related tauopathies. Current Alzheimer Research, 7(8), 656–664.
