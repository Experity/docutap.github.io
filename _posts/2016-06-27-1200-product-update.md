---
layout: post
title: June Product Update
---

## Reports are here!

![reports are coming](/img/2016-06-27-reports-are-here.jpg)

If you haven't tried out our new reports, make sure to click the link at the top of the Reports
page.

![new reports](/img/2016-06-27-reports-click-me.png)

Clockwise.MD account managers, product specialists and engineers have been working hard to bring
you even more information to your fingertips. We've released the following new types of reports.

#### Group reports

If you have more than one clinic, hospital or location - be sure to check out:

- Accuracy
- Patient Breakdown
- Patient Throughput
- ROI & Marketing
- Survey

![group reports](/img/2016-06-27-reports-group-example.png)

#### Performance reports

Performance scores now better reflect your individual configurations for a more accurate score.
The reports are now available at both the hospital and group levels.

#### Survey reports

If you use our survey products, we now provide a lot more detail at the individual and group levels:

![survey reports](/img/2016-06-27-reports-survey-example.png)

#### Email subscriptions

We're also excited to release email subscriptions later in July. You'll soon be able to subscribe
to any hospital or group report with any email address at any frequency including on certain days,
weekly or daily.

![email subscriptions](/img/2016-06-27-reports-email-subscriptions.png)

#### Moving to new reports

We'll enable email subscriptions and make Reports the main reports UI later in July.

If you have any feedback, please send them over to your account managers.

<div class='updates notice'>

Individual, group and survey reports are available now. Email subscriptions and a full migration
to the new reports will happen later in July.

</div>

## REMINDER: Pause a patient due to registration delays

#### Current functionality

Delay isn't really delay, it's Pause!

Some customers have the ability to communicate a registration delay to a patient.  Once the "delay"
button is pressed a message that says "waiting for authorization" will appear on the wait room TV.

![current delay column](/img/2016-05-04_current-delay-column.png)

![waiting for authorization](/img/2016-05-04_waiting-for-authorization.png)

Unfortunately, this ability to Delay is confused with other actions within Clockwise.MD that also
use the keyword "Delay". This includes the "Delay Callback" feature that adds minutes to a
patient's expected callback time, rather than simply displaying a message on the wait room TV.

#### Upcoming functionality

In an upcoming release, we will rename Delay to Pause. The same "Waiting for Authorization"
message will appear on the wait room TV.

![upcoming pause column](/img/2016-05-04_upcoming-pause-column.png)

<div class='updates notice'>

This change was originally scheduled for release in April but will now be available during the week
of 7/4/2016.

</div>

## REMINDER: We're dropping support for IFRAMEs

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

<p>IFRAMEs will be blocked starting on 7/7/2016.</p>

<p>Please update your web sites immediately if you use IFRAMEs. If you are unsure if your web site
uses IFRAMEs, please contact our <a href="https://www.clockwisemd.com/support">Support Team</a>.</p>

</div>
