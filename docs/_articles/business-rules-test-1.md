---
layout: article
title: Business rules - Version 1.13
date: 2020-01-02T00:00:00.000Z
type: article
published: 'true'
status: publish
---
<!-- ==================================================== -->
# Business rules
<!-- ==================================================== -->

<span class="govuk-body-l" style="float:left">Version 1.13</span>

<!--span style="float:right">[Business rules - All versions](https://departmentfortransport.github.io/street-manager-docs/articles/glossary-change-history.html)</span--><br /><br />

<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />


<!-- ==================================================== -->
## Table of contents
<!-- ==================================================== -->

1. [General rules and validation](#1--general-rules-and-validation)<br />
  1.1 [Numbers](#1-numbers)<br />
  1.2 [Dates and times](#1-datetime)<br />
  1.3 [Coordinates](#1-coordinates)<br />
  1.3 [Text character limits](#1-charlimits)<br />
1. [Workstreams](#2-workstreams)<br />
1. [Submissions and applications](#3-submissions-and-applications)<br />
  3.1 [Forward plans](#3-forwardplans)<br />
  3.2 [PAAs](#3-paa)<br />
1. [Changes](#changes)<br />

<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />



<!-- ==================================================== -->
## 1.  General rules and validation
<!-- ==================================================== -->

### 1.1. Numbers

All numbers within Street Manager system are non-negative.

<br />

### <span id="1-datetime">1.2. Dates and times</span>


#### 1.2.1 Date and time format

All dates and times must match the ISO 8601 standard date format.

See GOV.UK guidance for date-times <https://www.gov.uk/government/publications/open-standards-for-government/date-times-and-time-stamps-standard>


#### 1.2.2 Working day

See the [Street Manager glossary](https://departmentfortransport.github.io/street-manager-docs/articles/glossary.html) for the definition of a working day.

_(Previously section 1.6 in Business rules v0.1 draft)_



#### 1.2.2 Calendar day

Street Manager calculates calendar days based on a 24 hour clock. So for example the Street Manager system would consider the time period Monday 01:00 to Tuesday 23:00 as 2 calendar days.

_(Previously section 1.7 in Business rules v0.1 draft)_


<br />



#### 1.2.3 Calendar month

For the purpose of deeming and early start, a calendar month is calculated as 28 calendar days.

_(Previously section 1.13 in Business rules v0.1 draft)_


<br />



### 1.3. Coordinates

Coordinates must be a GeoJSON geometry (using British National Grid, easting and northing pairs).

<br />

### 1.4. USRN

USRN must be a value between 100001 and 99999999.

_(Previously section 16.3 in Business rules v0.1 draft)_








<br />

### 1.3. Text character limits

#### 1.3.1. Username field

The max length for username fields is 50 characters.

#### 1.3.2. Single-line text fields

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

#### 1.3.3 Multi-line text areas

Text areas for large comment fields are limited to the max length of 1500 characters.

All other text areas are limited to 500 characters. These include:
* Description of work
* Works location description
* Collaboration details
* Description of collaborative works* Early start pre approval details
* Early start pre approval reason 
* Additional info (apply for works) / comments (revoke) / details (lane rental assessment / collaborative working) 
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





<!-- ==================================================== -->
## 2. Workstreams
<!-- ==================================================== -->

Before users start raising works in Street Manager, their organisation must set up their workstreams. These were previously known as ‘operational districts’.

The Street Manager system will, by default, create the prefix ‘000’ for every organisation. When organisations set up their workstreams, they can choose to allocate numerical prefixes between 1 - 999.
See works reference number (WRN) section for details on how the workstream prefix will be used when raising works.

_(Previously section 15 & 15.1 in Business rules v0.1 draft)_


<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />



<!-- ==================================================== -->
## 3. Works submissions and applications
<!-- ==================================================== -->

### 3.1. Works reference number (WRN)

* The WRN is generated in the following format: {SWA prefix} {workstream prefix} {promoter works reference}
  * **SWA prefix** consists of two characters for the related organisation from the SWA code list.
  * **Workstream prefix** - See the workstream section for more details.
  * **Promoter works reference** - Between 1 to 19 characters generated by the Street Manager system or provided by the user.
* The WRN including the prefix must be unique in the Street Manager system e.g. the same organisation may have two works records with the same 'promoter works reference' if the works were created under two different workstreams.
* WRNs are not case-sensitive and displayed as uppercase.
* WRNs can only include the following special characters: dashes (-) or underscores (_) to separate characters
* Works records and WRNs are created automatically alongside other records such as forward plans and permit applications.

_(Previously section 1.1 in Business rules v0.1 draft)_  


<br />

### 3.2. Forward plans

* It is only possible to add forward plans for a start date in the present or future, and with an end date in the future.
* Forward plans can be progressed to PAA, edited or cancelled while in the ‘Raised’ status. 
* All forward plan details can be edited with the exception of certain details, namely the workstream, the highway authority and the USRN.
* When progressed to a PAA, the forward plan's status automatically gets set to 'Progressed'. 

<div class="center polaroid50 container"><img src="https://departmentfortransport.github.io/street-manager-docs/business-rules/images/Street%20Manager%20-%20Forward%20plan%20statuses.jpg" alt="Street Manager Forward plan statuses" width="100%" />
A diagram of forward plan statuses</div>

_(Previously section 22 in Business rules v0.1 draft)_  

<br /><br />




### 3.3. PAA & Permit applications (PA)

<br />

#### 3.3.1. Statuses

_(Previously section 1.5 in Business rules v0.1 draft)_ 

##### 3.3.1.1. PAA statuses

< Insert diagram >

##### 3.3.1.2. Permit statuses

< Insert diagram >

<br />


#### 3.3.2. Permit reference number

* The permit reference number is generated in the following format: {WRN} - {numerical suffix}
    * **WRN** - See the works reference number section for more details.
    * **Numerical suffix** - A minimum of two numbers starting from 01 for the first PAA or permit application created on the works record and counts up consecutively for each additional permit application (i.e. -01, -02, -03 etc).
* A permit reference number is automatically generated when a PAA or permit application has been submitted.
* The permit reference number is the reference number that promoters needs to display on on-site permit boards.

_(Previously section 1.2 in Business rules v0.1 draft)_  

<br />


#### 3.3.3. Works types

* Works types are as follows:
    * **Planned** - Minor, Standard, and Major works that are not Immediate
    * **Immediate** - See the [Street Manager glossary](https://departmentfortransport.github.io/street-manager-docs/articles/glossary.html) for more details on immediate works. The immediate works type (i.e. immediate urgent and immediate emergency) will be determined based on the answer to "Is there a risk of damage to people or property?"

_(Previously section 1.3 in Business rules v0.1 draft)_  

<br />


#### 3.3.4. Works categories

* Works categories are as follows:
    * **Minor**
    * **Standard**
    * **Major PAA/PA**

See the [Street Manager glossary](https://departmentfortransport.github.io/street-manager-docs/articles/glossary.html) for definitions and duration for each works category.

< Insert diagram >

_(Previously section 1.4 in Business rules v0.1 draft)_  

<br />


#### 3.3.5. Early start

* If a permit application does not provide sufficient advance notice (based on the proposed start date provided) including when the proposed start date is altered during a change request, the promoter will be required to specify if they have pre-approval for an early start and additional information.
* The early start calculation will be carried out immediately after the proposed start and end dates have been entered during the apply for works process.
* The early start calculation will include the day of the application is made.
* The minimum advance notice by works category are as follows:

| Works category | Minimum advance notice |
|:---------------|:-----------------------|
| Major PAA      | 3 calendar months (84 calendar days in Street Manager)|
| Major PA       | 10 working days        |
| Standard       | 10 working days        |
| Minor          | 3 working days         |
| Immediate      | Not applicable         |

_(Previously section 1.9 in Business rules v0.1 draft)_ 
 
<br />


#### 3.3.6. Assessment period

* The assessment period is the time period that a Highway Authority (HA) has to assess and evaluate a permit application (or any other promoter request) prior to the permit deeming.
* The assessment period will begin from the next working day after application submission.
* The assessment period for each works category are as follows:

| Works category | Assessment period |
|:---------------|:------------------|
| Major PAA      | 28 calendar days  |
| Major PA       | 5 working days    |
| Standard       | 5 working days    |
| Minor          | 2 working days    |
| Immediate      | 2 working days    |

_(Previously section 1.8 & 1.10 in Business rules v0.1 draft)_ 

<br />


#### 3.3.7. Adding permit applications (PA)

* PA's may be added from the Home page resulting in a new works record or added to an existing works record.
* PA's can only be added to an existing works record if the works record does not contain a Minor/Standard/Major PA that is 'in progress' or 'submitted'.
* Major PAA must be the first application on a works record i.e. cannot be added as a second application on an existing works record.
* A major PAA may be progressed to PA if it is in 'submitted' or 'granted' status.

_(Previously section 1.12 in Business rules v0.1 draft)_ 
 
<br />


### 3.3.8. Works activity types

* See the [Street Manager glossary](https://departmentfortransport.github.io/street-manager-docs/articles/glossary.html) for the works activity types.

_(Previously section 1.14 in Business rules v0.1 draft)_


### 3.3.9. PA assessment options

* x



<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />





<!-- ==================================================== -->
## Changes to applications and permits
<!-- ==================================================== -->

### 4.x. Change request reference number

* The change request reference number is generated in the following format: {permit reference number} -CR- {numerical suffix}
    * See the **permit reference number** section for more details.
    * Numerical suffix - A minimum of two numbers starting from 01 for the first change request created on the PA and counts up consecutively for each additional change request (i.e. -01, -02, -03 etc).

### 4.x. Change request types

* The change request types are as follows:

| Change request type | Available for | Criteria | Assessment required? |
|:--------------------|:---------------------|:---------|:------------------------|
| Promoter imposed change (modified application) | Promoter | PA is awaiting assessment | No |
| Promoter change request | Promoter |  PA in status 'Granted', 'In progress' or 'Modification Requested' | Yes |
| Works extension | Promoter | Same criteria as 'Promoter change request' and includes a change to the proposed end date | Yes |
| HA imposed change | HA | PA in status 'Granted' or 'In progress' | No |

* For promoter imposed and HA imposed change types, the changes made will be applied automatically to the PA with the change request record available to see what has changed historically, and these change request types are not chargeable.
* A PA's assessment period is not affected by promoter imposed changes (i.e. changes while the PA is awaiting assessment).
* A works extension change request may include other changes in addition to a change to the proposed end date.
* HA imposed change is currently limited to adding or removing conditions.


_(Previously section 5.1, 5.3, 5.4, 5.8 & 26 in Business rules v0.1 draft)_ 



### 4.x. Change request statuses

< insert diagram >




### 3.x. Change request assessment options

* The assessment options for change requests are as follows:

| Assessment option | Change request type | Assessment option description |
|:------------------|:--------------------|:---|
| Grant | Promoter change request & works extension | Changes will be applied to the PA. |
| Refuse | Promoter change request & works extension | Changes will not be applied to the PA. Original PA will remain unchanged in status and contents i.e. the PA is not refused as a result of a change request assessment. | 
| Grant with duration challenge | Works extension | HA to provide a reasonable period end date and reason for the duration challenge. The new proposed end date, reasonable period end date and any other changes requested will be applied to the PA. |

_(Previously section 5.1, 5.4 & 5.5 in Business rules v0.1 draft)_ 



### 4.x. Adding change requests

* Each PA may have only one change request awaiting assessment. 
* A change request may be added to PA's that are not 'Refused', 'Revoked' or 'Closed'
* The works category may be updated if the works duration is changed.
* Change requests may not be added to a PAA.
* The following cannot be changed on a PA: 
    * Permit reference number or works reference number
    * USRN
    * USRN address e.g. road/street & road category
    * Primary notice authority the PA is submitted to
* Proposed start date may not be changed if works start has been logged.
* All change requests show the original details and changed values.


_(Previously section 5.2, 5.3, 5.4 & 5.6 in Business rules v0.1 draft)_ 


### 4.x. Assessment period

* The assessment period for change requests is 2 working days. The change request will deem after this period and the changes will be applied to the PA.

_(Previously section 5.7 in Business rules v0.1 draft)_ 


<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />




<!-- ==================================================== -->
## Revoking a permit
<!-- ==================================================== -->





<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />



<!-- ==================================================== -->
## View and manage records
<!-- ==================================================== -->

List pages, search and filtering

Expiring interim page is xxx


Map

Map Filtering

Map Search


Works history


Commenting on a works record

Topic



<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />


<!-- ==================================================== -->
## Deliver and execute works
<!-- ==================================================== -->


Log works start

Rules

Log works stop - can you log a stop date that is before a reinstatement date that was added whilst the works was in progress?

Rules

Revert works start / works stop

Inspection units

Validity period

<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />






<!-- ==================================================== -->
## Sites and Reinstatements
<!-- ==================================================== -->


### 4.x. Sites and site numbers

* A new site will be added automatically when 'Add a reinstatement' is selected on the 'works record' level.
* For each works record, the site numbers begin at 1 and counts up consecutively for each additional site (i.e. Site 1, Site 2, Site 3 etc).
* All historical reinstatement details are available for each site on the individual 'site record' pages.


### 4.x. Reinstatement types

* The reinstatement types are as follows:
    * Excavation
    * Bar holes
    * Core holes
    * Pole testing
* Reinstatement measurements and whether the reinstatement is a final reinstatement must be provided for excavation reinstatement type.
* Number of holes must be provided for bar holes, core holes and pole testing reinstatement types.

_(Previously section 4.7 in Business rules v0.1 draft)_






### 4.x. Add a reinstatement

* To add a reinstatement, the latest permit must be in 'In progress or 'Closed' status and require excavation.
* Reinstatement date must be:
    * the current date or in the past
    * on or after the actual start date
    * on or before the actual end date if works stop has been logged
* To update a site with a new reinstatement, select 'Add another reinstatement' on the 'site record' level.
* This functionality may be used to correct a mistake on the previous reinstatement.
  + Note: if a mistake is made where the Reinstatement state 'Interim' is selected instead of 'permanent' as a new permit would be required to rectify this mistake. See the business rules regarding making an interim site permanent for more information.


_(Previously section 4.2, 4.3, 4.5 & 4.6 in Business rules v0.1 draft)_





### 4.x. Making interim site permanent

* If an existing site is in 'interim' state, a new permit must be raised to add a 'permanent' reinstatement to the existing site.

_(Previously section 4.4 in Business rules v0.1 draft)_







### 4.x. Reinstatement end date

* If the reinstatement state is 'interim', the interim period end date is 6 months from the reinstatement date e.g. if an interim reinstatement date is 26/10/18 then the end date should be 25/04/19
* If the reinstatement state is 'permanent' and
    * depth is less than or equal to 1.5m, the end date (guarantee expiry date) is 2 years from the reinstatement date e.g. if reinstatement added 13/06/18, end date is 12/06/20.
    * depth is greater than 1.5m, the end date (guarantee expiry date) is 3 years from the reinstatement date e.g. if reinstatement added 13/06/18, end date is 12/06/21.

_(Previously section 4.1 in Business rules v0.1 draft)_


### 4.x. Register final site

* Final site may be registered by marking 'Are you registering the final site?' as Yes when adding a reinstatement.
* Alternatively, select 'Change' on the works record level against 'Final site registered'.

_(Previously section 4.3 in Business rules v0.1 draft)_


<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />








<!-- ==================================================== -->
## Activities
<!-- ==================================================== -->

### 4.x. Activity reference number

* The activity reference number is generated in the following format: ARN- {SWA number} - {numerical suffix}
    * **SWA number** - The four-digit portion of the organisation's SWA code i.e. the SWA code without the two-character prefix.
    * **Numerical suffix** - A minimum of three numbers starting from 001 for the first activity by the organisation and counts up consecutively for each additional activity (i.e. -001, -002, -003 etc).

<br />



<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />






<!-- ==================================================== -->
## Inspections and non-compliance
<!-- ==================================================== -->

### 4.x. Inspection reference number

* The inspection reference number is generated in the following format: {WRN}-INSP-{numerical suffix}
    * **WRN** - See the works reference number section for more details.
    * **Numerical suffix** - A minimum of two numbers starting from 01 for the first inspection created on the works record and counts up consecutively for each additional inspection (i.e. -01, -02, -03 etc).

_(Previously section 3.1 in Business rules v0.1 draft)_ 

### 4.x. Inspection types and categories

* Inspections may be added by a HA at any stage of a works record.

| Inspection type | Inspection categories |
|:----------------|:----------------------|
| Live Site                | Category A<br />Site occupancy<br />Conditions<br />Third party<br />Routine |
| Reinstatement            | Category B<br />Category C<br />Third party<br />Routine |
| Non-compliance follow up | Joint site visit<br />Follow up<br />Follow up completion |
| Section 81               | Not applicable |

_(Previously section 3.2 & 3.5 in Business rules v0.1 draft)_ 

### 4.x. Inspection outcomes

* If a failed inspection outcome is selected for Live site, reinstatement or non-compliance follow up inspection types, details of non-compliant areas must be provided.
* If a failed inspection outcome is selected for Section 81, the inspection may advise if the site was made safe by HA.
* Additional information and evidence/photos may be provided by HA for all outcomes.
* The inspection outcomes available for inspection types and categories are as below:

| Inspection type | Inspection outcomes |
|:----------------|:--------------------|
| Live Site (excl. Site occupancy & Conditions), Reinstatement and Non-compliance follow up (excl. Joint site visit) | Passed<br />Failed — high<br />Failed — low<br />Unable to complete inspection |
| Live Site type with Site occupancy category | Works stopped - Apparatus remaining<br />Works in progress - No carriageway incursion<br />Works in progress<br />Works stopped<br />Unable to complete inspection |
| Live Site type with Conditions category | Passed<br />Non compliant (with conditions)<br />Unable to complete inspection |
| Non-compliance follow up with Joint site visit category | Further inspections required<br />Agreed site compliance<br />Unable to complete inspection |

_(Previously section 3.3 & 3.5 in Business rules v0.1 draft)_ 



<!-- SECTION NOT REQUIRED
### x. Inspection failure categories
_(Previously section 3.4 in Business rules v0.1 draft)_ -->


### 4.x. Inspection scheduling

* HA may schedule one inspection against a works record.
* A scheduled inspection consists of a date, time (optional) and inspection type & category.
* The date provided must be today or in the future. If time is provided, it must occur in the future.
* A scheduled inspection may be cancelled from the works record.
* A scheduled inspection that has not been cancelled will be automatically removed when any inspection is submitted.
* A scheduled inspection will remain on the works record until it is cancelled or an inspection is added regardless of the date and time the inspection was scheduled for.
* A new scheduled inspection may be created as part of any add an inspection process. Alternatively, A new scheduled inspection may be created directly on the works record level.

_(Previously section 3.6 in Business rules v0.1 draft)_ 





<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />





<!-- ==================================================== -->
## Fixed penalty notice (FPN)
<!-- ==================================================== -->

### 4.x. FPN reference number

* The FPN reference number is generated in the following format: {WRN}-FPN-{numerical suffix}
    * **WRN** - See the works reference number section for more details.
    * **Numerical suffix** - A minimum of two numbers starting from 01 for the first FPN created on the works record and counts up consecutively for each additional FPN (i.e. -01, -02, -03 etc).

_(Previously section 2.2 in Business rules v0.1 draft)_ 

### 3.3. FPN statuses

* The FPN statuses are as follows:
    * **Issued** - The initial status of an FPN issued by a HA. (Applicable for all FPNs)
    * **Accepted** - Promoter may change to this FPN status when to acknowledge receipt of FPN. (Optional status change)
    * **Disputed** - Promoter may change to this FPN status when in discussion with the HA about the validity of an FPN. (Optional status change)
    * **Withdrawn** - HA may change to this FPN status if HA agree to withdraw FPN. (if applicable)
    * **Paid** - HA acknowledge that the promoter payment (no discount) has been received. (if applicable)
    * **Paid (Discounted)** - HA acknowledge that the promoter payment (with discount) has been received. (if applicable)

< insert diagram >

_(Previously section 2.1 in Business rules v0.1 draft)_ 

<br />











<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />






<!-- ==================================================== -->
## Fee reporting
<!-- ==================================================== -->

<hr class="govuk-section-break govuk-section-break--xl govuk-section-break--visible" />








<!-- ==================================================== -->
## Changes
<!-- ==================================================== -->

| Section | Change comment |
|:--------|:---------------|
| 1.      | Added |
| 1.1.    | Updated |
| 1.2.    | Updated |













<!-- ==================================================== -->
<!-- ==========DO NOT DELETE ANYTHING BELOW THIS========= -->
<!-- ==================================================== -->



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
