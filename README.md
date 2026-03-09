# Hazardous Materials (B3) Inbound Logistics & Safety Control

### 📌 Overview
This repository contains a comprehensive business process model for the inbound logistics of Hazardous Materials (B3) within a manufacturing environment. The model is designed using **Camunda Modeler** and follows strict **BPMN 2.0** standards.

### 🎯 Business Objective
The goal of this process is to ensure that every hazardous material entering the facility is strictly validated for safety (MSDS compliance) and physical integrity before reaching the production line, minimizing environmental and operational risks.

### 🛠 Technical Implementation
- **Lanes:** Procurement, Warehouse & HSE, Production.
- **Key Mechanics:**
  - **Exclusive Gateways (X):** Used for decision-making (e.g., Document Validation & Shipment Approval).
  - **Boundary Events (Error/Escalation):** Implemented to handle "Spill/Leakage" scenarios during inspection.
  - **Timer Events:** Used for re-testing protocols or waiting periods.

### 📂 Files
- `B3-Logistics-Process.bpmn`: The source file for Camunda Modeler.
- `B3-Logistics-Process.svg`: High-resolution export of the diagram.

### 👤 Author
**Created by ATitanni, March 9, 2026**
*Senior QA Engineer | Aspiring Business Analyst*
