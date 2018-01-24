---
layout: post
title: Release Notes for 2018-01-24
---

Latest release notes for 2018-01-24 at 1215-UTC.

<div class='legend' markdown='1'>

#### Legend

All changes are available immediately unless labeled as internal or dark code:

- {:.legend} [internal] changes are only visible or applicable to Clockwise.MD staff.
- {:.legend} [dark code] changes are hidden from general use until made visible at a later date.

</div>

<div class='features' markdown='1'>

#### Features

- {:.feature} [Internal] Copy Queue tool now catches and activates existing but inactive reasons on the target queue(s).
- {:.feature} Next available visit calculations now account for walkins who cannot fit before a configured midday break.
- {:.feature} Available times API (/v1/hospitals/{hospital_id}/times) now supports filtering by reason description.
- {:.feature} Auto reschedule now respects end-of-day scheduling restrictions when moving late online appointments.

</div>

<div class='fixes' markdown='1'>

#### Fixes

- {:.fix} [Internal] Integration page queue mappings now accurately reflect whether they are on or off
- {:.fix} [Internal] Fixed stale appointment cleanup in chef12 environments (i.e. staging)

</div>
