---
layout: post
title: Release Notes for 2020-11-13
---

Latest release notes for 2020.24 2020-11-13 at 1348-UTC.


<div class='fixes' markdown='1'>

#### Fixes

- {:.fix} There was an issue where many patients were stating they had all reserved the same appointment time.  They did not have confirmation texts and they were not on Today's Patients view. To prevent this misunderstanding in the future, a new window will be displayed clearly to the patient that their reservation was not saved.  Previously they got no indication that there was a problem other than the page being frozen.  We believe this is mistakenly conveying to the patient that they have the appointment time.
- {:.fix} There was an issue that when a patient in one queue was updated to be in another queue/provider occasionally they were not visible in the new queue. They were visible in the Today's Patients page after the change.  This was reproduced in-house and is now resolved with this release.
- {:.fix} Updates to the queue logic have been made to reduce the possibility of multiple patients reserving the same slot.
- {:.fix} Updates to the patient queue have been made to reduce the possibility of patients being inadvertently hidden from view after their slot is edited or updated.

</div>
