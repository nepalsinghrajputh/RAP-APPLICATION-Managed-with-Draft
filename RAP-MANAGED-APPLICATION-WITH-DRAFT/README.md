# 🚀 SAP RAP Managed Application with Draft

<p align="center">

![SAP](https://img.shields.io/badge/SAP-S%2F4HANA-0FAAFF?style=for-the-badge&logo=sap)
![ABAP](https://img.shields.io/badge/ABAP-RAP-blue?style=for-the-badge)
![OData](https://img.shields.io/badge/OData-V4-success?style=for-the-badge)
![Fiori](https://img.shields.io/badge/SAP-Fiori-important?style=for-the-badge)
![Draft](https://img.shields.io/badge/RAP-Draft-orange?style=for-the-badge)

**Enterprise Billing Management Application built using SAP RAP Managed Scenario with Draft**

</p>

---

# 🌟 Overview

This repository demonstrates a complete **SAP RAP Managed Application with Draft** developed on **SAP S/4HANA** using **OData V4** and **SAP Fiori Elements**.

The application showcases modern ABAP development practices including CDS View Entities, Behavior Definitions, Behavior Implementations, Draft Handling, Feature Control, Validations, Side Effects, Authorization, and Header–Item composition.

---

# ✨ Features

| Feature | Status |
|---------|:------:|
| Managed RAP BO | ✅ |
| Draft Enabled | ✅ |
| Header–Item Composition | ✅ |
| OData V4 | ✅ |
| SAP Fiori Elements | ✅ |
| Metadata Extensions | ✅ |
| Determinations | ✅ |
| Header Validations | ✅ |
| Item Validations | ✅ |
| Side Effects | ✅ |
| Instance Feature Control | ✅ |
| Global Authorization | ✅ |
| Smart Filter Bar | ✅ |
| Default Selection Values | ✅ |
| Sort & Group | ✅ |
| Value Helps | ✅ |

---

# 🏗️ RAP Architecture

```text
SAP Fiori Elements
        │
OData V4 Service Binding
        │
Service Definition
        │
Projection CDS Views
        │
Projection Behavior
        │
Root CDS View Entity
        │
Managed Behavior Definition
        │
Behavior Implementation
        │
Database Tables
```

---

# 📂 Project Structure

```text
Abstract_View/
Basic_Views/
Root_Views/
Projection_Views/
BO/
BO_CLASS/
Metadata_Extensions/
Draft_Tables/
Tables/
Domains/
Value_Help_Views/
Service_Defination/
Service_Binding/
Service_Testing/
```

---

# 🔄 Draft Lifecycle

```text
Create
  │
  ▼
Draft Instance
  │
  ├── Activate ──► Active Table
  │
  └── Leave App ─► Draft Table
                    │
                    ▼
              Resume Draft
```

---

# ⚙️ Implemented Functionalities

## Draft
- Create, Edit, Resume, Activate and Discard Draft

## CRUD
- Create, Read, Update and Delete for Header and Items

## Smart Filter Bar
- Default Currency values
- Sort by Currency
- Group by Billing Type

## Side Effects
- Material Description automatically refreshes when Material changes.

## Validations

### Header
- Create Validation
- Update Validation

### Item
- Create Validation
- Update Validation

## Feature Control
- Dynamic Edit
- Dynamic Delete
- Dynamic Create Item
- Status Based UI Control

## Authorization
- Global Authorization
- Instance Authorization

---

# 📚 RAP Concepts Covered

- Managed RAP
- Draft
- CDS View Entity
- Behavior Definition
- Behavior Implementation
- Metadata Extension
- OData V4
- SAP Fiori Elements
- Determinations
- Validations
- Side Effects
- Feature Control
- Value Help
- Header–Item Composition

---

# 📸 Screenshots

Add screenshots for:
- List Report
- Object Page
- Draft Creation
- Draft Activation
- Side Effects
- Validation Messages

---

# 🚀 How to Run

1. Import repository into SAP.
2. Activate DDIC objects.
3. Activate CDS Views.
4. Activate Behavior Definitions.
5. Activate Behavior Implementations.
6. Activate Metadata Extensions.
7. Publish Service Binding.
8. Launch SAP Fiori Elements.

---

# 🔮 Future Enhancements

- RAP Actions
- Factory Actions
- RAP Functions
- EML Examples
- SAP Build Process Automation Integration

---

# 👨‍💻 Author

**Nepal Singh Bhayal**

SAP ABAP Consultant

⭐ If this project helped you, consider giving it a Star.
