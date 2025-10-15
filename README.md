# Milestone 1: Dataset Preparation

## 1. Data Collection
- Browse open-source platforms like **Kaggle**, **PhysioNet**, and **NIH Databases**.  
- Download openly licensed datasets including **MRI**, **CT**, and **EHR** data.  
- Verify license terms before use.

---

## 2. Data Organization
- Create a root project directory.  
- Inside it, set up the following folders:
  - **`/images/`** → for MRI and CT scans  
  - **`/ehr_notes/`** → for EHR text files or clinical notes  
- Use clear filenames such as `MRI_001.png`, `CT_002.png`, `note_001.txt`.

---

## 3. Documentation
Keep all dataset information well-tracked:

- **`docs/dataset_sources.md`** – dataset origins and download links  
- **`docs/cleaning_steps.md`** – preprocessing details (renaming, format conversion, duplicate removal)  
- **`docs/challenges.md`** – issues faced (missing labels, inconsistent formats, etc.)  
- **`README.md`** – overview of dataset structure and data linkage between images and notes

---

## 4. Dataset Mapping
- Build a mapping file in **Excel** or **Google Sheets** to link files and labels.  
- Recommended columns:
  - `filename`  
  - `modality` (MRI / CT / EHR)  
  - `diagnosis`  
  - `ICD10_code`  
- Fill in the table and export it as **`mapping.csv`** for use in preprocessing or model training.

---

## ✅ Outcome
After Milestone 1, you’ll have a **clean, organized, and fully documented dataset** ready for the next stage of preprocessing and model development.
