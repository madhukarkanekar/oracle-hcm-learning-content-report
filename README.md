# Oracle HCM Learning Course Content Details Report

This repository contains a SQL report developed in Oracle Fusion HCM Learning Cloud to extract course, offering, and content level details.

The report provides information about course structure, content mapping, tracking type, status, author, and external identifiers used in Oracle Learning Cloud.

## Features

- Course Name and Course Number
- Content Title and Content Number
- Content ID and Content Type
- Author and External Identifier
- Content Status
- Tracking Type
- Content Description
- Created By (User Name)
- Course → Offering → Content mapping

## Parameters

The report supports optional parameters:

- CONTENT_NAME
- STATUS

If parameters are not provided, all records will be returned.

## Tables Used

- WLF_LEARNING_ITEMS_F
- WLF_LEARNING_ITEMS_F_TL
- WLF_LI_ACTIVITIES_F
- WLF_LI_CONTENT_F
- WLF_LI_CLASSES_F
- FND_LOOKUP_VALUES
- PER_PERSON_NAMES_F
- PER_ALL_PEOPLE_F

## Use Case

This report is used for:

- Learning content audit
- Course structure validation
- Content tracking verification
- Integration validation
- Reporting and compliance

## Module

Oracle Fusion HCM  
Oracle Learning Cloud (OLC)

## Author

Madhukar
