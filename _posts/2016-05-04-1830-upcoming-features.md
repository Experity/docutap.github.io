---
layout: post
title: Upcoming features in May
---

Changes to clarifying Delay as Pause. A new feature called Provider Check-in. Additionally an
updated Training Manual. Finally, an important note to your IT department and web developers.

## Delay, I mean Pause a Patient

#### Current functionality

Delay isn't really delay, it's Pause!

Some customers have the ability to delay calling back a specific patient. It appears as a "Delay"
button in a column labeled "Delay".

Unfortunately, this ability to Delay is confused with other actions within Clockwise.MD that also
use the keyword "Delay". This includes the features of delaying all callbacks and when patients
are delayed due to lengthening wait times.

![current delay column](/img/2016-05-04_current-delay-column.png)

#### Upcoming functionality

In an upcoming release, we will rename Delay to Pause.

![upcoming pause column](/img/2016-05-04_upcoming-pause-column.png)

<div class='updates notice'>

This change will be available during the week of 4/16/2016.

</div>

## Provider Check-In

This new feature adjusts your velocity as providers check in and out during the day.
Currently, the "Provider Slots" feature tracks the number of providers currently on staff.
Adding onto this feature, the new Provider Check-In system now adds the ability to track named
providers.

Additionally with Provider Check-In, you can track which Provider visits which specific Patients.
This information can be used in reports to show provider throughput and their patient satisfaction
scores captured using our Survey feature.

<div class='updates notice'>

This is available now and can be enabled by your Account Manager.

</div>

## Training manual

Have you been to training lately? If you haven't, we have a shiny new Training Manual that may
help your next internal training session for new employees.

<div class='updates notice'>

<!--
The training manual is
[available online](https://drive.google.com/file/d/0B7ZVEXRrL2ZIdjFFd21pTmI5Uzg/view).
-->

The training manual is <a href="https://drive.google.com/file/d/0B7ZVEXRrL2ZIdjFFd21pTmI5Uzg/view">
available online</a>.

</div>

## Dropping support for IFRAMEs

#### What is it?

Clockwise.MD allows you to embed a "Save Your Spot" button, wait times, maps and other widgets
that link over to Clockwise.MD's web site from your web site. This level of integration requires
web developers to copy/paste snippets of code into your web site.

An alternative to the widget embedding options is to use an IFRAME. IFRAMEs allow your web site
to embed another web page or site within a frame (i.e. box) on your web page.

#### Why change?

Using IFRAMEs is one of the easiest ways to put another web site's contents on your web page,
it's also insecure and support for it in modern browsers is continuing to stiffen.

Two common security risks for web sites are
[Clickjacking](https://www.owasp.org/index.php/Clickjacking) and
[Cross Frame Scripting](https://www.owasp.org/index.php/Cross_Frame_Scripting).
Both of which take advantage of IFRAMEs and both can be stopped by blocking IFRAMEs.

Google will also block Geolocation from working within embedded web sites that have a mixture of
secure and insecure documents. This change will break Clockwise.MD's ability to use a map
correctly when embedded within an IFRAME on your web site. For more details,
[read about Geolocation API removed from unsecured origins in Chrome 50](https://developers.google.com/web/updates/2016/04/geolocation-on-secure-contexts-only?hl=en).

<div class='updates notice'>

<p>IFRAMEs will be blocked starting in June.</p>

<p>Please update your web sites immediately if you use IFRAMEs. If you are unsure if your web site
uses IFRAMEs, please contact our <a href="https://www.clockwisemd.com/support">Support Team</a>.</p>

</div>
