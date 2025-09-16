# FHIR Patient Project

## Overview
This project demonstrates the use of **FHIR (Fast Healthcare Interoperability Resources)** standard to represent healthcare data in JSON format. It includes sample **Patient** and **Organization** resources, which can be used to practice working with FHIR APIs, parsing healthcare data, or testing FHIR servers like [HAPI FHIR](https://hapi.fhir.org/).

---

## Files
- **patient.json**: Contains a sample Patient resource including:
  - Name, gender, birthDate
  - Contact information
  - Address
  - Next of kin information
  - Identifier and managing organization reference

- **organization.json** (optional): Contains sample Organization resource that can be referenced by the Patient.

---

## Purpose
- Learn how to structure FHIR JSON resources.
- Test FHIR API calls (POST, GET) using HAPI FHIR server.
- Understand patient identifiers, contact relationships, and organizational references in FHIR R4.

---

## How to Use
1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/fhir-patient-project.git
