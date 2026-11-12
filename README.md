# AI Construction Control
### An AI Assistant for Construction and Technical Documentation Management

Final project for the Building AI course

## Summary

AI Construction Control is a concept of an AI-powered assistant designed to support engineers in the construction industry. It helps analyze technical documentation, compare planned and actual work quantities, identify discrepancies, and check the completeness of construction documents.

## Background

Construction projects involve large amounts of technical and administrative documentation. Engineers in Production and Technical Departments (PTO) spend considerable time checking drawings, specifications, bills of quantities, work completion reports, and as-built documentation.

Many of these tasks are performed manually, which can lead to errors, delays, and inconsistencies between project documentation and actual construction work.

The main problems this project aims to address are:

- Time-consuming manual checks of construction documentation.
- Differences between design quantities, estimated quantities, and actual completed work.
- Errors in Acts of Completed Works (AVR).
- Missing or incomplete as-built documentation.
- Difficulties in tracking changes in design documentation.
- Delays in identifying discrepancies between contractors' reports and project requirements.

My personal motivation comes from my experience in the construction industry and working with technical documentation. I believe that artificial intelligence can help engineers reduce repetitive work, improve accuracy, and make construction project management more efficient.

## How is it used?

AI Construction Control is intended to be used by:

- PTO engineers.
- Construction site engineers.
- Client-side technical supervision and construction management teams.
- Project managers.
- Engineers responsible for checking completed work and documentation.

The proposed system would work as follows:

1. The engineer uploads project documentation, drawings, specifications, bills of quantities, and work completion reports.
2. The AI system extracts relevant information from the documents.
3. The system compares planned work quantities with the quantities reported by contractors.
4. It identifies possible discrepancies, missing information, and inconsistencies.
5. The system checks whether the required as-built documentation is included in the submitted package.
6. The engineer receives a report with detected issues and recommendations for further review.

For example, if a contractor submits an Act of Completed Works (AVR) claiming 500 cubic meters of concrete work, the system could compare this quantity with the relevant project documentation and available supporting records.

If a discrepancy is detected, the system highlights it and asks the engineer to verify the information.

The final decision always remains with the qualified engineer. AI supports the verification process but does not replace professional responsibility.

## Data sources and AI methods

The system could use several types of construction data:

**Data sources:**

- Architectural and structural drawings.
- Project and working documentation.
- Technical specifications.
- Bills of quantities.
- Estimated quantities and cost documentation.
- Acts of Completed Works (AVR).
- As-built and executive documentation.
- Construction schedules.
- Reports submitted by contractors.

The data could come from construction companies, project documentation systems, and authorized project records. For development and testing, anonymized or synthetic data could also be used.

**AI methods:**

1. **Optical Character Recognition (OCR)**

   Used to recognize text, numbers, tables, and other information in scanned documents and drawings.

2. **Natural Language Processing (NLP)**

   Used to analyze technical documents, identify relevant information, and classify documents by type.

3. **Machine Learning**

   Used to identify patterns in construction data and detect unusual differences between planned and reported work quantities.

4. **Anomaly Detection**

   Used to highlight unusual values, possible
