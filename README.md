```markdown
# 🚀 Import Data using Transform Maps | ServiceNow Project

A practical team project demonstrating **data import** into ServiceNow using **Import Sets** and **Transform Maps**.

---

## 📌 Project Overview

This repository documents a complete ServiceNow data import implementation.  
External data (from Excel) is loaded into a staging **Import Set** table, then cleanly mapped and transformed into a target table using **Transform Maps**.

**Why this matters**  
ServiceNow Transform Maps are the standard, reliable way for organizations to bring external data (users, assets, incidents, CMDB records, vendor lists, etc.) into the platform without writing custom code for every import. They are used daily by IT teams, ServiceNow administrators, and integration specialists for bulk data loading, migrations, and ongoing system integrations.

---

## 🎯 What This Project Covers

- Loading data from an Excel file into ServiceNow
- Creating and configuring an **Import Set** (staging table)
- Building a **Transform Map** with field mappings
- Using coalesce to prevent duplicate records
- Running the transform and verifying results
- Full project documentation across all phases

---

## 🔗 Live Demo

▶️ **[Watch the Project Demonstration](https://drive.google.com/file/d/1rvitBIzuYuJsYaIU-OKwLdHg8auo2UZi/view?usp=drivesdk)**

---

## 📁 Repository Structure

```
Import_Data_using_Tranform_Maps/
├── 1. Ideation Phase
├── 2. Requirement Analysis
├── 3. Project Design Phase
├── 4. Project Planning Phase
├── 5. Project Development Phase
├── 6. Project Documentation
└── 7. Project Demonstration
```

📄 **Dataset used**: [`dataset.xlsx`](dataset.xlsx)

---

## 🛠️ Technology & Platform

| Component              | Details                          |
|------------------------|----------------------------------|
| Platform               | ServiceNow                       |
| Core Feature           | Import Sets + Transform Maps     |
| Data Source            | Excel (`.xlsx`)                  |
| Key Concepts           | Staging Table, Field Mapping, Coalesce |

---

---

## 📚 Key Concepts Explained

| Term                | Meaning |
|---------------------|---------|
| **Import Set**      | Temporary staging table that holds raw imported data |
| **Transform Map**   | Rules that map and transform data from the staging table to the target table |
| **Field Map**       | Individual source → target field mapping |
| **Coalesce**        | Matching logic that updates existing records instead of creating duplicates |
| **Target Table**    | Final ServiceNow table where clean data is stored |

---

## ✅ Project Highlights

- Clean, structured documentation across 7 phases
- Real Excel dataset used for import
- Practical demonstration of ServiceNow’s standard data import process
- Focus on best practices (coalesce, field mapping, verification)

---

## 📖 How to Explore This Repo

1. Start with the **Ideation** and **Requirement Analysis** folders
2. Review the **Design** and **Planning** documents
3. Check the **Development** phase for implementation details
4. Watch the **Demo** video linked above
5. Refer to the **Documentation** folder for final reports

---

## 💡 Who Is This Useful For?

- ServiceNow beginners learning Import Sets & Transform Maps
- Students working on ServiceNow academic projects
- IT professionals who need a clear reference for data import processes
- Teams preparing for ServiceNow CSA / CAD related topics

---

## 📄 License

This is an educational team project.

```
