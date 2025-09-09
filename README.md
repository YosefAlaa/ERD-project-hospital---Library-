# ERD-project-hospital---Library-
Double ERD Projects
# ERD Projects – Library & Hospital Management Systems

This repository contains two complete **Entity Relationship Diagram (ERD)** projects:

1. **Library Management System**
2. **Hospital Management System**

---

## 📚 Library Management System – ERD Overview

**Entities:**
- **Book** – ISBN (PK), Title, Price, Publication Year
- **Author** – A-ID (PK), Name, Nationality
- **Member** – M-ID (PK), Name, Address, Phone, Date of Birth
- **Staff** – S-ID (PK), Name, Position, Hire Date
- **Section** – S-ID (PK), SectionName, Location
- **Dependent** – DependentName, BirthDate, Relation

**Key Relationships:**
- Author **writes** Books (M:N)
- Member **borrows** Books (M:N)
- Staff **manages** Sections (1:1)
- Book **belongs** to Section (M:1)
- Member **has** Dependents (1:M)

---

## 🏥 Hospital Manageme

