---
layout: post
title: Release Notes for 2020-10-30
---

Latest release notes for 2020.22 2020-10-30 at 1337-UTC.

<div class='features' markdown='1'>

#### Features

- {:.feature} Returning Patient Workflow eliminates the need for patients to sign the consent forms every time they visit the clinic based on a setting in Document Templates. The option selected in Settings > Document Template > 'Require the patient to sign this form' will drive when the consent form is presented for signature in the registration form. For example, if a patient visits the clinic every month and  the option selected in 'Require the patient to sign this form' field is 'Once a Year', consent form will be presented for signature annually. Every month when the patient registers for the appointment, consent form will display 'previously signed' and will not require patient to sign again.
- {:.feature} New functionality to create Notification Exception for Confirmation Text based on a Visit Reason is added to the application. In Settings > Text Messages > Confirmation Message section, a new parameter "Visit Reason" is added. Notification Exception for a visit reason can be created by selecting an option from Appointment Queue and then selecting a Visit Reason. (Only the visit reasons associated to the queue selected will be displayed).
- {:.feature} The Registration Partial Save functionality saves registration data in the event a patient is not able to complete the registration. The registration PDF will display the partial data that the patient has entered so far. A new icon is added to the Reg. Form button to indicate that registration is incomplete.
- {:.feature} Prevent Duplicate Appointment functionality will not allow a patient to reserve another appointment if that patient already has a reserved appointment (that has not been removed, canceled  or discharged from the queue). A new setting  is added to Settings > Online Scheduling - "Allow only one active reservation per patient and per visit reason" If this setting is enabled, the application will check for a duplicate patient visit based on the Patient First Name, Patient Last Name, Phone Number, DOB and Visit Reason. When a patient is attempts to reserve an appointment on visits/new page, application will check to see if the patient visit is duplicate or not based on the validation logic when they click 'get in line' If a duplicate is found the patient will see a message - 'Looks like you've already reserved an appointment with this name and cell phone for this visit reason. Please schedule an appointment for a different person or reason.'
- {:.feature} The texting window that opens from the Text button on the Patient Queue now functions properly when opened on a mobile device and allows the user to scroll and send a message.
- {:.feature} Returning Patient Workflow eliminates the need for patients to sign the consent forms every time they visit the clinic based on a setting in Document Templates. A new drop down field is added in Settings > Document Templates > "Require the patient to sign this form". This dropdown field will be available for all consent forms set up for a clinic. The Consent Form signature option will be presented for returning patients based on the selection in this field.
- {:.feature} The Registration Partial Save functionality saves registration data in the event patients are not able to complete the registration. Upon return to the registration form via the registration link, previously entered registration data will be prefilled and patients will be able to continue filling the form from where they had left.

</div>

