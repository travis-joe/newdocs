###  Video Overview:

Please watch this training on the fundamentals of integrating automated
webinars into your marketing funnel first.

  
This tutorial covers integrating Deadline Funnel with ConvertKit and the new
version of EverWebinar using the API integration.

## To integrate your Deadline Funnel campaign with Everwebinar you need to:

**Create your evergreen Deadline Funnel Campaign:**

Set up your Deadline Funnel evergreen campaign based on the number of days
between when someone  attends your webinar and the deadline for your promotion
after the webinar. For example, if someone registers for your webinar on
Monday, but attends your webinar on Tuesday, the deadline will start counting
down on Tuesday.

**Create your webinar-related tags in your ConvertKit account:**

We suggest 2 webinar-related tags, one for those who attended the webinar and
one for those who missed the webinar. In the example that follows, we have
created 2 tags in ConvertKit named, samplewebinar-attended-webinar and
samplewebinar-missed-webinar.  **Note** : Please replace 'samplewebinar' with
the actual name of your webinar when you are creating your tags.

**Integrate your ConvertKit account with your EverWebinar acccount:**

When you visit My Account >> Integrations, you can select ConvertKit and
follow the instructions for integrating the accounts.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4ede372c7d3a7e9ae81114/file-cPtSKo22N3.jpg)

Once your Deadline Funnel campaign and ConvertKit tags have been created,
click on your webinar to edit it, select the Integrations tab, and select
ConvertKit to set rules:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4ede4b04286364bc95a560/file-VOgXPoSLfH.jpg)

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4ede5c04286364bc95a562/file-flMGvmBEBl.jpg)

Add an integration rule using your first trigger event, 'they attended the
webinar', and adding the appropriate tag as shown here:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4ede832c7d3a7e9ae8111d/file-gWSbWuHqJr.jpg)

Click 'Create integration rule' to add a second integration rule using a
second trigger event, 'when they miss the live webinar', and add the
appropriate code for that then click 'OK':

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4ede962c7d3a7e9ae81120/file-kAGp06tHsV.jpg)

Navigate in your Deadline Funnel admin to Settings >> Advanced and copy your
tracking pixel:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4edeb004286364bc95a569/file-wTa0Fdwodn.jpg)

Navigate to EverWebinar and go to Integrations >> Integrate a 3rd-party
tracking system and paste your Deadline Funnel tracking pixel into the
'Webinar live room tracking' box:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4edec504286364bc95a56d/file-78LoyOW7S9.jpg)

Set up a ConvertKit Rule that will trigger your Deadline Funnel webhook when
either tag is applied:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4ef1342c7d3a7e9ae8123a/file-7k5k5rsrUF.jpg)

**To trigger the deadline based on when people are added to your sequence in
Convertkit, you'll need to set up our direct integration with Convertkit.**[
**Check out our guide on how to do that
here.**](https://documentation.deadlinefunnel.com/article/391-how-to-integrate-deadline-funnel-with-convertkit-api)

When you use either tag to trigger the rule (as shown in this example), you're
able to simplify your automation and run everyone through the same rule
whether or not they actually attend the webinar.

Another way to use this integration would be to set up two different rules in
ConvertKit and have one rule triggered when someone attends, and then the
other rule triggered if someone does not attend. This gives you precise
control of what messages your subscribers will see based on their specific
actions.

When your webinar tag is applied, the Deadline Funnel webhook will trigger and
begin the subscriber's deadline.This will coordinate the timing of your
ConvertKit emails and the Deadline Funnel deadline. Your leads will be tracked
by email, cookies, and ip address.  

## Email Follow-up Instructions:

  * You will be unable to use the email countdown timer or 'deadlinetext' in emails that are sent from EverWebinar as they do not allow the placeholder required to use the subscriber email
  * You can and should use email links in your follow-up emails to keep your countdown properly synced.
  * We encourage you to use ConvertKit for follow-up emails so that you have the option to include the Deadline Funnel animated countdown and the specific time and date of your subscriber's deadline, in the body of the email.

That's it!

If you have any questions, please let us know at
[help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com).

