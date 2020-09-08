---
layout: post
title: Release Notes for 2020-09-08
---

Latest release notes for 2020.18 2020-09-08 at 1846-UTC.

<div class='features' markdown='1'>

#### Features

- {:.feature} Text 'Here' to Auto Check In is a functionality to allow patients to let the clinic staff know that they have arrived and create a touch less check in experience.In order to use the Auto Check In feature, the following must be completed:On the Settings > Text Messages page:A new setting 'Text HERE to Auto Check In' is added. To use Auto Check In functionality, enable 'Text HERE to Auto Check In'. You will need to add the verbiage 'Text HERE when you arrive at the clinic' to the Pager Message and Late Message.When patients arrive at the clinic, and text 'HERE', patients will be checked in and you will see the 'Check In' button change to 'Yes' in the Here column.Patients will be able to check in for a visit by texting 'HERE' only in the time window that is defined in Settings > Checkin Kiosk > Checkin Window (minutes). For e.g. if the check in window (minutes) is 120 and visit time is 1 pm, text here to check in will only work starting 11 am same day.
- {:.feature} In Settings > Form Fields > Document Template there is a new checkbox to indicate that a document is a HIPAA consent form.  This setting applies to Practice Velocity users.  This data is not yet being consumed but additional work will be done in the near future to ensure this setting can be used to populate the HIPAA consent form field in Practice Velocity.
- {:.feature} A new bi-directional workflow is added for PVM and Clockwise integrated clinics. In order for the Coming back status to be in sync between PVM and Clockwise, 'Allow leave and come back' check box if enabled and checked on Add Walkin Patient and Quick Add Patient in Clockwise, then the patient is added to the Patient Queue but is not checked in and on PVM logbook Arrival Status for a patient will be set to 'Coming Back'.
- {:.feature} The Velocity settings have been updated to ensure the application honors first and foremost a Special Velocity set for a specific date.  Next in the hierarchy is the Velocity setting for a day of each week.  Lastly, if no other Velocity settings apply, the application will honor the Default Velocity.
- {:.feature} On the Patient Queue, there is now a pagination feature at the bottom of the screen.  The user may select the number of patient rows per page at the bottom, left on the screen.  The number related to the total patients in the view at the bottom, middle of the screen is shown, and the ability to go to the Next or Previous page using the text on the bottom right is now available.
- {:.feature} Insurance cards with Group IDs that have spaces or dashes in them will be recognized and populated in the Group ID field after the patient types the initial 3 characters.
- {:.feature} 'Patient Suffix' on the visits new page is now a drop down field. Patients can select a value from the following options: 'Jr.', 'Sr.', 'I', 'II', 'III', 'IV'

</div>

