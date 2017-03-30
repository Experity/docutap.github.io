---
layout: post
title: March Product Update
---

## Configurable Spanish

We've added functionality to our settings pages to make it easier to edit any patient-facing Spanish
communications. Simply click "En Espanol" on settings pages where applicable to view and edit
communications in Spanish.

![message contents](/img/2017-03-30-configurable-spanish-1.png)

![message configuration](/img/2017-03-30-configurable-spanish-2.png)

Reach out to your AM or Support Team today if you have a sizable Spanish-speaking patient
population and you **do not** have the Spanish option configured in Clockwise.

<div class='updates notice'>

Available now. Please contact your Account Manager for details.

</div>

## Text Message Wildcards

Wildcards allow you to site certain pieces of information, like the patient's time of visit or
position in queue, in real-time as the information continues to change. We've added a list of all
available wildcards to our **text message settings page** (hospitals/_ID_/settings/text_messages)
to allow you to easily utilize these inputs.  

![text message wildcards](/img/2017-03-30-texting-message-wildcards.png)

An example __Confirmation Message__:

> Your estimated visit is at **%{reserved_time}**. You'll receive a reminder msg
**%{pager_minutes}** mins before the visit. Please arrive 15 minutes before your visit time.
Reply to SMS. S for update, R to leave the line.

<div class='updates notice'>

Available now.

</div>

## Data Warehousing, Business Intelligence and Reporting

BI integrations really depend on the data you're querying for. Are you looking for the current
wait times, the patients currently being treated, all patients for the day, etc?

In addition to our Reports, we have three ways to pull data:

1. **Reporting Data**: Read data from our own data warehouse. Includes a query UI for flexible filters
and criteria selection. The data is not real-time, usually 5 to 45 mins behind production and is
non-PHI data. Available in CSV, PDF, Web, Images, Email.
2. **Exports Data**: Read data from our read replicas. No UI, single URL request at a time. The data is
near real-time, usually within 1 min of production and is non-PHI data. Available in CSV only.
3. **RESTful API**: Complete RESTful API for reading and writing directly against production. The data
is real-time and includes PHI data. Available in JSON.

Most customers only need #1 or #2 since they're not building a dashboard of patient demographics
but instead trying to track throughput across facilities and make decisions on staff scheduling.
In those instances, knowing how many patients named "Bob" went through yesterday isn't informative
but instead the number of walk-ins or online patients. That data is accessible via #1 and #2.

However, if you're trying to match up data between Clockwise.MD and your EMR, then option #3 is
your only option but you may struggle with name matching since the patient might register
"Bill" in Clockwise.MD but your EMR contains "William" and the phone number format doesn't match.
You'll need to build out ways of matching data types, formats, soundex/familiar names, etc.

You can also mix multiple systems together. For instance, we have customers pull the full list of
non-PHI patients every minute from the 2nd system and then pull PHI data via the API from the
3rd system.

Depending on your needs, we can guide you towards which systems to interface with.

Any information that you could provide on the data elements you're wishing to monitor, the
information you want to present and the insights you're trying to uncover will help us craft a
solution that works best in your environment.

<div class='updates notice'>

Available now. Please contact your Account Manager for details.

</div>
