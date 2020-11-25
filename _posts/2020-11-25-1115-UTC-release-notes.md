---
layout: post
title: Release Notes for 2020-11-25
---

Latest release notes for 2020.23 2020-11-25 at 1115-UTC.

<div class='features' markdown='1'>

#### Features

- {:.feature} To
prevent data transmission issues with PVM integrations, the application will no
longer allow document storage keys to be above 50 characters.
- {:.feature} This option appears in Settings > Online Scheduling.  The clinic can enable this setting to prevent
the same patient from scheduling more than one appointment for the same reason in the
span of 7 days.  If the
setting is enabled and the patient does not have their first appointment
cancelled, removed, or discharged they will get an error on the appointment reservation page that prevents them from reserving a duplicate appointment.
- {:.feature} On
the Settings > Document Template page, when a user updates a document
template and clicks Submit, a new pop up will appear.  It will ask if the
user would like to "reset" the rule date.  In other words, would
the change they made require that all patients should now be presented with
the updated document to sign, or not?  If they click "No, just update the
form" the dates stored as the last time the patient signed will not be
reset.
- {:.feature} When
the patient submits their eReg, the app should now only display the icon with
the check.

</div>

<div class='fixes' markdown='1'>

#### Fixes

- {:.fix} To
prevent data transmission issues with PVM integrations, the address line 1
field will be truncated at 25 characters and the birth sex field will be
truncated at 1 character.

</div>
