![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5af495ca0428631126f1ece3/file-h9JlJm1bqM.png)

Note: This article covers how to integrate your Chatfuel sequence with
Deadline Funnel if you are only using Chatfuel to share your special offer
with prospects. If you're wanting to use Chatfuel AND an Email sequence
together, please see [this
article](https://documentation.deadlinefunnel.com/article/553-how-to-
integrate-deadline-funnel-with-chatfuel-using-email-address).

## Overview

Chatfuel is an app for creating Facebook Messenger bots to use in your ads and
marketing.

With Deadline Funnel and Chatfuel, you can add authentic deadlines to your
automated sequences in Chatfuel. After someone subscribes to your chat
sequence you can trigger a Deadline Funnel campaign and give your lead a
deadline to take advantage of your special offer.

If you're unfamiliar with chatbots, here'a guide on  [Messenger Marketing and
Facebook Chatbots](https://blog.manychat.com/ultimate-guide-messenger-
marketing-and-facebook-chatbots/) that should help.

**In order to integrate Deadline Funnel with Chatfuel you will need:**

  * An active [Deadline Funnel account](https://deadlinefunnel.com/)
  * A Deadline Funnel campaign created using a webhook trigger. Be sure to select Chatfuel as the email service provider.
  * A [Chatfuel account](https://chatfuel.com/)
  * A Chatfuel sequence

## How to integrate Chatfuel with Deadline Funnel via API:

1\. Navigate to 'API Integrations' and scroll down to click to 'create a brand new API integration': 
![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5af4b3060428631126f1edf3/file-kWftMM9rlt.png)

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5af4b3120428631126f1edf4/file-nTKhOyWItR.png)

2\. Select Chatfuel: 
![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5af4b3980428631126f1edf7/file-WRwG415ZBY.png)

3\. Click 'Activate Integration': 
![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5af4b3dc2c7d3a3f981f77f7/file-TiFEAN1zpe.png)

4\. Copy your Deadline Funnel webhook URL for Chatfuel: 
![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5af4b4250428631126f1edfb/file-Zb3TdXzOAN.png)

## How to Integrate Deadline Funnel with Chatfuel:

1\. In the screenshot below, you can see that we've set up a "demo" sequence in Chatfuel: 

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5af4abf42c7d3a3f981f77bd/file-uTZ4y5ArcG.png)

2\. In your Chatfuel sequence, add a 'JSON API' plugin to the sequence: 

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5af4b5902c7d3a3f981f7805/file-8BTCyATJMn.png)

3\. Select 1) 'Post' for the type and 2) paste your Deadline Funnel Webhook URL into the box provided: 

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5af4b6630428631126f1ee0c/file-iVPjrRg80K.png)

4\. In the 'User Attributes' box choose 'Messenger ID' to capture the Facebook Messenger ID: 

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5af4b6fe2c7d3a3f981f7814/file-HZQf8GI100.png)

What we're passing to Deadline Funnel is the messenger ID that will enable
Deadline Funnel to track your leads accurately without an email address.

5\. In the Email Setup section of your Deadline Funnel campaign, copy your Deadline Funnel email link: 

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5af4b7de2c7d3a3f981f781c/file-c1Ar6EbibW.png)

6\. In the special offer section of your Chatfuel sequence, paste your Deadline Funnel email link and then add {{messenger user id}}@cf.deadlinefunnel.com to the end: 

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5af4b83b0428631126f1ee26/file-VmhhfPRkBN.png)

7\. Click 'Test this Chatbot': 

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5af9d2f62c7d3a640ed6cfcf/file-1RfJrPpg1h.png)

8\. Confirm the "Messenger ID" gets sent from Chatfuel to Deadline Funnel: 
Check the Event Tracking page in your Deadline Funnel account and make sure
you can see the 'Messenger ID':

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5af9d3a62c7d3a640ed6cfd6/file-SIPiIusHqR.png)

9\. Add email links to your Chatfuel sequence: 
Anywhere in Chatfuel that you're linking to your sales page, you'll need to
use the email links provided by Deadline Funnel and add:

{  {messenger user id }}@cf.deadlinefunnel.com

to the end of the link (instead of directly linking to your sales page).

If you have any questions while setting up this integration, please contact us
in chat (click the blue icon, bottom right corner of the screen) and we'll be
happy to help.

If you have any questions, please let us know at
[help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com).

