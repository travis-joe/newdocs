# How to Integrate Deadline Funnel with ManyChat \(using email address\)

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5a84a7b22c7d3a4a4199204c/file-ymnnuXwsWn.png)

## Why Deadline Funnel + ManyChat?

ManyChat is one of the most popular apps for creating Facebook Messenger bots that you can use in your ads and marketing.

With Deadline Funnel + ManyChat, you can add authentic deadlines to your automated sequences in ManyChat - so that after someone subscribes to your ManyChat sequence you can let them know they have a specific number of days or hours to take advantage of your special offer.

Still no clue what we're talking about? That's okay! Here's a great guide on [Messenger Marketing and Facebook Chatbots](https://blog.manychat.com/ultimate-guide-messenger-marketing-and-%20facebook-chatbots/) that might help. :\)

## A few notes before we get started...

In order to follow along, you will need the following:

* An active [Deadline Funnel account](https://deadlinefunnel.com/)
* A [ManyChat Pro account](https://manychat.com/) \(yes, you do need to be on a paid ManyChat plan in order for this to work!\)

This guide also assumes that you already have a Deadline Funnel campaign created and that you will be integrating this campaign with a ManyChat sequence and your email sequence at the same time. If you are just going to be sending messages from ManyChat, [please use this guide instead.](https://documentation.deadlinefunnel.com/article/525-how-to-%20integrate-deadline-funnel-with-manychat)

And if you have any questions along the way please contact us in chat \(blue icon, bottom right corner of the screen\) and we'd love to help!

### Integrating Deadline Funnel with ManyChat

1. Navigate to API Integrations in the left hand menu of Deadline Funnel and click 'Or click here to create a brand new API', then select ManyChat from our list of providers:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b5757290428631d7a894195/file-7wTHD9CfYT.png)

1. On the next screen it's going to ask you for your API Key from ManyChat:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5bd0b53304286356f0a5060d/file-PqC4aZ7G7x.png)

1. You can find that under Settings &gt; API in your ManyChat account:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5bd0b54c2c7d3a01757a5b0a/file-2KwJZoVtl9.png)

4 Once you're connected, you're going to select the Custom Field in ManyChat that will store each lead's unique deadline. You will need to already have this Custom Field created in ManyChat so that you can select it from the dropdown:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5bd0b56904286356f0a5060f/file-ojcw3uQJWe.png)

5 Now copy the Webhook URL that populates below that:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5bd0b5f02c7d3a01757a5b16/file-ATFV3Rln1R.png)

1. Go into ManyChat and navigate to your sequence and click 'Edit Message', then select +Dynamic from the options at the bottom of the screen and move it to the top of the sequence: ![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5afefa3f2c7d3a2f9011a47d/file-YxZr2hLiJr.png) 7. Then paste the Deadline Funnel webhook there:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5afefa4e2c7d3a2f9011a47e/file-PTnuEcrN4d.png)

1. Next you'll need to navigate to Body and click on Add Full Subscriber Data \(this allows Deadline Funnel to grab the information it needs from ManyChat to trigger the deadline\) and hit Save:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5afefab32c7d3a2f9011a481/file-L1gBvhi1GI.png)

1. Next you'll need to navigate back to the Email Setup tab in the Deadline Funnel admin and copy your special Email Link:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5af4b7de2c7d3a3f981f781c/file-c1Ar6EbibW.png)

1. Then go back into your ManyChat and paste the link wherever you are sending people to your special offer page in the sequence. It's important that you remove everything after the 'em=' and replace it with the 'Email' placeholder ![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b0729902c7d3a2f9011e527/file-hxGLtLGi5T.png)

## Quick recap

1. To integrate Deadline Funnel + ManyChat, you need to add the webhook to the top of your ManyChat sequence so that it can start a new deadline for each user as they interact with your sequence.
2. Then you need to copy your [email link](http://documentation.deadlinefunnel.com/article/16-expiring-links) from Deadline Funnel \(i.e. [http://dfl1.us/go/618/anGekY/1516738987?em=~Contact.Email~](http://dfl1.us/go/618/anGekY/1516738987?em=~Contact.Email~)\)...
3. Remove everything after the 'em=' so it looks like this: [http://dfl1.us/go/618/anGekY/1516738987?em=](http://dfl1.us/go/618/anGekY/1516738987?em=)
4. Paste it into your ManyChat button and then add the "Email" placeholder

### Test

Add yourself to the sequence in ManyChat, and then go into Event Tracking in the Deadline Funnel admin to verify that the email has been added there.

Now, whenever someone enters your sequence in ManyChat, their deadline will begin, and when they click on the Deadline Funnel email links in your ManyChat sequence, we will be able to make sure their tracking continues to be accurate

* even on other devices and networks!

If you have any questions, please let us know at [help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com).

