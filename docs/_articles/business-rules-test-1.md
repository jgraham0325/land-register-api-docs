---
layout: article
title: Business rules - Version 1.13
date: 2020-01-02T00:00:00.000Z
type: article
published: 'true'
status: publish
---
# Business rules
<span class="govuk-body-l">Version 1.13</span>

**NOTE:** This documentation is being trialled for use with the **Street Manager private beta for authorised participants given credentials only**, it is not in final state and should not be taken as production documentation.

<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />

## Table of contents

1. <a href="#1--general-rules-and-validation">General rules and validation</a><br />
1.1 <a href="#1-numbers">Numbers</a><br />
1.2 <a href="#1-datetime">Dates and times</a><br />
1.3 [Coordinates](#1-coordinates)<br />
1.3 <a href="#1-charlimits">Text character limits</a><br />
2. <a href="#2-workstreams">Workstreams</a><br />
3. <a href="#3-submissions-and-applications">Submissions and applications</a><br />
3.1 <a href="#3-forwardplans">Forward plans</a><br />
3.2 [PAAs](#3-paa)<br />


<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />

## 1.  General rules and validation

**<span id="1-numbers">1.1. Numbers</span>**

All numbers within Street Manager system are non-negative.

**<span id="1-datetime">1.2. Dates and times</span>**


**1.2.1 Date and time format**

All dates and times must match the ISO 8601 standard date format.

See GOV.UK guidance for date-times <https://www.gov.uk/government/publications/open-standards-for-government/date-times-and-time-stamps-standard>


**1.2.2 Working day**

See the glossary for the definition of a working day: <https://departmentfortransport.github.io/street-manager-docs/articles/glossary.html>

_(Previously section 1.6 in Business rules v0.1 draft)_




**<span id="1-coordinates">1.3. Coordinates</span>**

Coordinates must be a GeoJSON geometry (using British National Grid, easting and northing pairs).


**<span id="1-usrn">1.4. USRN</span>**

USRN must be a value between 100001 and 99999999.

_(Previously section 16.3 in Business rules v0.1 draft)_










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

**1.3.3 Multi-line text areas**

Text areas for large comment fields are limited to the max length of 1500 characters.

All other text areas are limited to 500 characters. These include:
* Description of work
* Works location description
* Collaboration details
* Description of collaborative works* Early start pre approval details
* Early start pre approval reason 
* Additional info (apply for permit) / comments (revoke) / details (lane rental assessment / collaborative working) 
* Revoke reason
* Permit discount reason
* Reinstatement location description
* Inspection outcome details
* Inspection call log summary
* FPN offence details
* FPN status reason
* Activity location description
* Cancellation reason


<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />

## 2. Workstreams

Before users start raising works in Street Manager, their organisation must set up their workstreams. These were previously known as ‘operational districts’.

The Street Manager system will, by default, create the prefix ‘000’ for every organisation. When organisations set up their workstreams, they can choose to allocate numerical prefixes between 1 - 999.
See works reference number (WRN) section for details on how the workstream prefix will be used when raising works.


<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />

## 3. Works submissions and applications

**<span id="3-refnumbers">3.1. Works reference number (WRN)**</span>

xxx

_(Previously section 1.1 in Business rules v0.1 draft)_  



**<span id="3-forwardplans">3.2. Forward plans</span>**

* It is only possible to add forward plans for a start date in the present or future, and with an end date in the future.
* Forward plans can be progressed to PAA, edited or cancelled while in the ‘Raised’ status. 
* All forward plan details can be edited with the exception of certain details, namely the workstream, the highway authority and the USRN.
* When progressed to a PAA, the forward plan's status automatically gets set to 'Progressed'. 

<div class="center polaroid50 container"><img src="https://departmentfortransport.github.io/street-manager-docs/business-rules/images/Street%20Manager%20-%20Forward%20plan%20statuses.jpg" alt="Street Manager Forward plan statuses" width="100%" />
A diagram of forward plan statuses</div>

_(Previously section 22 in Business rules v0.1 draft)_  






**<span id="3-pa">3.4. PAA & Permit applications</span>**

**3.3.1. Permit reference number**

xxx

_(Previously section 1.2 in Business rules v0.1 draft)_  



**3.3.2. Works type**

xxx

_(Previously section 1.3 in Business rules v0.1 draft)_  



**3.3.3. Works category**

xxx

_(Previously section 1.4 in Business rules v0.1 draft)_  



**3.3.4. Permit application statuses**

**PAA statuses**

<Insert diagram>

**Permit statuses**

<Insert diagram>

_(Previously section 1.5 in Business rules v0.1 draft)_  





**3.x.x. Early start**
* x


**<span id="3-workstype">3.3. Works category**</span>

xxx

_(Previously section 1.4 in Business rules v0.1 draft)_  









<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />

## Changes to applications and permits

**<span id="4-pa">4.x. Change request reference number</span>**

x

**<span id="4-pa">4.x. Change request types</span>**

x

**<span id="4-pa">4.x. Editing application pre-assessment</span>**

_(Previously section 26 in Business rules v0.1 draft)_ 


**<span id="4-pa">4.x. Modified application</span>**

<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />

## Revoking a permit



**<span id="3-assesspa">3.x. Permit application assessment</span>**
* x


<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />

## Viewing and managing records

List pages, search and filtering

Expiring interim page is xxx


Map

Map Filtering

Map Search


Works history


Commenting on a works record

Topic



<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />

## Deliver and execute works

Log works start

Rules

Log works stop

Rules

Revert works start / works stop

Inspection units

Validity period

<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />

## Sites and Reinstatements

<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />

## Inspections and non-compliance

**<span id="4-pa">4.x. Inspection reference number</span>**

x



<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />

## Fixed penalty notice (FPN)

**<span id="4-pa">4.x. FPN reference number</span>**

x


<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />

## Fee reporting

<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />


<style>
.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
}
div.polaroid50 {
  width: 50%;
  background-color: white;
  box-shadow: 0 1px 4px 0 rgba(0, 0, 0, 0.2), 0 1px 15px 0 rgba(0, 0, 0, 0.19);
}
div.container {
  text-align: center;
  padding: 0px 20px 10px 20px;
  margin-top: 20px;
  margin-bottom: 20px;
  font-size: 14px;
}
em {
  font-size: 12px;
}
</style>
