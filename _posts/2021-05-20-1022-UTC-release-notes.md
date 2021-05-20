---
layout: post
title: Release Notes for 2021-05-20
---

Latest release notes for 2021.10 2021-05-20 at 1022-UTC.

<div class='features' markdown='1'>

#### Features

- {:.feature} The Patient Queue and Nurse Screen have been enhanced to display the count of remaining slots for any visit reason that has a "Max Slots" value in the Settings >  Queues and Reasons page.  The count of remaining slots is valid for the present day and for that visit reason across all the queues it is used in.  The count will be reduced with any new appointment type added using that visit reason including the Staff Adds, Walk-ins, Onlines, Scheduled and appointments added through APIs.
- {:.feature} On the Undo Screen, if the user is trying to Add a previously removed appointment, but the Max Slot value for the visit reason on that appointment has already been reached, the Add button will be disabled and the user will see the following message when hovering over the button, "The clinic has reached its limit for this visit reason today."

</div>

<div class='fixes' markdown='1'>

#### Fixes

- {:.fix} The Recipient Type field on the text message exceptions setting has been updated to reduce confusion.

</div>
