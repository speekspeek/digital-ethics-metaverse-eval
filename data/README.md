# Data Access Instructions

This project uses only **public, fully anonymized datasets**, consistent with Scientific Reports reproducibility requirements.

No raw data is uploaded to this repository due to licensing.

---

## 1. Open University Learning Analytics Dataset (OULAD)

- Dataset homepage: https://analyse.kmi.open.ac.uk/open_dataset  
- License: **CC-BY 4.0**
- Contents:  
  - Student info, course registrations, VLE logs  
  - Assessment submissions  
  - Weekly learning behavior data

Download steps:
1. Visit the dataset homepage  
2. Download the ZIP file  
3. Unzip into your local `data/oulad/` folder  
4. Use `notebooks/01_preprocessing.ipynb` for preprocessing

---

## 2. EdNet Dataset

- Homepage: https://ednet.kaist.ac.kr  
- License: **CC-BY-NC**
- Contents:  
  - Interaction logs  
  - Feedback events  
  - Student attempts  
  - Response correctness  

Download steps:
1. Go to the EdNet homepage  
2. Download "KT1" or "student activity" dataset  
3. Unzip to `data/ednet/`  
4. Process via `notebooks/01_preprocessing.ipynb`

---

## Note

Per journal policy, only data **access instructions** and **processing scripts** are included.  
Raw logs must be downloaded from official publishers.
