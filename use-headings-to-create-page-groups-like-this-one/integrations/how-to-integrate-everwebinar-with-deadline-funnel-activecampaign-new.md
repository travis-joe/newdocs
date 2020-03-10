# How to Integrate Everwebinar with Deadline Funnel & ActiveCampaign

Please watch this training on the fundamentals of integrating automated webinars into your marketing funnel first.

This tutorial covers integrating Deadline Funnel with ActiveCampaign and the new version of EverWebinar using the API integration.

## To integrate your Deadline Funnel campaign with Everwebinar you need to:

**Create your evergreen Deadline Funnel Campaign:**

Set up your Deadline Funnel evergreen campaign based on the number of days between when someone _**attends**_ your webinar and the deadline for your promotion after the webinar. For example, if someone registers for your webinar on Monday, but attends your webinar on Tuesday, the deadline will start counting down on Tuesday.

**Create your webinar-related tags in your ActiveCampaign account:**

We suggest 2 webinar-related tags, one for those who attended the webinar and one for those who missed the webinar. In the example that follows, we have created 2 tags in ActiveCampaign named, webinarname-attended-webinar and webinarname-missed-webinar. **Note** : Please replace 'webinarname' with the actual name of your webinar when you are creating your tags.

**Integrate your ActiveCampaign account with your EverWebinar acccount:**

When you visit My Account &gt;&gt; Integrations, you can select ActiveCampaign and follow the video/instructions for integrating the accounts.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4ede372c7d3a7e9ae81114/file-%20cPtSKo22N3.jpg)

Once your Deadline Funnel campaign and ActiveCampaign tags have been created, click on your webinar to edit it, select the Integrations tab, and select ActiveCampaign to set rules:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4ede4b04286364bc95a560/file-%20VOgXPoSLfH.jpg)

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4ede5c04286364bc95a562/file-%20flMGvmBEBl.jpg)

Add an integration rule using your first trigger event, 'they attended the webinar', and adding the appropriate tag as shown here:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4ede832c7d3a7e9ae8111d/file-%20gWSbWuHqJr.jpg)

Click 'Create integration rule' to add a second integration rule using a second trigger event, 'when they miss the live webinar', and add the appropriate code for that then click 'OK':

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4ede962c7d3a7e9ae81120/file-%20kAGp06tHsV.jpg)

Navigate in your Deadline Funnel admin to Settings &gt;&gt; Advanced and copy your tracking pixel:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4edeb004286364bc95a569/file-%20wTa0Fdwodn.jpg)

Navigate to EverWebinar and go to Integrations &gt;&gt; 3rd Party Tracking Systems

> > Embed a 3rd-party tracking system:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4ee0d52c7d3a7e9ae8114c/file-%20vzkj5Nfvlk.jpg)

Paste your Deadline Funnel tracking pixel into the 'Webinar live room tracking' box:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4edec504286364bc95a56d/file-78LoyOW7S9.jpg)

Set up an ActiveCampaign automation that will trigger your Deadline Funnel webhook when either tag is applied:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e50501704286364bc95b54f/file-%20hwnHxfFcx8.jpg)

**To trigger the deadline based on a webhook, as shown above, you'll need to set up our direct integration with Activecampaign.**[ **Check out our guide on how to do that here.**](https://documentation.deadlinefunnel.com/article/244-how-to-%20integrate-deadline-funnel-with-activecampaign-api)

When you use either tag to trigger the automation \(as shown in this example\), you're able to simplify your automation and run everyone through the same automation whether or not they actually attend the webinar.

Another way to use this integration would be to set up two different automations in ActiveCampaign and have one automation triggered when someone attends, and then the other automation triggered if someone does not attend. This gives you precise control of what messages your subscribers will see based on their specific actions.

When your webinar tag is applied, the Deadline Funnel webhook will trigger and begin the subscriber's deadline. This will coordinate the timing of your ActiveCampaign emails and the Deadline Funnel deadline. Your leads will be tracked by email, cookies, and ip address.

## Email Follow-up Instructions:

* You will be unable to use the email countdown timer or 'deadlinetext' in emails that are sent from EverWebinar as they do not allow the placeholder required to use the subscriber email.
* You can and should use email links in your follow-up emails to keep your countdown properly synced.
* We encourage you to use ActiveCampaign for follow-up emails so that you have the option to include the Deadline Funnel animated countdown and the specific time and date of your subscriber's deadline, in the body of the email.

That's it!

If you have any questions, please let us know at [help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com).

