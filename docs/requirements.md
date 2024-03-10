# Requirements Specification Document

## Project Title: TT06-QRNG

### Project Overview

TT06-QRNG is an experimental attempt at making CMOS quantum circuits using the Skywater 130nm PDK. Preliminary research has indicated such a development task is feasible, albeit challenging and with high risk of failure. The low cost (approx. $150) associated with inclusion the Tiny Tapeout project along with the significant benefit of developing an open-source PDK for quantum ASICs has made this project possible.

#### Purpose

The purpose of TT06-QRNG is to design & experimentally validate a number of silicon-photonic structures and unitary quantum logic gates useful for the implementation of quantum circuits 

####  Objectives

For the Skywater 130nm PDK, design, implement, and validate:

- [ ] A CMOS LED
- [ ] A CMOS Photo Detector
- [ ] A CMOS Wave Guide
- [ ] A CMOS Beam Splitter
- [ ] A Quantum RNG
- [ ] The following logic gates:

  - [ ] Pauli-Hadamard
  - [ ] Pauli-X
  - [ ] Pauli-Y
  - [ ] Pauli-Z

#### Scope

##### Deliverables

- [ ] KiCAD Library Symbols
  - [x] CMOS LED
  - [x] CMOS Photo Detector
  - [x] CMOS Beam Splitter
  - [ ] QRNG
  - [x] Hadamard
  - [x] Pauli-X
  - [x] Pauli-Y
  - [x] Pauli-Z
- [ ] LEF Cell Design
  - [ ] CMOS LED
  - [ ] CMOS Photo Detector
  - [ ] CMOS Wave Guide
  - [ ] CMOS Beam Splitter
  - [ ] QRNG
  - [ ] Hadamard
  - [ ] Pauli-X
  - [ ] Pauli-Y
  - [ ] Pauli-Z 
- [ ] TECH Design Rules
  - [ ] CMOS LED
  - [ ] CMOS Photo Detector
  - [ ] QRNG
  - [ ] Hadamard
  - [ ] Pauli-X
  - [ ] Pauli-Y
  - [ ] Pauli-Z
- [ ] Experimental Schematic
- [ ] Experimental Layout
- [ ] Design & Test Documentation

### Stakeholders
**Project Sponsor:** Spooky Manufacturing
**Enabling Project:** Tiny Tapeout
**Project Manager:** Noah G. Wood
**Development Team:**

- @noahgwood

**End Users:**

- Quantum Computing Researchers
- Hobbyists & Developers

**Subject Matter Experts:** N/A

**Quality Assurance Team:** N/A

**Regulatory Bodies**: N/A

**External Vendors/Suppliers**: 

- EFabless - ASIC manufacturing
- SkyWater - Open-source silicon PDK 

**Customers/End Users**:

- Spooky Manufacturing

**Other Stakeholders**: N/A

### Functional Requirements
1. **Requirement 1**: [Description of the requirement]
    - *Rationale*: [Explanation of why this requirement is necessary]
    - *Acceptance Criteria*: [Criteria that must be met to satisfy this requirement]

2. **Requirement 2**: [Description of the requirement]
    - *Rationale*: [Explanation of why this requirement is necessary]
    - *Acceptance Criteria*: [Criteria that must be met to satisfy this requirement]

[Add additional functional requirements as needed]

### Non-Functional Requirements
1. **Performance**
    - **Requirement**: [Description of the performance requirement]
    - **Acceptance Criteria**: [Criteria for measuring performance]

2. **Reliability**
    - **Requirement**: [Description of the reliability requirement]
    - **Acceptance Criteria**: [Criteria for ensuring reliability]

[Add additional non-functional requirements such as security, usability, scalability, etc.]

### Hardware Requirements
* 1x Tiny Tapeout Board

### Software Requirements
- KiCAD (Schematics)
- Magic VLSI (Layout)
- Typora (Documentation)
- Visual Studio (Other)

### Environmental Requirements
Must operate at standard computing temperatures.

### Testing Requirements
Outline the testing procedures and criteria to be used for validating the project, including unit testing, integration testing, and system testing.

### Documentation Requirements
Sufficient documentation is needed such that the structures developed may be used to implement future designs.

Detail the documentation deliverables expected for the project, including user manuals, technical specifications, and design documents.

### Constraints
1. Limited to 1-3v
2. 1 Tile Limit (approx 160umx100um)
3. 24 pins
4. 1 Chip/Board
5. Completion by April 18th (6 weeks)

### Assumptions
List any assumptions made during the requirements gathering process, including dependencies, risks, or uncertainties.

## Revision History
| Date       | Revisions | Author    | Comment     |
| ---------- | --------- | --------- | ----------- |
| 03/07/2024 | 1         | NoahGWood | Initial Doc |
|            |           |           |             |
|            |           |           |             |
|            |           |           |             |
