# How to Integrate Deadline Funnel with ActiveCampaign \(API\)

The API integration with ActiveCampaign is the easiest and most flexible way to integrate Deadline Funnel with your ActiveCampaign account. Each Deadline Funnel campaign gets its own API integration.

**Important** : You will need to complete the setup of your first evergreen campaign before you will see the API integrations link in the left nav. Be sure to select **API Trigger** as the trigger and **ActiveCampaign** as your email service provider.

## Video Tutorial:

1. Click on API integrations to set up your ActiveCampaign integration:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b4679c72c7d3a099f2e7344/file-7MF13PLmCB.png)

1. Enter your ActiveCampaign API URL and API Key into the correct boxes. You can find these in your ActiveCampaign account by clicking on 'Settings' in the left navigation and then on 'Developer':

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b08689d0428635ba8b2c1cc/file-d4RVMrXpDA.png)

Inside the 'Developer' section you will find your 'API URL' and 'API Key' under API Access:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b086a5b2c7d3a2f9011eef1/file-0nguWnDwy6.png)

Once you've pasted both values in Deadline Funnel, click on 'Connect ActiveCampaign':

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b467e9a2c7d3a099f2e736b/file-3vSn3MpYg0.png)

1. Select or create a custom field to store each lead's deadline:

We call this the "deadline text" field, and it's just a field in ActiveCampaign that stores each lead's unique deadline. You can create this field from Deadline Funnel if you need to while you're setting up the integration.

If you want to use an existing custom field, select it from the drop-down. To create a new custom field, start typing into the box.

Go ahead and name it "deadlinetext" if you're not sure what to call it. You can always change it later.

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b467fc42c7d3a099f2e7370/file-lbqLR783BL.png)

1. Copy your Deadline Funnel webhook:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b4680590428630abc0bf8f8/file-GKWus6PvLV.png)

1. Add a webhook action to your automation in ActiveCampaign:

You can add this webhook anywhere in your automation where you want the deadline to be triggered.

To add the webhook in the automation, click on the plus symbol, then choose Conditions and Workflow, and then click on Webhook and paste your Deadline Funnel webhook in.

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/595a76230428637ff8d4430d/file-fYyR57Iyug.gif)

Now the deadline will begin for each contact as soon as they reach that webhook in your automation.

You can test by adding a contact to your automation, waiting for the webhook to happen, and then check under Event Tracking in Deadline Funnel to confirm their email address was received by Deadline Funnel.

## Important Note about Email Links

For the API integration to work you MUST use the Deadline Funnel [email links](http://documentation.deadlinefunnel.com/article/16-expiring-links) in any of your emails that link to a sales page with a countdown timer, or that link to a page in your funnel that links to another page with your countdown timer.

In other words, the API integration requires that your subscribers click one of the Deadline Funnel email links before they reach a page with a countdown. This is necessary in order to make sure each subscriber is assigned the correct deadline.

### How to Time Your ActiveCampaign Emails to Match Your Deadline \(optional\)

You can time your reminder emails to be in sync with your leads' individual deadlines. We have a guide on [how to do that here](https://documentation.deadlinefunnel.com/article/689-how-to-time-your-%20activecampaign-emails-to-match-your-deadline)!

If you have any questions, send us a message in chat or email us at [help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com).

