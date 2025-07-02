# DFTB Mono- and Bimetallic AgPt Cluster Slater-Koster Files

This repository contains ground state (GS) and excited state (ES) Slater-Koster parameter files in DFTB+ format for monometallic and bimetallic silver-gold (Ag-Pt) clusters.

## 📁 File Structure:
- **GSSK/** – Ground state Slater-Koster files
- **ESSK/** – Excited state Slater-Koster files
- - **Pt13/** – XYZ files for the icosahedra and cuboactahedra (Ico and Cubo) platinum (13-atoms) nanoclusters
- - **Pt14/** – XYZ files for the octahedron (Oh) platinum (14-atoms) nanoclusters
- **AgPt20alloys/** – XYZ files for the tetrahedra (Td) silver and platinum (20-atoms) nanoclusters and their AgPt nanoalloys
- **AgPt38alloys/** – XYZ files for the truncated octahedron (TOh) silver and platinum (38-atoms) nanoclusters and their AgPt nanoalloys
- **AgPt55alloys/** – XYZ files for the icosahedra (Ih or Ico) silver and platinum (55-atoms) nanoclusters and their AgPt nanoalloys
- **AgPt1099alloys/** – XYZ files for the nanocube (NC) silver and platinum (1099-atoms) nanoclusters and their AgPt nanoalloys

## Supporting Files Description

The GS and ES Slater-Koster parameter files, containing the final parameters for monometallic and bimetallic clusters, are included in the `GSSK` and `ESSK` folders.

### Ground State Slater-Koster Files
The `GSSK` folder contains the Slater-Koster parameter files for ground state calculations:

- `Ag-Ag-GS-SK.skf`
- `Au-Au-GS-SK.skf`
- `Ag-Au-GS-SK.skf`
- `Au-Ag-GS-SK.skf`

### Excited State Slater-Koster Files
The `ESSK` folder contains the Slater-Koster parameter files for excited state calculations:

- `Ag-Ag-ES-SK.skf`
- `Au-Au-ES-SK.skf`
- `Ag-Au-ES-SK.skf`
- `Au-Ag-ES-SK.skf`

### Example Input Files
Example input files for running ground state and excited state calculations are included in the `INPUT_files` folder.

---


## 📖 Citation
If you use these files in your research, please cite:

**Kumawat and Schatz, Efficient Modeling of Structural, Electronic, and Optical Properties of Silver and Gold Metal Nanoclusters and Alloys Using Optimized SCC-DFTB Parameters, *Journal of Physical Chemistry C*, 2025**  
[![DOI](https://zenodo.org/badge/DOI/10.1021/acs.jpcc.4c08100.svg)](https://doi.org/10.1021/acs.jpcc.4c08100)

### BibTeX:
```bibtex
@article{kumawat2025efficientoptical,
  author = {Kumawat, Rameshwar and Schatz, George},
  title = {Efficient Modeling of Structural, Electronic, and Optical Properties of Silver and Gold Metal Nanoclusters and Alloys Using Optimized SCC-DFTB Parameters},
  journal = {Journal of Physical Chemistry C},
  year = {2025},
  volume = {129},
  number = {2},
  pages = {1348–1361},
  doi = {10.1021/acs.jpcc.4c08100}
  publisher={ACS Publications}
}
