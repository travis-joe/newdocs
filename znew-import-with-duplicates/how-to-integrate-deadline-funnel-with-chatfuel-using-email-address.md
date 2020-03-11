# How to Integrate Deadline Funnel with Chatfuel using Email Address

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5af495ca0428631126f1ece3/file-h9JlJm1bqM.png)

## Overview

Chatfuel is an app for creating Facebook Messenger bots to use in your ads and marketing.

With Deadline Funnel and Chatfuel, you can add authentic deadlines to your automated sequences in Chatfuel. After someone subscribes to your chat sequence you can trigger a Deadline Funnel campaign and give your lead a deadline to take advantage of your special offer.

If you're unfamiliar with chatbots, here's a guide on [Messenger Marketing and Facebook Chatbots](https://blog.manychat.com/ultimate-guide-messenger-%20marketing-and-facebook-chatbots/) that should help.

In order to integrate Deadline Funnel with Chatfuel you will need:

* An active [Deadline Funnel account](https://deadlinefunnel.com/)
* A Deadline Funnel campaign created using a webhook trigger. Be sure to select Chatfuel as the email service provider.
* A [Chatfuel account](https://chatfuel.com/)
* A Chatfuel sequence

This tutorial also assumes that you already have a Deadline Funnel campaign created and that you will be triggering the campaign in Chatfuel and then collecting the email address of the user in Chatfuel. If you're not going to be asking for their email address before triggering the deadline, [please use this guide instead.](https://documentation.deadlinefunnel.com/article/552-how-%20to-integrate-deadline-funnel-with-chatfuel)

## How to integrate Chatfuel with Deadline Funnel via API:

1. Navigate to 'API Integrations'. Click 'Add New Integration' and then select Chatfuel: ![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b575a2e0428631d7a8941bd/file-MxpZgBai61.png)
2. Copy your Deadline Funnel webhook URL for Chatfuel:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b575a432c7d3a03f89ceee0/file-0vdffod7OE.png)

## How to Integrate Deadline Funnel with Chatfuel:

**Note: You should already have a card set up to collect a user's Email Address at the beginning of the sequence.**

1. In your Chatfuel sequence, add a 'JSON API' plugin to the sequence: ![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5af4b5902c7d3a3f981f7805/file-8BTCyATJMn.png)
2. Select 1\) 'Post' for the type and 2\) paste your Deadline Funnel Webhook URL into the box provided: ![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5af4b6630428631126f1ee0c/file-iVPjrRg80K.png)
3. In the 'User Attributes' box choose 'Email' to capture the user's email address:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5af9fd24042863158411c17d/file-uG0IgYGiXO.png)

1. Click 'Test this Chatbot':

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5af9fd93042863158411c185/file-mcToeuA3Zy.png)

**Note:** Make sure to open up the messenger app and send a test email back to Chatfuel.

5

Confirm the Email gets sent from Chatfuel to Deadline Funnel by checking under Event Tracking in the left hand menu of the Deadline Funnel admin:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5afafe1b2c7d3a640ed6db60/file-EZk8npaQdF.png)

### Add email links to your Chatfuel sequence:

In the Email Setup section of your Deadline Funnel campaign, copy your Deadline Funnel email link:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5af4b7de2c7d3a3f981f781c/file-c1Ar6EbibW.png)

In the special offer section of your Chatfuel sequence, paste your Deadline Funnel email link and then add to the end:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5afb06742c7d3a640ed6dbe2/file-qvwfplIQUU.png)

**Important Note:** Anywhere in Chatfuel that you're linking to your sales page, you'll need to use the email links provided by Deadline Funnel and add:

to the end of the link \(instead of directly linking to your sales page\).

If you have any questions while setting up this integration, please contact us in chat \(blue icon, bottom right corner of the screen\) and we'll be happy to help.

If you have any questions, please let us know at help@deadlinefunnel.com.

