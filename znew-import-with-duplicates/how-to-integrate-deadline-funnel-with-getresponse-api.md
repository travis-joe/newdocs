# How to Integrate Deadline Funnel with Getresponse \(newimport/API\)

You can integrate Deadline Funnel with GetResponse using the API and trigger your countdown based on when someone subscribes to your list.

\(Note: currently the GetResponse restricts their webhook or "callback" to be triggered only on certain events, such as a subscription.\)

## Integrate Deadline Funnel with GetResponse

Important: You will need to complete the setup of your first evergreen campaign before you will see the API integrations link in the left nav.

1. In your Deadline Funnel dashboard, click on 'API Integrations' in the left hand menu, click 'Add New Integration', then select GetResponse from the next screen. It will then take you to the following screen where it asks for your API Key:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5ba16ad22c7d3a16370f410b/file-owysWkcXUg.png)

2. To get your API Key, go to your GetResponse account, navigate to the menu in the top right hand corner &gt; Integrations & API.

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d14b7f32c7d3a6ebd22a0c8/file-0pSL0lUrnX.jpg)

3. If you already have a key, copy that, if not go ahead and hit 'Generate Key' to generate a new key and copy the new key:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d14b80d04286305cb87c850/file-vZuVyWGzRD.jpg)

The page will ask you to name the key for your reference, you can use any name here:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d14b86a04286305cb87c853/file-ykxtXqEEy0.jpg)

Finally, copy the key:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d14b87604286305cb87c854/file-FoPqxsVY3x.jpg)

4. Now paste the API key into the box in Deadline Funnel and hit 'Connect GetResponse'.

5. On the next screen you can select the List that you want to use and select or create the custom field to hold the lead's deadline. Once you've selected both, a webhook URL will be created. Copy this webhook URL, as you'll need to add it in your GetResponse account:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5ba16f3c0428631d7a8b4f33/file-p0ZgJZp7x8.png)

6. **Enable Callback** in your GetResponse account, **select "Subscribes"** , and add the Deadline Funnel webhook so that the Deadline Funnel webhook is triggered when a subscriber is added to the list you selected in Deadline Funnel. **Make sure no other notifications except Subscribes is chosen.** And be sure to hit 'Save' at the bottom:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d1cea2a2c7d3a5cd38e95c1/file-uJcloxDQMy.jpg)

And you're all set! You can move on to testing your integration.

### Important Note for setting up multiple deadlines:

There's only space for one Callback URL in GetResponse. Normally DF would create a new Webhook for each Deadline Funnel campaign, but we've set it up so that it adds the information for the new integration onto the original Webhook. This means that each time you create a new integration for a new campaign, you'll need to grab the Webhook URL and re-paste it in the Callback section of GetResponse.

### Test your integration

To test that your integration is working you'll need to add a subscriber to your list, then navigate back to Deadline Funnel and go into the Event Tracking tab in the left hand menu. Verify that the subscriber's email has been added there, and you're good to go!

### Important Note about Email Links

For the API integration to work you MUST use the Deadline Funnel [email links](http://documentation.deadlinefunnel.com/article/16-expiring-links) in any of your emails that link to a sales page with a countdown timer, or that link to a page in your funnel that links to another page with your countdown timer.

In other words, the API integration requires that your subscribers click one of the Deadline Funnel email links before they reach a page with a countdown. This is necessary in order to make sure each subscriber is assigned the correct deadline.

If you have any questions, please let us know at [help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com)

