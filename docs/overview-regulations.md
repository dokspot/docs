---
id: overview-regulations
title: Overview of eIFU Regulations
sidebar_label: Regulations
---

## Purpose

This dokspot document represents the current know-how status of dokspot GmbH about international standards and regulations for eIFU.

## International Regulations

In general all international regulations for digital IFU (eIFU) for medical devices and/or IVD devices require:

1. that the device is used in a healthcare setting by healthcare professional
2. a risk assessment before introduction of digital IFU
3. that users of the device can obtain a printed version of the instructions on request free of charge

The following table summarizes these regulations and provides links to sources:

| Region | Status | Resources |
|--------|--------|-----------|
| Australia | ✅ | [Electronic Instructions for Use (eIFU)](https://www.tga.gov.au/publication/electronic-instructions-use-eifu)<br>[Patient Cards and Leaflets](https://www.tga.gov.au/publication/medical-device-patient-cards-and-leaflets) |
| New Zealand | ✅ | Usually follows EU and Australian Guidelines |
| China | ❌ | No written guideline available to date. |
| Brasil | ✅ | [Normative Instruction-IN N°4, OF June 15th, 2012](https://www.legisweb.com.br/legislacao/?id=242406) |
| Japan | ✅ | Based on EMDA Japan has accepted digital IFU. |
| European Union | ✅ | [EU Regulation 207/2012](http://eur-lex.europa.eu/LexUriServ/LexUriServ.do?uri=OJ:L:2012:072:0028:0031:en:PDF) |
| Switzerland | ✅ | [EU Regulation 207/2012](http://eur-lex.europa.eu/LexUriServ/LexUriServ.do?uri=OJ:L:2012:072:0028:0031:en:PDF) |
| Turkey | ✅ | [Electronic Instructions for Use (eIFU)](http://www.resmigazete.gov.tr/eskiler/2015/04/20150402-14.htm) |
| Saudi Arabia | ✅ | [Electronic Instructions for Use (eIFU)](http://www.sfda.gov.sa/en/medicaldevices/regulations/DocLib/Guidance-Document-Labeling-v1-18_01_2015(MDS%E2%80%93G10).pdf) |
| USA | ✅ | [FDA Blue Book Memorandum](https://www.fda.gov/inspections-compliance-enforcement-and-criminal-investigations/warning-letters/section-206-medical-device-user-fee-and-modernization-act-mdufma-new-section-502f-federal-food-drug)<br>[MDUFMA](https://www.fda.gov/industry/medical-device-user-fee-amendments-mdufa/medical-device-user-fee-and-modernization-act-2002-mdufma-pl-107-250) |
| India | ✅ | [Electronic Instructions for Use (eIFU)](https://mtaiindia.org/acceptance-of-eifu-for-medicaldevice-a-welcome-move/) |
| Canada | ✅ | [Guidance Document](https://www.canada.ca/en/health-canada/services/drugs-health-products/medical-devices/application-information/guidance-documents/guidance-labelling-medical-devices-including-vitro-diagnostic-devices-appendices.html) |

## International Standards

This chapter lists international standards that may apply for the implementation of electronic instructions for use for a medical device:

- REGULATION (EU) 2017/745 OF THE EUROPEAN PARLIAMENT AND OF THE COUNCIL
of 5 April 2017 on medical devices, amending Directive 2001/83/EC, Regulation (EC) No 178/2002 and Regulation (EC) No 1223/2009 and repealing Council Directives 90/385/EEC and 93/42/EEC
- REGULATION (EU) 2017/746 OF THE EUROPEAN PARLIAMENT AND OF THE COUNCIL of 5 April 2017 on in vitro diagnostic medical devices and repealing Directive 98/79/EC and Commission Decision 2010/227/EU

- ISO13485 Third Edition 2016-03-01. Sections 4.1.6 and 7.5.6 to be considered for a eIFU computer system.

- 22 CFR Part 11 - Describes the requirements of the US legal system for compliance of electronic records and signatures. For a eIFU Computer System this includes the following(*):
  - SOPs (training)
  - System Features
  - General Security
  - Data Transfer
  - Audit Trails
  - Electronic Signatures
  - Infrastructure Qualification
  - Validation
  - Software Validation (COTS vendor)
  - Computer System Validation (users)

- GAMP - Good Automated Manufacturing Practice Forum (GAMP) is a private group that defines requirements for computer systems used for manufacturing, supply and operation of medical devices. GAMP sorts these computer systems in five categories:
  - Operating Systems (OS) - validation not required. Assumes validation of the software application indirectly validates the OS.
  - Standard Instruments - minimal validation; record configuration and verify operation
  - Standard Software Packages (e.g., database, spreadsheet) - validation of the software is not required but validation of applications made with it are validated as COTS or custom based on complexity 
  - Configurable Software Packages (e.g., LIMS, Document Management) - vendor audit required for high risk; validated as COTS
  - Custom/Bespoke - developer and user validations required

GAMP guidelines agree with FDA approach for software validation. 
