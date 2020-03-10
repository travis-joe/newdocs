Our API Integration allows you to create an automation in Drip and start a
lead's Deadline Funnel tracking based on when a webhook is triggered in that
automation.

Each Deadline Funnel campaign gets its own API integration

**Important** :  You will need to complete the setup of your first evergreen
campaign before you will see the API integrations link in the left nav.

## Video Tutorial:

## Set up the integration between Drip and Deadline Funnel:

1\.  Click on API Integrations in the left menu. You will need to add your Drip Account ID and Token ID into the appropriate boxes: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b4915962c7d3a099f2e89ae/file-s3xzcauaTU.png)


2\. To get your Account ID, navigate inside Drip to account settings and scroll down to copy your Account ID and paste it into the Drip Account ID box in Deadline Funnel: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5a6262d80428632faf61fdb7/file-Rv0r8Kkuz5.png)

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5a62633e2c7d3a39e6262f32/file-o61FzwL9sZ.png)


3\. Click on 'User Settings' in your Drip account to get your Token credentials: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5a6261052c7d3a39e6262f21/file-oeBtWC2C8l.png)


4\. Scroll to the bottom to the API Token, and copy the API Token: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5a62622f0428632faf61fdb0/file-NfUlOsdS0C.png)


5\. Paste the API token into the Drip Token ID box in Deadline Funnel, then hit 'Connect Drip': 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b49188c0428630abc0c0e06/file-1uVLIWn5m2.png)


6\. Select the custom field from the dropdown that you want to use store each lead's deadline. If you want to create a new field, just start typing into the box to create the new custom field: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b4919220428630abc0c0e08/file-DjkWkHNmNu.png)

## Copy your webhook for Drip

In the example below, we will set up an automation in Drip that sends the HTTP
post to trigger the Deadline Funnel tracking.

As soon as a contact reaches that portion of the automation, their unique
deadline will begin, and they'll only have a specific amount of time from that
point to access your special offer.  

There are a lot of different variations on this that you can do with Drip and
Deadline Funnel - you can trigger a deadline when someone clicks a link,
completes a campaign, performs a custom event, etc.

Copy the webhook URL from Deadline Funnel:  

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b491ae40428630abc0c0e11/file-xjEk3yUKxp.png)

## **Add the Webhook URL to trigger Deadline Funnel in the Drip
automation/Workflow**

You can either create a new Drip automation or edit an existing one.

1\.  Click the plus icon at the point in your automation where you want the deadline to begin: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5a6265b90428632faf61fdcc/file-n1ALEU9jKc.png)


2\. Then select 'Action' from the list of options: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/59567f2e2c7d3a707d7b58e3/file-zyZ5tsKUID.png)


3\. Select 'Send an HTTP post' from the options given: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5a6266222c7d3a39e6262f53/file-u3oaSDCZr7.png)


4\. Paste the Webhook URL from Deadline Funnel into the 'Endpoint URL' box and click 'Update Action': 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5a6266ae2c7d3a39e6262f5a/file-9Z5OnUfZNr.png)

Now you're all set.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5a62670d0428632faf61fdd6/file-jliP0O8lwa.png)

When each contact reaches the HTTP Post in your automation, their deadline
will begin.

### **Test your integration**

You can test by adding a new contact to your sequence, waiting until the
contact has reached the http post in your automation, and then checking under
Event Tracking in Deadline Funnel to confirm their email address was received
by Deadline Funnel.

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

If you have any questions, please let us know at
[help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com).

