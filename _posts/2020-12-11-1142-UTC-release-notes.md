---
layout: post
title: Release Notes for 2020-12-11
---

Latest release notes for 2020.25 2020-12-11 at 1142-UTC.

<div class='features' markdown='1'>

#### Features

- {:.feature} Enhancements
have been made to the process for generating the list of patients in the queue
and the resulting available times.  There were areas of the application
that were not running these two methods simultaneously which intermittently
left the set of available times incorrect.  All areas of the application
have been updated to run both methods.
- {:.feature} There
are different combinations of settings regarding reasons and times that neglect
the system requirements for slot creation.  Updates have been made to
ensure the interdependencies for reason and time are met regardless of hospital
settings.
- {:.feature} There
is a setting to turn on or off the 24/7 availability and when it is turned on
the entire patient queue is recalculated.  It has been found that this setting
is being turned on inadvertently and this warning will help prevent large
numbers of patient queue recalculations.

</div>

<div class='fixes' markdown='1'>

#### Fixes

- {:.fix} The defect in the
integration with xPV when a user in Clockwise marked a patient for "Leave
and Come Back" was not showing the correct status in xPV and has been
corrected.
- {:.fix} A
defect in the appointment create logic was allowing multiple slots for the same
time to be booked via API and is now resolved. This specific issue was only
related to appointments being booked outside the hours of operation.

</div>
