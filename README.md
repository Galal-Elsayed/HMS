# HMS (Hospital Management System) - Odoo Module

## Overview
This module provides a Hospital Management System (HMS) for Odoo, designed to manage hospital operations such as departments, doctors, patients, and logs. It also includes reporting and access control features.

## Features
- Manage hospital departments
- Manage doctors and their information
- Manage patients and their medical records
- Patient status reporting
- Access control and security groups
- Integration with Odoo's partner model

## Installation
1. Copy the `hms` directory into your Odoo `addons` folder.
2. Update the app list in Odoo.
3. Install the "HMS" module from the Odoo Apps menu.

## Usage
- Navigate to the HMS menu in Odoo after installation.
- Use the provided menus to manage departments, doctors, and patients.
- Generate patient status reports as needed.

## Module Structure
```
hms/
  ├── __init__.py
  ├── __manifest__.py
  ├── models/
  │     ├── __init__.py
  │     ├── department.py
  │     ├── doctor.py
  │     ├── log.py
  │     ├── patient.py
  │     └── res_partner.py
  ├── report/
  │     ├── patient_status_report.xml
  │     └── report.xml
  ├── security/
  │     ├── hms_groups.xml
  │     ├── hms_record_rules.xml
  │     └── ir.model.access.csv
  ├── views/
  │     ├── department_views.xml
  │     ├── doctor_views.xml
  │     ├── patient_views.xml
  │     ├── res_partner_view.xml
  │     ├── templates.xml
  │     └── views.xml
  └── README.md
```

## Author
Galal Elsayed
---