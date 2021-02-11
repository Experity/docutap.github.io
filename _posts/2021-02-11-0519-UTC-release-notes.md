---
layout: post
title: Release Notes for 2021-02-11
---

Latest release notes for 2021.3 2021-02-11 at 0519-UTC.

<div class='features' markdown='1'>

#### Features

- {:.feature} The intermittent issues for specific date fields causing the application to display an error message and making the system inaccessible has been resolved.
- {:.feature} When opening the Future Patients page, the application will default to only the next day of patients to improve performance.  If the user would like to see further into the future, the date parameter fields should be used.

</div>

<div class='fixes' markdown='1'>

#### Fixes

- {:.fix} On the Today's Patient page the Current Expected Callback Time column had been displaying the incorrect data when the patient's visit had been in the past.  This is now resolved.
- {:.fix} On the Today's Patient page, the Current Expected Callback Time column is now displaying the correct format for date and time.
- {:.fix} The date field within the New Reservation section of the Patient Detail modal now requires the use of the date picker to prevent data entry issues.
- {:.fix} When creating a new document template, the application will now default to the option "Every visit" for the frequency the patient should sign the document.  Users are free to update the setting at any time.
- {:.fix} The label for the Form Signature card within the  paperless registration setting is now displaying correctly.

</div>
