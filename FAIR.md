## FAIR data principles

This workflow was designed with the FAIR principles in mind:

**Findable**
- The repository is hosted publicly (GitHub) with a descriptive README, keywords, and topic tags.
- A `.zenodo.json` file is included so that a GitHub release can be archived on Zenodo, minting a persistent DOI that makes the exact version of this workflow citable and discoverable independently of the repo host.

**Accessible**
- The repository and its data are openly accessible via a standard web protocol (HTTPS, via GitHub/Zenodo) with no login or special access required.
- Data files are provided in CSV so no special software license is needed to read them.
- Metadata (README, `.zenodo.json`, `pollution_metadata.txt`) remain accessible even if the underlying data were ever removed, since metadata and data are stored/described separately.

**Interoperable**
- Data are stored in CSV, a widely supported, non-proprietary tabular format readable by any standard data-analysis tool (pandas, R, Excel, etc.), not just the software used here.
- The analysis code uses widely adopted, standard Python libraries (pandas, numpy, scikit-learn/statsmodels), so the workflow can be understood and adapted using common vocabulary/conventions in the field.

**Reusable**
- Dependencies are pinned to exact versions in `requirements.txt`, so the computational environment can be reconstructed precisely, making results reproducible by others.
- Data provenance and any known limitations are documented (`pollution_metadata.txt`, README), so reusers can judge fitness for purpose.
- The notebooks include descriptive markdown explaining each analytical step, equations, and assumptions, so the workflow is understandable and reusable beyond the original author.