This tutorial explains how you can create a 'wait' condition with ConvertKit
so that your promotion emails begin and end on specific days of the week.

Many Email Service Providers offer conditional waits, i.e., wait until Monday
at midnight, then send the webhook.

ConvertKit offers automations and rules, but doesn't have a 'wait' condition,
so this offers a workaround.

## Video Tutorial:

## Timing Emails for a Specific Day of the week:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5aff3a260428635ba8b27727/file-9JcUaluDiw.png)

### Scenario 1:

You want your promotional emails to always start on a Monday and end on a
Friday.

As explained in the video, in this scenario you cannot set a deadline based on
the number of days, because the number of days will be variable.

## Our recommendation: Multiple Sequences:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5aff3c8d2c7d3a2f9011a809/file-b4ZsmBvNfc.png)

Multiple sequences will allow you to control the start of your promotional
sequence so that the distance between the start and end of your promotional
emails is the same after the webhook is triggered.

### Three Sequences Scenario:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5aff4e840428635ba8b277e8/file-8ZWSGHGNOH.png)

  * Email 1 adds your lead to an Introductory/Waiting List Sequence
  * Email 2 adds a tag to trigger your Deadline Funnel webhook and sends a single promotional email
  * Email 3 kicks off your promotional sequence that runs Tuesday through Friday

Here are some of the reasons for setting up the promotion this way:

  * The API integration with ConvertKit is set to use a tag in ConvertKit as the trigger
  * Due to how ConvertKit currently works it's easiest to set the tag when someone first enters a sequence, which is why we're starting a new sequence on a specific day to trigger the webhook

**Note:** It's important to set the email time for the promo sequence to be
sent 1 hour before the Monday-only email is set. You should test this, but
this is to make sure that the first promotional email is sent on Tuesday and
not later in the day on Monday.

If you have any questions, send us a message in chat or email us at
[help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com).

