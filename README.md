# The Limb Skeletal Cell Atlas

## A single-cell atlas of the murine limb skeleton integrating the developmental and adult stages

This repository contains all notebooks and scripts used to perform the analyses and generate the figures in the Limb Skeletal Cell Atlas [manuscript](https://www.nature.com/articles/s41598-025-05277-6) [[PDF](https://rdcu.be/euD9U)].

### About
Breakthroughs in improving scalability have led to the creation of organism-wide transcriptomic datasets, aiming to comprehensively profile the cell types and states within an organism throughout its lifecycle. To date, however, the skeleton remains a majorly underrepresented organ system in organism-wide atlases. Considering how the skeleton not only serves as the central framework of the vertebrate body but is also the home of the hematopoietic niche and a central player in major metabolic and homeostatic processes, this presents a major deficit in current reference atlas projects. To address this issue, we integrated ten separate scRNA-seq datasets containing limb skeletal cells and their developmental precursors, generating an atlas of 133 332 cells. This limb skeletal cell atlas describes cells across the mesenchymal lineage from the induction of the limb field to the adult bone and encompasses 39 different cell states. 

### Reproducibility
To avoid conflicts between package dependencies, it is strongly recommended to use our [Docker](https://hub.docker.com/r/gnasello/sc-env) environment.

### Web app documentation
The source code of the web app hosted at http://skeletalcellatlas.org/ along with tutorials for running the app locally are aailable at [this repository](https://github.com/mbarzegary/skeletal-cell-atlas)

### Citation
Herpelinck, T._*_, Ory, L._*_, Verbraeken, T. _et al._ A single-cell atlas of the murine limb skeleton integrating the developmental and adult stages. _Sci Rep_ *15*, 22514 (2025). https://doi.org/10.1038/s41598-025-05277-6

### Funding
Research was funded by the Research Foundation Flanders (FWO Vlaanderen) T.H.: 1S80021N, G.N.: 12C5923N, MatheMorphosis: G0D3420N, and FWO-INSITE: G085018N; by the European Union’s Horizon 2020 Framework Program (H2020/2014-2021) ERC INSITE (772418) and SC1-DTH ISW (101016503); by the European Union’s Horizon Europe Framework Program (HEU/2022-2027) ERC INSTant CARMA (101088919), as well as by the special research fund of the KU Leuven (C24/17/077). The funders had no role in study design, data collection and analysis, the decision to publish, or the preparation of the manuscript. 

This work is part of Prometheus, the KU Leuven R&D division for skeletal tissue engineering (http://www.kuleuven.be/prometheus).
