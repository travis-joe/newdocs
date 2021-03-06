# How to Integrate Deadline Funnel with HubSpot \(API\)

Our API integration allows you to create a connection with HubSpot that triggers a Deadline Funnel campaign when a new contact is added to HubSpot.

**Important Note:** You must have an Enterprise account with HubSpot in order to use this integration.  
\*Marketing Hub Professional accounts or Sales Hub Professional seats purchased before November 1, 2018 will have legacy access to the "Trigger a webhook workflow action."  
[For more information, please refer to this HubSpot help article.](https://knowledge.hubspot.com/articles/kcs_article/workflows/how-do-%20i-use-webhooks-with-hubspot-workflows)

## Video Tutorial:

## How to set up the integration between HubSpot and Deadline Funnel

1. Navigate to 'API integrations' in the Deadline Funnel navigation and copy your Deadline Funnel webhook, as you will need to add this to Hubspot:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b4cb8a70428631d7a88f2a1/file-Cr0Ge83vgD.png)

## How to set up your HubSpot webhook:

1. Navigate to Automations &gt; Workflows in your HubSpot account and edit your existing workflow or create a new one:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b4e14770428631d7a8904d0/file-LPZaBISJEY.png)

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b4e15bc0428631d7a8904ed/file-sRpGxcEwS2.png)

1. Click the 'plus' sign to 'Add an action':

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b4e17532c7d3a03f89caff5/file-fK80EahyI3.png)

1. Select 'Trigger a webhook' for the action:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b4e17cd0428631d7a8904ff/file-i4X8a96fa8.png)

1. Select, 'Post' for the method, paste your Deadline Funnel webhook URL into the box and click 'Save':

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b4e187e2c7d3a03f89cb00a/file-YRLzIMg2BB.png)

### How to test your integration

You can test your webhook integration by adding a new contact, waiting until the contact has reached the trigger point in your workflow, and then checking under 'Event Tracking' in Deadline Funnel to confirm their email address was received by Deadline Funnel.

### Important Note about Email Links

For the API integration to work you MUST use the Deadline Funnel [email links](http://documentation.deadlinefunnel.com/article/16-expiring-links) in any of your emails that link to a sales page with a countdown timer, or that link to a page in your funnel that links to another page with your countdown timer.

In other words, the API integration requires that your subscribers click one of the Deadline Funnel email links before they reach a page with a countdown. This is necessary in order to make sure each subscriber is assigned the correct deadline.

If you have any questions, please let us know at [help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com).

