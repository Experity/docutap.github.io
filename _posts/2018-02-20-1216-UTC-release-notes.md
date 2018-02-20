---
layout: post
title: Release Notes for 2018-02-20
---

Latest release notes for 2018-02-20 at 1216-UTC.

<div class='legend' markdown='1'>

#### Legend

All changes are available immediately unless labeled as internal or dark code:

- {:.legend} [internal] changes are only visible or applicable to Clockwise.MD staff.
- {:.legend} [dark code] changes are hidden from general use until made visible at a later date.

</div>

<div class='features' markdown='1'>

#### Features

- {:.feature} Scheduled Providers workflow now supports filtering reasons for new and existing patient types
- {:.feature} Scheduled Providers workflow now auto-selects a reason if only a single one is able to be chosen
- {:.feature} Scheduled Providers workflow will now no longer redundantly ask if a patient is new or existing

</div>

<div class='fixes' markdown='1'>

#### Fixes

- {:.fix} Extra fields no longer appear to be editable from the DataViews patient edit modal and patient queue if no extra field exists for the patient and custom field in question, and extra fields can now be edited from the DataViews patient edit modal even if the corresponding custom field is not configured as a DataViews column.
- {:.fix} Fixed case where Multi Patient velocities that perfectly overlap running velocity causes errors

</div>
