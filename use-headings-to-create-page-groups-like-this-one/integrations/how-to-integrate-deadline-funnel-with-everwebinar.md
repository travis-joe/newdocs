## Introduction

In this video, we provide an overview of how to integrate your webinar
platform with Deadline Funnel.

If you have any questions about these options - We have live chat in the
bottom right hand corner of the screen Mon-Fri, 8am-5pm ET. Or you can shoot
us a quick email at help@deadlinefunnel.com :)

## Emails

There are two types of emails you'll be sending:

  * Pre-webinar (registration links, reminders)
  * Post-webinar (replay, sales emails)

You can use EverWebinar to send all of the pre-webinar notifications, but it's
important to use your actual email platform (e.g. ActiveCampaign) for sending
out all emails after the webinar happens.

This means that your replay email as well as your post-webinar sales emails
need to be sent from your email platform (e.g. ActiveCampaign), and not sent
through EverWebinar.

## Two integration options

There are two ways to integrate EverWebinar and Deadline Funnel.

If you are using one of these email platforms, follow the direct integration
method:

  * ActiveCampaign
  * AWeber
  * ConvertKit
  * Drip
  * Infusionsoft
  * Ontraport

If you are using a different email platform, follow the optin integration
method.

## Direct integration method

To use the direct integration method, you must be using an ESP that integrates
with both Deadline Funnel and EverWebinar via API.

If you use ActiveCampaign, ConvertKit, Drip, Ontraport, or InfusionSoft this
gives you the most flexibility because EverWebinar can send a trigger to your
email system to apply a tag to the lead's record when they attend or miss the
"live" webinar. Said another way, these are currently the email software
systems that BOTH Deadline Funnel and EverWebinar integrate with via API--and
that give you the most flexibility:

  * [How to integrate Deadline Funnel & ActiveCampaign](http://documentation.deadlinefunnel.com/article/494-how-to-integrate-everwebinar-with-deadline-funnel-activecampaign-new)
  * [How to Integrate Deadline Funnel & Drip](http://documentation.deadlinefunnel.com/article/496-how-to-integrate-everwebinar-with-deadline-funnel-drip-new)
  * [How to Integrate Deadline Funnel & ConvertKit](http://documentation.deadlinefunnel.com/article/497-how-to-integrate-everwebinar-with-deadline-funnel-convertkit-new)
  * [How to Integrate Deadline Funnel & Ontraport](http://documentation.deadlinefunnel.com/article/500-how-to-integrate-everwebinar-with-deadline-funnel-ontraport-new)
  * [How to Integrate Deadline Funnel & Infusionsoft](http://documentation.deadlinefunnel.com/article/499-how-to-integrate-everwebinar-with-deadline-funnel-infusionsoft-new)

##  **If you are not using the Deadline Funnel API:**

If you are using a different email platform, then you will need to use the
optin integration method instead.

First, make sure that you only allow same-day/just-in-time registration. Doing
this keeps the number of days between the registration event and the deadline
for your promotion a specific number of days.

In some cases this might not be ideal for what you had planned, but it's
required in order to synchronize the timing of your follow-up emails and the
Deadline Funnel tracking - since EverWebinar can't tell your email system to
apply a tag.

Once you've done this, you'll need to establish the trigger for the deadline
based on when people optin.

We recommend using Zapier to do this if possible:

[How to Trigger a Countdown Upon Subscribe using
Zapier](https://documentation.deadlinefunnel.com/article/373-how-to-trigger-a-countdown-upon-subscribe-using-zapier)

If Zapier is not an option with your ESP, you can use our Optin Form trigger:

[How to Integrate Deadline Funnel Using the Optin Form
Feature](https://documentation.deadlinefunnel.com/article/17-optin-form)

