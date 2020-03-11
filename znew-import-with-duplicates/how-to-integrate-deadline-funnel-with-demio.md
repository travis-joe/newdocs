# How to integrate Deadline Funnel with Demio

## Introduction

In this video, we provide an overview of how to integrate your webinar platform with Deadline Funnel.

## Emails

There are two types of emails you'll be sending:

* Pre-webinar \(registration links, reminders\)
* Post-webinar \(replay, sales emails\)

You can use Demio to send all of the pre-webinar notifications, but it's important to use your actual email platform \(e.g. ActiveCampaign\) for sending out all emails after the webinar happens.

This means that your replay email as well as your post-webinar sales emails need to be sent from your email platform \(e.g. ActiveCampaign\), and not sent through Demio.

## Two integration options

There are two main ways to integrate Demio and Deadline Funnel.

If you are using one of these email platforms, follow the direct integration method:

* ActiveCampaign
* AWeber
* ConvertKit
* Drip
* Infusionsoft
* Ontraport

If you are using a different email platform, follow the optin integration method.

## Direct integration method

The first step of the direct integration method is to integrate Demio with your email platform.

The most important part of this step is that you send these two tags from Demio to your email platform, as shown in the following screenshot:

* A tag that is applied when someone "came to the webinar" - e.g. samplewebinar-attended-webinar
* A tag that is applied when someone "did not come" - e.g. samplewebinar-missed-webinar

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d28ba502c7d3a2ec4becf3d/file-vWDb5OTLQp.png)

The next step of the direct integration method is to integrate Deadline Funnel with your email platform, so that whenever either of those two tags are applied in your email platform, Deadline Funnel starts the tracking for that subscriber.

Please click on one of the following links to view the integration guide for your email platform:

* [ActiveCampaign](https://documentation.deadlinefunnel.com/category/319-activecampaign)
* [AWeber](https://documentation.deadlinefunnel.com/category/326-aweber)
* [ConvertKit](https://documentation.deadlinefunnel.com/category/320-convertkit)
* [Drip](https://documentation.deadlinefunnel.com/category/318-drip)
* [Infusionsoft](https://documentation.deadlinefunnel.com/category/321-infusionsoft)
* [Ontraport](https://documentation.deadlinefunnel.com/category/317-ontraport)

## Optin integration method:

If you are using a different email platform, then you will need to use the optin integration method instead.

First, make sure that you only allow same-day/just-in-time registration. Doing this keeps the number of days between the registration event and the deadline for your promotion a specific number of days.

In some cases this might not be ideal for what you had planned, but it's required in order to synchronize the timing of your follow-up emails and the Deadline Funnel tracking - since Demio can't tell your email system to apply a tag.

If you have any questions, please let us know at [help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com).

