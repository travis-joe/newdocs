# How to Integrate Everwebinar with Deadline Funnel & MailChimp

Please watch this training on the fundamentals of integrating automated webinars into your marketing funnel first.

This tutorial covers integrating Deadline Funnel with MailChimp and the new version of EverWebinar using the API integration.

## To integrate your Deadline Funnel campaign with Everwebinar you need to:

## \*\*Integrate MailChimp with Deadline Funnel via API and set your deadline

to begin when someone subscribes to a list:\*\*

[**How to Integrate Deadline Funnel with MailChimp via API**](http://documentation.deadlinefunnel.com/article/354-how-to-integrate-%20deadline-funnel-with-mailchimp-api)

In the example that follows, we will use a list named, Attended Webinar. \( **Note** : Please give your MailChimp list a name that relates to your webinar.\)

**Create your evergreen Deadline Funnel Campaign:**

Set up your Deadline Funnel evergreen campaign based on the number of days between when someone _attends_ your webinar and the deadline for your promotion after the webinar. For example, for someone who registers on Monday for a Tuesday webinar, Deadline Funnel will calculate the numbers of days between Tuesday and the deadline for the campaign.

**Integrate your MailChimp account with your EverWebinar acccount:**

When you visit My Account &gt;&gt; Integrations, select MailChimp and follow the instructions for integrating your account.

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4ede372c7d3a7e9ae81114/file-cPtSKo22N3.jpg)

Once your Deadline Funnel API integration and campaign have been created, click on your webinar to edit it, select the Integrations tab, and select MailChimp to set rules:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4ede4b04286364bc95a560/file-VOgXPoSLfH.jpg)

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4ede5c04286364bc95a562/file-flMGvmBEBl.jpg)

Add an integration rule using your first trigger trigger event, 'when they attend the live webinar', and set the integration consequence as shown here, then click 'OK':

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4ede832c7d3a7e9ae8111d/file-gWSbWuHqJr.jpg)

Click 'Create integration rule' to add a second integration rule using a second trigger event, 'When they miss the live webinar', and set the appropriate integration consequence, then click 'OK':

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4ede962c7d3a7e9ae81120/file-kAGp06tHsV.jpg)

Navigate in your Deadline Funnel admin to Settings &gt;&gt; Advanced and copy your tracking pixel:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4edeb004286364bc95a569/file-wTa0Fdwodn.jpg)

Navigate to EverWebinar and go to Integrations &gt;&gt; Integrate a 3rd-party tracking system and paste your Deadline Funnel tracking pixel into the 'Webinar live room tracking' box:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e4edec504286364bc95a56d/file-78LoyOW7S9.jpg)

When you use either list to trigger the automation \(as shown in this example\), you're able to simplify your automation and run everyone through the same automation whether or not they actually attend the webinar.

When EverWebinar adds your webinar attendee to your MailChimp list, the Deadline Funnel webhook will trigger and begin the subscriber's deadline.This will coordinate the timing of your MailChimp emails and the Deadline Funnel deadline. Your leads will be tracked by email, cookies, and ip address.

## Email Follow-up Instructions:

* You will be unable to use the email countdown timer or 'deadlinetext' in emails that are sent from EverWebinar as they do not allow the placeholder required to use the subscriber email
* You can and should use Deadline Funnel email links in your follow-up emails to keep your countdown properly synced.
* We encourage you to use MailChimp for follow-up emails so that you have the option to include the Deadline Funnel animated countdown and the specific time and date of your subscriber's deadline, in the body of the email.

That's it!

If you have any questions, please let us know at [help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com).

