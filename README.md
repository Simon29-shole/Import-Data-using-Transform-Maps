```markdown
# 📥 Import Data Using Transform Maps

**A ServiceNow team project demonstrating data import from external sources into ServiceNow tables using Import Sets and Transform Maps.**

🔗 **Live Demo**: [Watch Demo Video](https://drive.google.com/file/d/1rvitBIzuYuJsYaIU-OKwLdHg8auo2UZi/view?usp=drivesdk)

---

## 📌 Project Overview

This project shows how to load external data (Excel / CSV) into ServiceNow using the standard **Import Set → Transform Map** pipeline.

**What is a Transform Map?**  
A Transform Map defines how data moves from a temporary staging table (Import Set) to a target ServiceNow table (e.g., Users, Incidents, CMDB). It handles field mapping, data cleaning, and duplicate prevention via coalesce fields.

**Who uses this?**  
ServiceNow Administrators, Developers, and Integration Specialists who need to:
- Import bulk data from spreadsheets or external systems
- Migrate data from legacy systems
- Keep records updated without creating duplicates
- Apply business rules and data transformations during import

---

## 🎯 Project Objectives

- Load external data into ServiceNow using Import Sets
- Create and configure Transform Maps
- Map source fields to target table fields
- Prevent duplicate records using Coalesce
- Demonstrate a clean, reusable import process

---

## 🗂️ Project Structure

```text
Import_Data_using_Tranform_Maps/
├── 1. Ideation Phase
├── 2. Requirement Analysis
├── 3. Project Design Phase
├── 4. Project Planning Phase
├── 5. Project Development Phase
├── 6. Project Documentation
└── 7. Project Demonstration
```

📄 **Sample Dataset**: `dataset.xlsx` (root directory)

---

## 🔄 How the Import Process Works

```text
External Data (Excel/CSV)
        ↓
   Data Source
        ↓
 Import Set Table (Staging)
        ↓
   Transform Map
   (Field Maps + Scripts + Coalesce)
        ↓
 Target Table (Final Destination)
```

---

## 🛠️ Key Concepts Covered

| Concept              | Description                                      |
|----------------------|--------------------------------------------------|
| **Import Set**       | Temporary staging table for raw imported data   |
| **Transform Map**    | Rules that map staging fields → target fields   |
| **Field Maps**       | Direct field-to-field mapping                   |
| **Coalesce**         | Prevents duplicates by matching existing records|
| **Transform Scripts**| Custom logic for data cleaning and transformation|

---

---

## 🚀 How to Use This Project

1. Review the phase folders for documentation and design artifacts
2. Use the provided `dataset.xlsx` as the sample source file
3. Follow the demonstration steps in the **Project Demonstration** folder
4. Watch the demo video for a complete walkthrough

---

## 📚 Why This Matters

Transform Maps are a core skill for any ServiceNow professional working with data integration.  
They enable reliable, repeatable, and controlled data imports without writing custom scripts for every load.

---

## 📄 License

This is an academic team project created for learning purposes.
```
