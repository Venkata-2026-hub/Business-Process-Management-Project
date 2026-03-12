# Business-Process-Management-Project
Repair Center (RC) business process model


## Project Overview

This repository documents the **Repair Center (RC) business process model** developed as part of an academic project in **Business Process Management (BPM)**.  
The objective of the project was to analyze, design, and model the workflow involved in handling customer device repairs within an organization.

The process was modeled using **BPMN (Business Process Model and Notation)** to visualize interactions between different roles and departments. The model illustrates the **complete repair lifecycle**, starting from receiving the device and ending with returning the repaired device to the customer.


## Process Description

The Repair Center process begins when a **customer submits a device for repair**. The device is logged into the system and a repair case is recorded. The repair agent then analyzes the device to determine the cause of the issue and decide the appropriate repair action.

Based on the analysis results, different scenarios may occur:

- The device is **repaired internally**
- The device is **sent to an external repair partner**
- **Spare parts must be ordered**
- A **repair offer must be approved by the customer**
- The device is **returned without repair or recycled**

Once the repair is completed and the device passes testing, the device is sent back to the customer.

## Key Process Roles

### Customer
- Submits the device for repair
- Receives repair offer if the device is outside warranty
- Accepts or declines repair offer

### Log Inbound
- Receives the device
- Records the repair case in the system

### Repair Agent
- Performs device analysis
- Repairs the device
- Tests the device after repair

### Parts Management
- Orders spare parts if required
- Receives and manages spare parts inventory

### Administration
- Sends repair offers to customers
- Sends reminders when no response is received

### Log Outbound
- Sends the repaired device back to the customer

## Process Flow Overview

Main process steps include:

1. Device received
2. Repair case recorded
3. Device analysis
4. Decision on repair type
5. Spare parts ordering (if needed)
6. Repair execution
7. Device testing
8. Customer approval (if necessary)
9. Device returned to customer

Alternative flows include:
- Sending the device to an external repair partner
- Customer declining the repair offer
- Recycling the device

## Decision Points in the Process

Several decision gateways determine the path of the process:

- Whether the repair can be done internally
- Whether spare parts are required
- Whether the device is under warranty
- Whether the customer accepts the repair offer
- Whether the device should be repaired, returned, or recycled

These decision points make the process flexible and adaptable to different repair scenarios.

## Tools Used for Process Modeling

The business process was modeled using BPM tools and standards commonly used in industry:

- **Camunda Modeler** – used for designing BPMN workflow diagrams
- **Trisotech** – used for professional BPMN modeling and process documentation
- **ADONIS** – used for enterprise process modeling and business architecture
- **BPMN (Business Process Model and Notation)** – standard notation for visualizing workflows

These tools help analysts design, simulate, and analyze business processes to improve efficiency and transparency.

## Learning Outcomes

Through this BPM project, the following skills and knowledge were developed:

- Understanding **Business Process Management concepts**
- Modeling processes using **BPMN standards**
- Identifying **organizational roles and responsibilities**
- Analyzing **decision points and alternative process flows**
- Using professional **process modeling tools**
- Understanding service operation workflows in organizations


