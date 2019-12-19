---
layout: article
title: Business rules - test
date: 2019-12-17T16:25:26.694Z
type: article
published: 'true'
status: publish
---
1 – General rules and validation 
 
All numbers within Street Manager system are non-negative.

All dates must match the ISO date format.



1.1 Usernames text field validation
The max length for usernames is 50 characters.

1.2 Free text fields limited to 100 characters. These include:
●	Promoter contact details
●	Approved contractor
●	Contractor details
●	Secondary contact email
●	Project reference number
●	Early start pre-approval authoriser
●	Promoter org
●	Promoter contact details
●	Approved contractor
●	Contractor contact details
●	Street name
●	Area name
●	Project reference number
●	Inspection call log field
●	Inspection call log reference
●	Inspector name
●	FPN authorised officer
●	FPN officer contact details
●	Activity name
●	Activity type details
●	Contact name
●	Contact details
●	Street special designation code




1.3 Free text fields with max length 255 characters
●	Special designation location text

1.4 Free text fields with max length 300 characters 
●	Special designation description

1.5 Start and end time validation
Whole numbers between 0 and 2400 inclusive

1.6 Free text fields with max 500 characters. These include:
●	Description of work
●	Works location description
●	Collaboration details
●	Description of collaborative works
●	Early start pre approval details
●	Early start pre approval reason 
●	Additional info (apply for permit) / comments (revoke) / details (lane rental assessment / collaborative working) 
●	Revoke reason
●	Permit discount reason
●	Reinstatement location description
●	Inspection outcome details
●	Inspection call log summary
●	FPN offence details
●	FPN status reason
●	Activity location description
●	Cancellation reason


1.7 Free text comment fields 
●	1500 characters


2 – Set up & logging in process

2.1 Setting up an account
To set up an account, users need to:

●	work for a local highway authority in England, or a utility company or a contractor employed by those organisations
●	know who the ‘primary contact’ is in their organisation – the person with authority to sign up individuals and organisations to the service

If the organisation is already registered on Street Manager, the org’s primary contact will be able to create accounts for other users. If the organisation is a utility company, they will need a Street Works Act (SWA) code which confirms they have a legal right to carry out works in the highway. To find or create an organisation’s SWA code, visit GeoPlace. Note, SWA codes should be a maximum length of 4 characters.


2.2 Logging in

Once users have their log in details, they can log in through the Street Manager log-in page at: https://www.manage-roadworks.service.gov.uk/

Note, by logging in users agree to the Street Manager terms of use. 

2.3 - User registration process and outcomes (previously section 24)
2.3.1 - Adding a new user (previously section 24.1)
Only admin users can add new users to their organisation
Need to enter the exact match email address for the account they wish to add/remove. System will validate if the user has already been added and inform the user if so
Admin users logged in under a promoter organisation are only able to add promoter users. HA admin users are able to add both HA and promoter users
2.3.2 - Removing a user (previously section 24.2)
Only admin users can remove a user from their organisation
Need to enter the exact match email address for the account they wish to add/remove. System will validate if the user exists and inform them if they don't
Removed users will still be displayed in historical audits of actions they carried out in the system
2.3.3 - Editing a user (previously section 24.3)
Currently no functionality to edit a user. Admin user should remove and re-add any users that need to have their details edited


2.4 Configuring Street Manager

2.4.1 Setting up workstreams

Before users start raising works in Street Manager, they should set up their workstreams. These were previously known as ‘operational districts’. The Street Manager system will, by default, create the prefix ‘000’ for every organisation. When users set up their workstreams, which it’s advised that they do before raising works, they can choose to allocate numerical prefixes between 1 - 999.

Note, the organisation code is automatically included in the workstream prefix when raising works.


2.4.2 View workstream

Users can view workstreams by  XXX

2.4.3 Updating workstreams
XXX

2.5 - User registration process and outcomes (previously section 24)
2.5.1 - Adding a new user (previously section 24.1)
Only admin users can add new users to their organisation
Need to enter the exact match email address for the account they wish to add/remove. System will validate if the user has already been added and inform the user if so
Admin users logged in under a promoter organisation are only able to add promoter users. HA admin users are able to add both HA and promoter users
2.5.2 - Removing a user (previously section 24.2)
Only admin users can remove a user from their organisation
Need to enter the exact match email address for the account they wish to add/remove. System will validate if the user exists and inform them if they don't
Removed users will still be displayed in historical audits of actions they carried out in the system
2.5.3 - Editing a user (previously section 24.3)
Currently no functionality to edit a user. Admin user should remove and re-add any users that need to have their details edited


2.6 - Contractors process and outcomes (previously section 20)
2.6.1 - Adding a contractor (previously 20.1)
Only admin users can add a contractor organisation and only to their own organisation (determined by the SWA code against that admin users).
2.6.2 - Removing a contractor (previously 20.2)
Only admin users can remove a contractor organisation. Removing them will remove any permissions they have to work on behalf of that organisation
2.6.3 - Switching between organisations (previously 20.3)
Currently, contractor can only work on behalf of one organisation at a time. When they log in, they are required to choose which organisation they wish to work on behalf of. They have the option of switching between organisations at any point. Also, contractors can only choose organisations that have added them to their list of contractors (see 20.1)




3 – Homepage process 

3.1 Navigating from the homepage

The Street Manager homepage features tiles that allow the user to navigate to the task they want to accomplish or view lists under those topics. 



3.2 Returning to the homepage

Users can navigate back to the homepage by clicking on the ‘Plan and manager roadworks’ banner that appears at the top of every page within Street Manager.








4 – Submissions and applications

4.1 Forward plans process and outcomes (previously section 22)

4.1.1 - Submitting a forward plan (previously section 22.1)
Forward plans allow a Planner to supply information about works that are part of their longterm programme (whether their annual operating programme, or their 3 or 5 year rolling programme). Giving advance notice with a forward plan helps with collaboration of works and management of the road network.

It is only possible to add forward plans for a start date in the present or future, and with an end date in the future.

Forward plans can be edited or cancelled at any point up until they are closed, with the exception of certain details, namely the workstream, the highway authority and the USRN.
4.1.2 - Progressing a forward plan into a PAA (previously section 22.2)
Forward plans are only for major works and can only be progressed to a PAA when they have a status of 'Raised'.

When progressed to a PAA, the forward plan's status automatically gets set to 'Closed' so that there is only one active plan, PAA or permit against a works record at any given time.


4.2 PAAs

4.3 Permits 

Users can apply for a permit by clicking the ‘apply for works’ link on the homepage. This will prompt the user to define the proposed location of works by looking up the area they wish to work in. To pinpoint the exact location, users have the option of searching by the NSG database, by coordinates, by USRN, or by the Ordnance Survey database. 

Note, coordinates must be a GeoJSON geometry (using British National Grid, easting and northing pairs).

What’s more, if searching by USRN, the USRN must be a value between 100001 and 99999999 (previously 16.3)


4.3.1 Selecting location on map
Once a user has search for a street or area, they can select the correct location. The user will then be provided with a range of map filters which allow them to view planned works, events and other licensed activities, as well as forward plans within a certain date range that interests them. 
This will return a list of results from which the user can select the relevant works location. 

4.3.1.1- Map date filter (previously 16.1)
The map date filter will default to the current date in the 'From' field and 14 days after the current date in the 'To' field.

4.3.1.2 - Displaying works on map (previously 16.2)
Street Manager displays up to 500 works / events and other licensed activities / forward plans on the map. 

Results will not be displayed on the map when user clicks out three zoom levels higher than the default view after the point of clicking on the address from the search results.

4.3.1.3 Applying for works with selected USRN

Once the user has pinpointed the location of their works, they will be prompted to drop a pin on a map. Doing this will bring up USRN within a XX radius of the pinned location. Users can view designations, or continue applying for works with selected USRN.  


4.3.2 Setting up workstreams (previously ‘workstreams prefix’ 15.1)

When raising a permit, each works will need to be allocated to a workstream. This was previously known as an ‘operational district’. 

The Street Manager system creates by default the prefix ‘000’ for every organisation. It is strongly advised that before users start raising works in Street Manager, they first set up their workstreams and allocate to them numerical prefixes between 1 - 999.

Note, the organisation code is automatically included in the workstream prefix when raising works




 4.4 Permit fields process and outcomes (previously section 1)
4.4.1 - Works reference number (WRN) (previously 1.1)
When applying for a permit, a Promoter has the option to use their own works reference number (WRN) or use an automatically-generated one by the Street Manager system. 
Note, a WRN can only be 19 characters or under, using only alphanumeric characters. 
If the user opts for generating a WRN automatically, they will receive an 8-digit number that is made up of their organisation’s SWA code, and its allocated workstream prefix in Street Manager. The 8 digits in the WRN need to be unique as this is the distinguishing part, but these 8 digits can be the same for two permits if the works are allocated to another workstream (meaning the prefix will be different for each).
The WRN is generated in the following format and made up of these parts: {SWA_prefix} {workstream_prefix} - {Promoter works reference} - {StreetManager numerical record suffix}
The SWA prefix is from the SWA code list. The workstream prefix and promoter works reference are stored separately against the works record. While the numerical record suffix (-01, -02, -03 etc) counts up from 01 to reflect the number of permits that have already been raised.
When the user selects the option to automatically create the WRN, it is created and stored against the works record when the first permit application is submitted.
Manual WRNs are not case sensitive, but will be subsequently displayed as uppercase. System-generated WRNs are created in uppercase. Dashes (-) and underscores (_) are the only special characters allowed in manually entered WRNs.



4.4.2 - Permit reference number (previously 1.2)
The permit reference number is a unique reference number within the system that is less than or equal to 30 characters. This is automatically generated by Street Manager at the end of the ‘apply for a permit journey’ as part of the submission confirmation. This is also the number that the promoter needs to display on their on-site permit board. 
Format: the permit reference is made up of the works reference number, with a numerical suffix (-01, -02, -03 etc) which counts up from 1 to reflect the number of permits that have been raised.


4.4.3 - Works type (previously 1.3)
-	Planned 
(Minor, Standard, and Major works that are not Immediate) Selecting this triggers progressive disclosure within the user interface of the question "Is a temporary traffic regulation order (TTRO) required?"and saves the works category as planned which triggers the planned permit application flow. Standard, Minor, Major (PAA) applications are able to be created from this flow. 
- Immediate 
(Unscheduled works of a critical nature that need to be undertaken without delay) Selecting this triggers progressive disclosure within the user interface of the question "Is there a risk of damage to people or property?" and saves the works category as Immediate – which triggers the Immediate permit application flow

Note: Permit type defaulted to 'Planned' - if TTRO required and user is progressing an existing PAA to a major permit application.



4.4.4 Works category (previously 1.4)

This is automatically calculated based on information provided by the user (namely, duration and whether a TTRO is required).

Options of work category depend on what flow / journey the user is in. 
If in the Immediate flow, the works category options are:
●	Immediate (Urgent) or 
●	Immediate (Emergency)

If Planned flow the works category options are: 
●	Minor 
●	Standard 
●	Major PA/PAA

Here is how the specific category options are calculated.
Works are determined as 
●	Major if the duration is less than 10 working days duration and / or a TTRO (Temporary Traffic Regulation Order) is required
●	Standard, if the duration is 4-10 working days (inclusive)
●	Minor, if the duration is 1 to 3 working days (inclusive)





4.4.5 (previously 1.5)

Current Statuses: 

*Permit Status*

Permit application submitted
Granted: Proposed
Refused
Granted: In progress
Closed
Cancelled
Revoked: Proposed
Revoked: In progress
Revoked: Closed
Deemed: Proposed
Deemed: In progress
Awaiting assessment: In progress


*Permit Alteration Status*
Submitted
Granted
Refused
Deemed
Revoked

4.4.6 (previously 1.6)

Working day


Street Manager calculates working days based on bank holidays, public holidays, and weekends – not times. For example, the period from 00:00 - 16:30 is considered a working day. Any time before 16:30 is recorded as _that_ working day. Any time after 16:30 is considered the next working day.

****Note - currently the working day duration factors in bank holidays. However, as the Street Manager system receives bank holiday data from gov.uk up to the end of the following year, any works that extend beyond that won't be factoring in bank holidays****



4.4.7 Calendar day (previously 1.7)

Street Manager calculates calendar days based on a 24 hour clock. So for example the Street Manager system would consider the time period Monday 01:00 to Tuesday 23:00 as 2 calendar days.


4.4.8 Deadline date (previously 1.8)

The deadline date is the end of the response period, and forms part of the logic linked to deeming. For all application types, the clock starts counting down from the next working day after submission. Anything submitted after 16:30 is effectively the same as submitting them the next working day

The response periods for all types of applications before they deem are as follows:


- PAA - 28 calendar days 

- Major - 5 working days 

- Standard - 5 working days 

- Minor - 2 working days

- Immediate - 2 working days



4.4.9 Early start (previously 1.9)

Each works category has a minimum notice period ahead of the proposed start date. These are as follows (includes the working day the application is made):

- PAA - 3 months (12 calendar weeks/84 calendar days)
- Major - 10 working days
- Standard - 10 working days
- Minor - 3 working days

If the proposed start date is less than the notice period date, the promoter will be required to specify if they have pre-approval for an early start.

If they do have pre-approval, the promoter is required to share the name of the person who agreed to the early start, together with any additional details. 
If they do not have pre-approval, the promoter is required to include justification for an early start request.


4.4.10  Permit application deeming (previously 1.10)

The deadline / response date are the same. This is the date by which the HA needs to respond to the submission of the permit application in order to avoid the permit deeming. 

The response periods for permit applications before deeming are as follows:

- PAA - 28 calendar days (clock starts ticking on following working day to submission as per other deeming logic for all other permits)

- Major - 5 working days 

- Standard - 5 working days 

- Minor - 2 working days

- Immediate - 2 working days 


Example scenario:
If a PAA is submitted on Tuesday at 14:00 it will deem in 28 calendar days, with the count starting from the next day (Wednesday). This makes Wednesday day 1. The calculation to work out the deadline date is Wednesday + 27 calendar days.

If this PAA was to be submitted after 16:30 on the same Tuesday, this effectively acts as though the PAA was submitted the next day, which means the response period is actually two days away, so same scenario different time:

1. Permit submitted Tuesday 16:31
2. Response period (we start counting from) Thursday
3. Thursday is day 1 + 27 calendar days





4.4.11 USRN (previously 1.11)
Will be defaulted from NSG data based off location specified for permit.

(note that this is not a biz rule – change doc name to include spec)



4.4.12 (previously 1.12)

Multiple permits per work record

Users can add multiple permits to a works record. However, it’s only possible to have one "live" permit at any time (i.e. with a ‘submitted’ or ‘in-progress’ status). Users can only add another permit once the existing permit is no longer "live" i.e. it has been cancelled, revoked, refused or completed.

When adding a further permit to a works record, certain things cannot be changed. These include the works location (including coordinates and USRN) and the works reference number. For this reason, when adding a new permit to a works record, the map section of the permit journey is skipped and the user is first taken to the works location details page. Currently, if you need to submit a permit for a new set of coordinates or different USRN, you have to raise a new works.




4.4.13 Business month (previously 1.13)
For the purpose of deeming (see ‘permit application deeming’), a business month is 28 calendar days.



4.5 - Permit status process and outcomes (previously section 10)
4.5.1 - Permit Status (previously 10.1)
When a permit with the status ‘submitted’ or ‘awaiting_assessment_in_progress’ is granted or refused by the HA, the status then changes to ‘granted_proposed’ or ‘refused’.
If a promoter cancels a permit with the status ‘submitted’, ‘granted_proposed’ or ‘deemed_proposed’ the status changes to ‘cancelled’.
If an HA revokes a proposed permit (i.e. before being granted) with the status of granted_proposed or deemed_proposed, then the status will change to revoked_proposed.
If an HA revokes a permit that is in progress (i.e. after being assessed and granted) with the status granted_in_progress or deemed_in_progress and the assessment status must be granted_proposed, granted_with_changes, deemed_proposed or granted_auto, then the status changes to revoked_in_progress.
4.6. Cancelling process and outcomes (previously 7)

4.6.1 Cancelling a permit before assessment (previously 7.1)

This defines the ability for a promoter to cancel a permit application within their organisation for which the works have not been started yet – but after submission of the permit.

It is possible to cancel a permit after submission (before assessment), and after assessment. 

If the user wishes to go ahead with the cancellation in both scenarios listed above, this will trigger a confirmation request and a reason for cancellation – if they wish to go ahead with it. This functionality is to allow the promoter to remove any works that are no longer required – even if the permit has already been granted. Note, the works will be cancelled, not permanently deleted.

It is not possible for a user (promoter) to cancel any work that is not from their own promoter organisation. 

HAs are unable to cancel a works (unless they log in as a promoter to cancel works they had raised).  

Cancellation will trigger updating the works record status to ‘cancelled’ – if the last live permit on the works record is set to cancelled.


4.7 Lane rental process and outcomes (previously 18)
4.7.1 - Adding a lane rental assessment to a permit (previously 18.1)
HA able to add a Lane Rental Assessment or Charge on the Application Details from a link on the 'Review permit application details' page where they can fill out the one page lane rental form and submit.

Drop down charge band options:- Select a charge band- Charge band 1- Charge band 2- Charge band 3- Charge band 4- Charge band 5

User is only able to enter whole numbers in chargeable days field.

Optional selection with hint text:
- Chargeable: Works will incur a lane rental charge. Add or amend details at any time. Lane rental assessment chargeable days must be a whole number between 1 and 10,000
- Potentially chargeable: Flag or follow up for inspection
- Charges waived: (e.g. Due to collaborative works)
- Exempt: Works fall outside the lane rental scheme
- Charges not applicable to works

The lane rental form provides the HA the following ability:
- Ability to capture free text for additional comments
- Ability to add a lane rental charge (optional)
- Ability to identify if the permit is chargeable
- Ability to apply charge band/tier
- Ability to apply number of chargeable days
- Ability to highlight if charge has been agreed (Defaulted to ‘No’ in Street Manager)

The banner for “Lane rental details added” is shown to the user (upon completing an assessment) on permit applications details page.

Lane rental assessment submission recorded in history of works record.

HA able to add lane rental information at any status (they are not restricted in SM, pre or post grant)
4.7.2 - Lane rental applicable roads flagged to user when drawing permit on map (previously 18.2)
When the user draws their permit on the map, they will be alerted through a text flag which is visible when a Lane Rental USRN is selected based on the ASDs that apply.

Text reads “Lane rental applies”.

The flag is visible when a Lane Rental USRN is selected based on ASD.

User has the ability to reveal additional Lane Rental details from the ASDs.

A link is provided so users can explore help and guidance on lane rental schemes.

The flag (text) permit works is on lane rental applicable road on Check your answers page ‘Apply for works - Review permit application details’ page in the permit journey.

Text reads “Lane rental charges may apply for these works”.

4.8 - Activities process and outcomes (previously 23)
4.8.1 - Adding an activity (previously 23.1)
Only an HA can add an activity
4.8.2 - Cancel an activity (previously 23.2)
Only the HA that added the activity can cancel it.
When cancelled, the activity will be flagged as cancelled and will continue to be displayed in the map
4.8.3 - Edit an activity (previously 23.3)
Only the HA that added the activity can edit it.
Unable to edit the activity location or works area.








5 - Changes to applications and permits (change in title)
5.1 - Change requests
Change request types:
- Promoter change request: raised by the promoter and requires HA to assess - grant and refuse
- Work extension: raised by the promoter and requires HA to assess - grant, grant with duration challenge and refuse
- Imposed change: raised by the HA and is automatically applied to the permit
- Modified application: allows promoter to edit their permit before it's been assessed. See section 5.2
- Modified permit: allows the HA to make a modification on a permit, post-assessment, and needs to be actioned by the promoter

5.2 - Editing permit pre-assessment (previously section 26)
5.2.1 - Modified application (previously 26.1)
A promoter can change the details of the permit before it's been assessed by the HA. This involves using the change request functionality (see rest of section 5) but it doesn't require the HA to assess. The changes made will be automatically applied as long as the permit is awaiting assessment. The exception is when the change concerns USRN-related data i.e. street name, area name (if provided), highway authority, road category, or the works reference number. If promoter wishes to change any of these fields they must cancel and resubmit the permit.

Once made, the changes will show in the change request table and the change request status will be "Applied" and type of "modified application".

Promoters are not charged for making these changes. Changes made and applied do not affect the deem period.

5.2 - Raising a change request
Only one change request can be raised and be live per permit at any one time.
To raise, click into the change request that you wish to alter and click the option. Will be required to provide a reason for the change.
5.3 - Raising a promoter change request
Promoter can submit a change request on a raised permit after it has been granted, and before the work has stopped.
However, the promoter is not able to submit a change request for any USRN-related data i.e. street name, area name (if provided), highway authority, road category, or the works reference number.

If the change request is raised after work has started, it will not be possible to change the actual start date and time.
5.4 - Raising a work extension
HA able to grant with a duration challenge. In this instance, HA must provide a reasonable period end date and reason for the challenge.
Can result in the works category being updated if it goes over the relevant threshold
5.5 - Assessing a promoter change request
- If a change request is granted, the permit will update with the new values.
- If a change request is refused, the permit will remain unchanged. Important note - it's only the change request itself that gets refused, not the permit as a whole.
- If a work extension is granted with duration challenge, the 'Reasonable period end date' field will update accordingly with the new date entered by the HA.
5.6 - Viewing change requests
Details of the change requests are displayed on the permit details page.
Clicking into a change request will highlight what has changed - both what the original values were and the new values.
5.7 - Deeming
Promoter change request deems after 2 working days
5.8 - Imposing a change
This functionality is only available to the Highway Authority and can only be used to impose adding or removing conditions.

5.9 Changes & permit status (previously section 9)

5.9.1 Authorisation (previously section 9.1)
The status of a permit changes when an action is taken by the Highway Authority, which then triggers a change in status.


5.10 - Modified application and modified permit process and outcomes (previously 25)
5.10.1 - Assessing a permit as a modified application (previously 25.1)
Option available to HA to assess a permit as a modified application (previously a PMR) when a Modification Request has been submitted. If selected, HA required to specify the details of what they want to be modified.
5.10.2 - Submitting a modified application (previously 25.2)
Promoter can submit a modified application using the regular change request functionality by adding a change request with the modifications requested.

Note - promoter won't be charged for submitting a change request that is a result of a modified application.
5.10.3 - Assessing a change request as a result of a modified application (previously 25.3)
If the HA is happy with that the change request contains all the modifications that were requested, they can grant the change request. Note - currently this won't automatically grant the permit. HA still needs to grant the permit separately

If HA is not happy the change request contains all the modifications that were requested, they can refuse the change request, adding a note to explain. The permit will remain with a modification request assessment status until the HA actually grants or refuses it so the promoter has the option to add subsequent change request until the HA is happy with changes submitted. Alternatively, they can refuse the change request and then subsequently refuse the permit.

HA is able to change the assessment decision to grant or refuse at any point up until a change request has been submitted by the promoter.

Note - existing change request deeming functionality applies where it will deem after 2 working days. This will be further extended at a later date to take into account what remains of the response period for the permit
5.10.4 - Viewing permits with 'Modification requested' status (previously 25.4)
New 'Modification requested' status added to the permit application status filter on the Applications and works page





6 Revoking a permit process and outcomes

6.1 Revoking a permit

Only the HA can revoke a permit, which can be revoked at any point from when it was granted up to the point the works stopped. If the permit was revoked before the works started, the promoter won’t be able to perform any works record-level actions i.e. log works start. Similarly, the promoter won’t be able to perform any permit actions i.e. add a change request.

If the work has been started, all works record-level actions will continue to be available i.e. reinstatements, inspections and so on. The same goes for the permit actions i.e. change requests, work extensions etc.

At the point of revoking, any outstanding change requests will also be revoked. 

It is possible, however, for the promoter to submit a new permit on a works record when the existing permit has been revoked.




7 – Search process and outcomes (previously 17)
7.1 - Searching using search bar on list pages (previously 17.1)
Search bar added to PA, CR, WR and PAA tabs.

Search rules:
- Complete and partial search.
- Search retains all currently applied filters and vice-versa.
- Search term remains when changing between tabs after the user has searched for something i.e. if a user types in a search term (and doesn’t click submit) and then clicks a different tab, the text will disappear.
- If, however, the user types in a search term (and clicks submit) and then clicks a different tab, the search term will still be in the box.
- Allows user to search for street name and works reference number across each tab but if the user enters the area, town or post code no results will be shown as the database only searches for the partial or complete street name.
- For PA, WR and PAA tabs, if you search by works reference number or street name, the export CSV link will export results with that search term (as well as any filters applied) but will not export any sorting on the columns.
7.2 - Advanced filtering on list pages (previously 17.2)
Advanced filtering options available for lists on the following tabs:
- PAA
- Works records
- Permit applications
- Change requests

Once selected, the filter is applied to the list and results will be displayed.

Filters selection is not persisted when user changes tabs. Note that each tab (with the exception of the change requests) offers the user a link to export the list. The list exported will retain the advanced search results but any sorting will not be exported.

Note that working within traffic sensitive times checkbox on change request tab will not return any results yet due a dependency on known issue being fixed around ASD change requests.

Logic behind the advanced filters:

Working within traffic sensitive times
- A traffic sensitive ASD has been selected
High impact traffic management
- Traffic Management Type is one of:
* Road closure
* Contraflow
* Lane closure
* Convoy working
* Multi-way signals
* Two-way signals

Not submitted final registration
- Promoter has not logged final reinstatement on "Add a reinstatement" page

Works with excavation
- "Has an excavation been carried out?" is set to Yes

Early start
- Permit proposed timings have indicated that the permit is due for an early start

Deemed
- Permit/Change Request was automatically deemed by street manager

Duration extension (Change Request only)
- Permit alteration is a duration extension

Lane rental charges (potentially) apply
- Work takes place on a lane rental applicable road, and a lane rental assessment has been added with an outcome of "Chargeable" or "Potentially chargeable"

Lane rental charges not agreed
- a lane rental assessment has been added with an outcome of "Chargeable" and charges have not been agreed



8 – Deliver / Execute (on site, starting stopping)

8.1. On site process and outcomes (previously 11)

8.1.1 Actual work start (previously 11.1)
Only a Promoter associated with the work can log the actual work start date and time after a permit has been granted.

8.1.2 Actual work stop (previously 11.2)
Only a Promoter associated with the work can log the actual work stop date and time after a permit is in progress.

 8.1.3 - Revert process and outcomes (previously 21)
8.1.3.1 - Reverting the start date and time (previously 21.1)
It is not possible to revert the start date of a works if the following apply:
• The stop date and time has been entered
• A reinstatement has been added
• 'Yes' selected for the 'Final site registered?' question
• It's an immediate works
• The permit has been revoked

If logging the actual start date and time causes the proposed end date to slide (due to the validity period) and then the start date is reverted, the proposed end date will also revert to what it was originally.

The user is required to provide a reason for reverting.
8.1.3.2 - Reverting the stop date and time (previously 21.2)
It is not possible to revert the start date if the following applies:
• Another permit has been added against that works record

The user is required to provide a reason for reverting.



8.1.4 Excavation carried out (previously 11.3)
Only a Promoter associated with the work can update the excavation required field when a permit is in progress. It can be changed until the point that a reinstatement is recorded. Can only record a reinstatement when excavation carried out is true. Is defaulted from permit application.

8.1.5 - Inspection units (previously 11.4)
The user can only add inspection units if an excavation was carried out.

Only a Promoter associated with the work can update the inspection units if the permit is in progress or closed.

At least 1 reinstatement needs to be recorded before inspection units can be added. Field defaulted with 1 once at least 1 reinstatement added.

Inspection units must be a whole number between 1 and 999 inclusive


8.2. Validity period process and outcomes (previously section 13)

8.2.1 Validity period (previously section 13.1)

Validity periods for each works category are as follows. Note, these are all working days and are inclusive of the original start date:
- PAAs - out of scope currently
- Major - 5 working days
- Standard - 5 working days
- Minor - 2 working days

For every permit that is for a non-traffic sensitive category 3 or 4 road, if an actual start date is logged that is later than the proposed start date, the system will check the validity period for that permit. This check is based on the works category. If the actual start date is less than or equal to the latest date available via the validity period, then the proposed end date will shift accordingly, in line with the original duration of the works.

Non-traffic sensitivity is determined by the following scenarios:
- There are traffic sensitive designations for that permit but they’re not selected when submitting the permit
- The permit doesn’t have any traffic sensitive designations

If the permit application is for a traffic sensitive and/or category 0, 1, or 2 road, then the proposed end date will not shift.


8.3. Works history process and outcomes (previously section 12)

8.3.1 All users can view the entire history of a works. Everytime an action is taken on an application or a permit from either the HA or the promoter side, this is reflected in the works history which functions as an audit trail (previously section 12.1)


8.4 Commenting process and outcomes (previously section 8)

8.4.1 Commenting on a work (previously 8.1)

Only users that are associated with a works can comment. Users associated with a works include being from the workstream and authorised organisation / contractor tied to a particular works record.

8.4.2  Topic (previously 8.2)

Only Highway Authorities can comment with the topic ‘overrun warning’.


8.5 Fees report process and outcomes (previously section 14)

8.5.1 Fees report (previously 14.1)

A fees report can be generated by either the HA or a promoter. In order to do so, the user specifies the dates to report on using the ‘To and From’ date selectors to specify the date range for which they want to generate a report. Currently, the system only allows for reports with a maximum of 31 days. This is done for performance reasons, due to the number of entries that could potentially be returned.

Dates queried are the date of the chargeable activity.

The fees report includes an entry for every individual chargeable activity only for completed, cancelled and revoked works. 

Chargeable activities reported on are:
- Granting of a permit application
- PAA progressed to PA - note, this occurs upon receipt of a permit application, not when it’s granted
- Granting of a change request
- Change in work category

Sorted by date in ascending order.




9 – Reinstatements process and outcomes (previously section 4)

9.1 Reinstatement end date (previously section 4.1)

'Auto-calculated based on both reinstatement status and depth.

'If 'reinstatement status ID' = interim, calculated as 6 months from the reinstatement date entered e.g. if reinstatement date is 26/10/18 then end date should be 25/04/19

if 'reinstatement status ID' = permanent, calculated based off depth entered:
- If  'Depth'  <= 1.5 then should be 2 years from reinstatement date. E.g. if reinstatement added 13/06/18, end date is 12/06/20
- If 'Depth' > 1.5 then should be 3 years from reinstatement date. E.g. if reinstatement added 13/06/18, end date is 12/06/21

9.2 Restriction to adding a reinstatement (previously section 4.2)

The promoter is only able to add a reinstatement if they have indicated an excavation is required. The answer to this question defaults with what was entered at the time of the permit application but it can be changed.

The status of the permit must also either be in progress or closed.
●	Reinstatement depth measurement validation:
Depth: 0.01 - 99.99
Length: 0.01 - 9999.99
Width: 0.01 - 99.99
all must be to 2 decimal places



9.3 Adding sites and reinstatements to sites (previously section 4.3)

'To add a new site, select 'Add a reinstatement' at the work record level

To add a reinstatement to an existing site, click into that site from the work record and click 'Add another reinstatement'


9.4 Making interim site permanent (previously 4.4)

In order to make an interim site permanent user needs to add a new permanent reinstatement to an existing site. However, user cannot add a permanent reinstatement to an existing site if the site was made interim in the lifetime of the current permit (i.e. you can't go interim -> permanent on the same permit)

User required to submit a new permit if they wish to make an interim site permanent.

9.5 Reinstatement date (previously 4.5)

Reinstatement date must occur in the past
Only able to enter reinstatement date after the 'Actual start date' has been entered
Reinstatement date must be after the ‘actual start date’
The reinstatement date must be before the ‘actual end date’, if the ‘actual end date’ has been entered. 
The date for ‘reinspection date time’ must match the date for ‘reinspection date’
User cannot enter a date in the future
Time must occur today or a date in the future

9.6 Updating a reinstatement (previously 4.6)
'To update/correct a reinstatement, add another reinstatement to that site. This will then be considered the active reinstatement for that site. Note - one restriction to this is if you accidentally selected "interim" instead of "permanent". As covered above in 4.4, in these circumstances a new permit would be required.



10 – Inspections and non-compliance process and outcomes (previously 3)

10.1 Inspection reference number (previously 3.1)
Auto-generated by Street Manager by taking the {WRN}, followed by a dash {-}, followed by the text {INSP}, followed by two digits starting with {01}, which automatically increase as more inspections are added to a works.



10.2 inspection category (previously 3.2)

- Options available dependent on inspection type 
- If SLG:
    - A 
    - Third party
    - Routine
- If reinstatement:
    - B 
    - C 
    - Third party
    - Routine
- If non compliance inspection:
    - Joint site visit
    - Follow up
    - Follow up completion

10.3 Inspection outcome (previously 3.3)

Options dependent on inspection type and category:
- SLG:
    - Pass
    - Failed - high
    - Failed - low
    - Unable to complete
- Reinstatement:
    - Pass
    - Failed - high
    - Failed - low
    - Unable to complete
- Non compliance - joint site visit:
    - Further inspection required
    - Withdraw defect
    - Unable to complete
- Non compliance - follow up & follow up completion:
    - Pass
    - Failed - high
    - Failed - low
    - Unable to complete

If the inspection outcome is ‘unable to complete inspection’ or ‘non compliant with conditions’, the user will be required to enter free text into the ‘inspection outcome details’ box. 


10.4 Restriction to adding inspection (previously 3.4)

'HA only able to add an Inspection if promoter has indicated an excavation was required. The answer to this question defaults to what was inputed at the time of the permit application, but can be changed.

Also, permit must be in progress or closed.

Note - this will change in the future to allow inspections on proposed works also.

10.5 - Adding an inspection (previously 3.5)
Inspections can be added against a work record from the point that a works record has been created on Street Manager. In other words, inspections can be added at every stage of a works record – from submitted right through to closed.

What’s more, the inspection start date must be in the past.
HAs have the ability to log additional information for their inspection regardless of its outcome (unable to complete/fail/pass - not just for a fail)
HAs can also upload evidence regardless of outcome (photo update consistent with the other uploads within SM)





11 – Fixed Penalty Notice (FPN) process and outcomes (previously section 2)

11.1 FPN status (previously section 2.1)

'See 'FPN Record' section of status diagram

Status of FPNs  

- Issued - when HA issues an FPN. (Legally mandatory status)
- Accepted - FPN status when promoter acknowledges receipt of FPN. (Optional status change)
- Paid - FPN status when HA selects 'Mark FPN as paid' once promoter payment has been received. (Optional status change)
- Disputed - FPN status when promoter enters into discussion with the HA about the validity of an FPN. (Optional status change)
- Withdrawn - FPN status when HA selects 'Withdraw FPN'. (Legally mandatory status)
- Paid (Discounted) - FPN status when HA adds a % discount to FPN as they are selecting 'Mark FPN as paid'. (Optional status change)

If the FPN status is withdrawn or disputed, the user will be required to enter a reason in the free text field provided. If the FPN status is accepted, this will be optional.


11.2 FPN reference number (previously section 2.2)

This is a unique number calculated and generated by Street Manager. The HA will serve an FPN against a particular works reference number. The format of the FPN reference number is as follows: {WRN}-FPN-{FPN count, two digits, padded with zero}

11.3 Issue date and time (previously section 2.3)
'Calculated by Street Manager. 'issue_date_time 
Date and time recorded to capture exact date and time that the FPN has been issued by the HA, visible in the audit/history trail


11.4 Work ID (previously section 2.4)
Calculated by Street Manager. 'work_id: is set by the database and will be automatically set to the next number in a sequence i.e. `1,2,3,4,5...`
Not shown on the front end - used to identify the works record in the back end






