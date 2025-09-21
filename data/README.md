# Data

This folder is **not tracked** in Git (no raw datasets are uploaded here).

## Datasets used
- **PALM-4U (LES benchmark)**  
  Link: https://palm.muk.uni-hannover.de/  
- **AIJ pedestrian-wind**  
  Link: https://www.aij.or.jp/jpn/publish/cfdguide/  
- **CODASC street canyons**  
  Link: https://doi.org/10.34735/pik-codas  
- **JU2003 field campaign**  
  Link: https://www.ju2003.de/  
- **Lab CFD (URANS/LES)**  
  Produced by our group (contact authors).

## How to prepare
1. Download raw datasets to `data/raw/`.
2. Run preprocessing:
   ```bash
   python src/utils/preprocess.py --input data/raw --output data/processed
