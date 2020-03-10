This article explains how to connect Actionetics or ClickFunnels with Deadline
Funnel via an API integration so that when a lead submits a ClickFunnels optin
form their Deadline Funnel tracking will begin. You can also trigger tracking
when someone makes a purchase.

**Important** :  You need to complete the setup of your first evergreen
campaign before you will see the API integrations link in the left navigation.
Create an Evergreen campaign with an API/Webhook trigger to follow along with
this tutorial.

### When would I use this integration?

This integration enables you to sync Deadline Funnel and ClickFunnels via API
if you’re using an email service provider that Deadline Funnel doesn't offer
an API integration with. If you're using an email provider we do integrate
with via API directly, it's best to use the API integration for that email
service.

##  Video Tutorial:

## Set Up the Webhook

1\.  Navigate to 'API Integrations'. Click 'Add New Integration' and then select Actionetics/Clickfunnels: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b6cb12d0428631d7a89d43b/file-CB2TKr8P5f.png)


2\. Click to copy the Webhook URL for ClickFunnels/Actionetics: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b57592c2c7d3a03f89ceed1/file-8rax7liPEa.png)


4\. Return to ClickFunnels and click 'Settings' for the page you are integrating with Deadline Funnel: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/591cbc742c7d3a057f892de6/file-Jv8oBbv63M.png)


5\. Scroll down and click 'Manage Your Funnel Webhooks': 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/591cbcac0428634b4a333966/file-8VFqGnCNzI.png)


6\. Click '+ New Webhook': 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/591cbcd72c7d3a057f892dec/file-TKKqFaAnPD.png)


7\. Paste the Webhook URL from Deadline Funnel into the box, select 'contact_created' as the Event, and click 'Create Funnel Webhook': 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/591cbd6c2c7d3a057f892df2/file-8zvsK6ZBpR.png)

When someone submits the ClickFunnels optin form, the information will be sent
to Deadline Funnel and Deadline Funnel will start tracking their deadline.

**Note: You will select 'purchase_created' as the event if you want to trigger
your countdown upon purchase.**

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5afc7bcc042863158411da59/file-riyGlWPZdL.png)

## Important Note about Email Links

For the API integration to work you MUST use the Deadline Funnel  [email
links](http://documentation.deadlinefunnel.com/article/16-expiring-links) in
any of your emails that link to a sales page with a countdown timer, or that
link to a page in your funnel that links to another page with your countdown
timer.

In other words, the API integration requires that your subscribers click one
of the Deadline Funnel email links before they reach a page with a countdown.
This is necessary in order to make sure each subscriber is assigned the
correct deadline.

## Don't Forget to Test

Be sure to opt in through your ClickFunels optin form and click on the links
in the emails and verify that the tracking is working correctly. It's
important to test your funnel before sending live traffic.

You can learn more about testing your funnel here: [Testing Your Deadline
Funnel Campaign](http://documentation.deadlinefunnel.com/article/364-testing-your-deadline-funnel-campaign)

As of the most recent update to this article, Actionetics does not offer
custom fields. This means that you have all the functionality of some of our
other email software integrations... except for the ability to mail-merge the
lead's actual "deadline text" into your Actionetics emails. For more
information on this feature, click
[here](http://documentation.deadlinefunnel.com/article/224-how-to-personalize-your-emails-with-the-deadline-text-field).

If you have any questions, please let us know at
[help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com).

