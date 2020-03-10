# How to Integrate Deadline Funnel with Klick-Tipp \(API\)

The API integration with Klick-Tipp is the easiest and most flexible way to integrate Deadline Funnel with your Klick-Tipp account.

**Important** : You will need to complete the setup of your first evergreen campaign before you will see the API integrations link in the left nav.

At the top of the screen you can see which Deadline Funnel campaign you're currently editing. Each Deadline Funnel campaign gets its own API integration.

1. Click on API integrations in the left menu, then click 'Add New Integration' and select Klick-Tipp.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b575c100428631d7a8941d6/file-%20HMVU9Qj9Vj.png)

3. Copy your Deadline Funnel Webhook:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b575c1c0428631d7a8941d8/file-%20qd9p0qAvW8.png)

4. Add your Deadline Funnel webhook to your Outbound Events in Klick-Tipp by navigating to automation &gt;&gt; New Outbound:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/59975b0c2c7d3a73488c20dc/file-8CMzMKIxoi.png)

5. Give your new outbound event a name, select your filter, and paste the Deadline Funnel Webhook URL into the 'Activation URL' box and click 'New Outbound Event':

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/59975bf3042863033a1c1dc2/file-%20opmfVRJdkV.png)

Now the deadline will begin for each contact as soon as they reach that webhook in your automation.

You can test by adding a contact to your automation, waiting for the webhook to happen, and then check under Event Tracking in Deadline Funnel to confirm their email address was received by Deadline Funnel.

## Important Note about Email Links

For the API integration to work you MUST use the Deadline Funnel [email links](http://documentation.deadlinefunnel.com/article/16-expiring-links) in any of your emails that link to a sales page with a countdown timer, or that link to a page in your funnel that links to another page with your countdown timer.

In other words, the API integration requires that your subscribers click one of the Deadline Funnel email links before they reach a page with a countdown. This is necessary in order to make sure each subscriber is assigned the correct deadline.

If you have any questions, send us a message in chat or email us at [help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com).

