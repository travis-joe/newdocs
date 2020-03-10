# How to Integrate Deadline Funnel with MailChimp \(API\)

You can integrate Deadline Funnel with Mailchimp using the API and trigger your countdown based on when someone:

* Subscribes to your list 
* Is added to a group
* Subscribes on a Mailchimp Landing Page

Please note that if you are going to integrate your Deadline Funnel campaign with a group, you need to have that group created in your Mailchimp list **before** you create your API Integration with Deadline Funnel. You can find additional information on Mailchimp groups here: [https://kb.mailchimp.com/lists/groups/getting-started-with-groups](https://kb.mailchimp.com/lists/groups/getting-started-with-groups)

## Video Tutorial:

![](https://fast.wistia.com/embed/medias/1vfqfnncct/swatch)

## Integrate Deadline Funnel with Mailchimp

**Important** : You will need to complete the setup of your first evergreen campaign before you will see the API integrations link in the left nav.

1. In your Deadline Funnel dashboard, click on 'API Integrations' in the left hand menu and scroll down to click 'Click here to create a brand new API integration', then select MailChimp from the next screen:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b48d6dc2c7d3a099f2e876e/file-5SYoM4nVm8.png)

2. You will need to add your MailChimp Username and Account ID on the next screen. To get your API Key, go to your Mailchimp account, navigate to Account &gt; Extras &gt; API Keys. Click on 'Create A Key', copy the new API Key and paste it into the 'MailChimp API key' box in Deadline Funnel:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/59c18db32c7d3a73488cfc9a/file-4VuyNdkQW0.png)

3. Then Copy your MailChimp account username ad paste it into the 'MailChimp Username' box in Deadline Funnel and click 'Connect MailChimp':

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b48d8e32c7d3a099f2e8789/file-%20nU6JdBd7Kn.png)

## Setting up your Deadline to Begin when Someone Subscribes to a List:

1. Choose \(1\) 'List' from the dropdown that asks when to start tracking subscribers, \(2\) select your preferred list, and \(3\), select the custom field to hold the lead's deadline:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b48e5430428630abc0c0c67/file-%20WOmSyWDs6G.png)

2. Copy the Deadline Funnel webhook as you need this to set up your Webhook in your MailChimp account.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b48e5882c7d3a099f2e8802/file-%20dYgZxEZkY1.png)

**Note:** MailChimp changed the name of this custom field from 'deadlinetext' to ' **MMERGE5** '. This is normal and will not affect the webhook performance.

3. In your MailChimp account, navigate to the list you want to integrate with. Go to Settings &gt; Webhooks and click Create New Webhook:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/59c18ff32c7d3a73488cfcaa/file-4ASDTBjknn.png)

4. Paste your Webhook URL into the Callback URL box, then check the box to send updates for 'Subscribes'. Be sure to check all 3 boxes in the 'Only send updates when a change is made...' section. Click 'Save':

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/59c190ad2c7d3a73488cfcad/file-%20jBxxYZ5y4r.png)

And you're all set! You can move on to testing your integration.

## Setting Up Your Deadline to Begin When Someone is Added to a Group:

MailChimp's "groups" feature is a great way to trigger a series-based deadline in Deadline Funnel. While normally you could simply trigger the deadlines once a user subscribes to your list using our integration with MailChimp's API as described in this article, this method allows you to trigger the deadline by adding users to a group at a _certain interval_ in your email sequence.

In this example we are using MailChimp's "Onboarding series", which is an automated series with multiple email steps that allows you to narrow down where you want the subscribers to be added to the group **.**

1. Start by creating a new group inside of MailChimp. This group's function is to trigger a deadline at a certain interval. It has no other functions, so we will make it an invisible group that people cannot add themselves to from any of our web forms:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d1cc53f2c7d3a5cd38e9144/file-%20ZrDLAQRHBf.jpg) 2. After this is done, navigate to the point in your MailChimp series that you want your subscribers to be added to the group. Keep in mind that when they are added to this group, that will trigger their deadline in Deadline Funnel. So in this example, we want to time it so that the subscribers get added to the group after the fourth email is sent out:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d1cc4e22c7d3a5cd38e9137/file-u9RhY7TY23.jpg)

3. Select 'Post-send action' and use the 'Add to group' option, then select the group that you just created. In our example, that group is called TriggerGroup:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d1cc6432c7d3a5cd38e9166/file-S9Ocl2KKuE.jpg)

4. Choose \(1\) 'Group' from the dropdown that asks when to start tracking subscribers, \(2\) select your preferred list, \(3\) select the group/tag, and \(4\), select the custom field to hold the lead's deadline::

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b48e73f2c7d3a099f2e8815/file-%20uG71IdkB3W.png)

5. Copy the Deadline Funnel webhook as you need this to set up your Webhook in your MailChimp account:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b48e5882c7d3a099f2e8802/file-%20dYgZxEZkY1.png)

**Note:** MailChimp changed the name of my custom field from 'groupdeadline' to **'MMERGE5'**. This is normal and will not affect the webhook performance

6. In your MailChimp account, navigate to the list you want to integrate with, then go to Settings &gt; Webhooks and click 'Create New Webhook:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/59c18ff32c7d3a73488cfcaa/file-4ASDTBjknn.png)

7. Paste your webhook URL into the 'Callback URL' box. Check the box to send updates for 'subscribes and 'profile updates', then uncheck everything else. And be sure to check the second and third boxes in the 'Only send updates when a change is made...' section and click 'Save'

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/59cbc903042863033a1d2bfd/file-%20kIVF7RBvgs.png)

## Setting Up Your Deadline to Begin when Someone Subscribes on a Mailchimp

Landing Page:

You can integrate Deadline Funnel with a Mailchimp landing page by setting up your API integration and then connecting your landing page to the correct list.

When you 1\) create your Landing Page 2\) select the list you integrated with Deadline Funnel from the drop-down:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5bc8b698042863158cc7983f/file-%20QS3YEnMBjY.png)

### Test your integration

To test that your integration is working you'll need to add a subscriber to your list \(and group, if appropriate\), then navigate back to Deadline Funnel and click the green 'Test' button under Step 3. You can also verify that it's working by checking for the subscriber's email under Event Tracking in the left hand menu.

## Important Note about Email Links

For the API integration to work you MUST use the Deadline Funnel [email links](http://documentation.deadlinefunnel.com/article/16-expiring-links) in any of your emails that link to a sales page with a countdown timer, or that link to a page in your funnel that links to another page with your countdown timer.

In other words, the API integration requires that your subscribers click one of the Deadline Funnel email links before they reach a page with a countdown. This is necessary in order to make sure each subscriber is assigned the correct deadline.

**Please Note: Sometimes when you're adding a Deadline Funnel Email Link to a Mailchimp email, you will see the following message:**

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b9fd3c10428631d7a8b3c84/file-9ghpgUYSoe.png)

**You can disregard this message and hit 'Insert' anyway. The links should still work as expected.**    


If you have any questions, please let us know at [help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com)

