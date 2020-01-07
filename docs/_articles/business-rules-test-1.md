---
layout: article
title: Business rules - Version 1.13
date: 2020-01-02T00:00:00.000Z
type: article
published: 'true'
status: publish
---
# Business rules
Version 1.13

**NOTE:** This documentation is being trialled for use with the **Street Manager private beta for authorised participants given credentials only**, it is not in final state and should not be taken as production documentation.


## Table of contents

1. <a href="#1--general-rules-and-validation">General rules and validation</a><br />
1.1 <a href="#1-numbers">Numbers</a><br />
1.2 <a href="#1-datetime">Dates and times</a><br />
1.3 <a href="#1-charlimits">Text character limits</a><br />


## 1.  General rules and validation

**<span id="1-numbers">1.1. Numbers</span>**

All numbers within Street Manager system are non-negative.

**<span id="1-datetime">1.2. Dates and times</span>**

All dates and times must match the ISO 8601 standard date format.

See GOV.UK guidance for date-times <https://www.gov.uk/government/publications/open-standards-for-government/date-times-and-time-stamps-standard>

**<span id="1-charlimits">1.3. Text character limits</span>**

**1.3.1. Username field**

The max length for username fields is 50 characters.

**1.3.2. Single-line text fields**

Max length is 100 characters.

These include:
* Promoter contact details
* Approved contractor
* Contractor details
* Secondary contact email
* Project reference number
* Early start pre-approval authoriser
* Promoter org
* Promoter contact details
* Approved contractor
* Contractor contact details
* Street name
* Area name
* Project reference number
* Inspection call log field
* Inspection call log reference
* Inspector name
* FPN authorised officer
* FPN officer contact details
* Activity name
* Activity type details
* Contact name
* Contact details
* Street special designation code

1.3.3 Multi-line text areas

Text areas for comments are limited to the max length of 1500 characters.

All other text areas are limited to 500 characters. These include:
* x


