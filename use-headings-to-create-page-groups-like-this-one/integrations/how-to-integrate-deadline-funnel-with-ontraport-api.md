This API integration provides the ability to set up Deadline Funnel campaigns
that are triggered when someone gets tagged or clicks a link in addition to
during opt in. This allows you to send an evergreen marketing campaign to
existing Ontraport subscribers and incorporate a Deadline Funnel authentic
evergreen deadline.

You can integrate Deadline Funnel with Ontraport:

  * Using a Rule
  * Using a Sequence
  * Using a Campaign

**Important** : You will need to complete the setup of your first evergreen
campaign before you will see the API integrations link in the left navigation
bar.  Each Deadline Funnel campaign gets its own API integration.

##  Video Tutorial:

## Integrate Ontraport with your Deadline Funnel Account:

1\.  Click API integrations in the left navigation, you will need to add your Ontraport App ID and API Key into the appropriate boxes:: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b49238b0428630abc0c0e58/file-CKbLQLruvA.png)


2\. Log into your Ontraport account and click 'Administration': 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/59553b3f0428637ff8d42d83/file-oBF9BR447K.png)


3\. Under Integrations, click 'Ontraport API Instructions and Key Manager': 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5a81eab60428634376d00b70/file-3L7C4VE46M.png)


4\. Click 'New API Key' from the menu shown here and give your new API key a name, i.e., 'Ontraport Demo key'. Then select the correct User from the DropDown and make sure to select the boxes to turn on Add Contacts, Search Contacts, and Manage Fields as shown here: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/59553b842c7d3a707d7b50cb/file-Sj6vvLZYZw.png)


5\. Click save and it will take you to this screen where you can see your new App ID and API Key: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/59553b9a0428637ff8d42d8a/file-fyMvlMjZ35.png)


6\. Return to Deadline Funnel and paste your 1) Ontraport App ID and 2) API Key into the corresponding boxes in the admin and click 'Connect Ontraport': 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b49252c0428630abc0c0e5f/file-tZE51E1PMn.png)


7\. Select the custom field from the dropdown that you want to use store each lead's deadline. If you want to create a new field, just start typing into the box to create the new custom field.  **Please note: If you create the custom field in Ontraport and then select it in Deadline Funnel (instead of creating it in Deadline Funnel), you will need to create the field under the "Contact Information" tab in the contact record in Ontraport in order for it to work.**

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b4925e70428630abc0c0e64/file-RHW7J7dGDp.png)

####

####

## Option 1: Integrate Deadline Funnel with an Ontraport Rule

1\.  In Ontraport navigate to Contacts > Rules, and click to add a 'New Rule': 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5955482a2c7d3a707d7b5128/file-oW0zT94KRH.png)


2\. Give your new rule a name and select the trigger 'When Contact is added to Sequence': 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/595544a72c7d3a707d7b5110/file-8fVkqYv7JH.png)


3\. Select the correct sequence: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/595547720428637ff8d42df6/file-1g68rFs2sw.png)


4\. Navigate to the 'Actions' section and scroll down to select 'Send to a Webhook': 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d323e6d2c7d3a2ec4bf232f/file-8uNirURvOp.jpg)


5\. You're going to fill these two boxes with the Webhook URL and Post Data Field from Deadline Funnel: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e3049832c7d3a7e9ae6da10/file-43F8FpgZIC.png)

See below for where to find the corresponding fields in Deadline Funnel:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e3048de2c7d3a7e9ae6da03/file-wRubHzoAPu.png)


6\. Click 'Save' and you're ready to test it out. You can test by adding a new contact to your sequence and then check under Event Tracking in Deadline Funnel to confirm their email address was received by Deadline Funnel. 

## Option 2: Integrate Deadline Funnel into an Ontraport Sequence

1\.  Navigate to Contacts > Sequences and click the sequence you want to integrate with Deadline Funnel: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/59554b942c7d3a707d7b513c/file-vQQ8VeQzpW.png)


2\. In the Add a Step bar click 'Rule' and name your rule. Then select 'Send to a Webhook' under Actions and paste in the Webhook URL and Post Data Field from Deadline Funnel: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e3049832c7d3a7e9ae6da10/file-43F8FpgZIC.png)


3\. See below for where to find the corresponding fields in Deadline Funnel: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e3048de2c7d3a7e9ae6da03/file-wRubHzoAPu.png)

Click 'Save' and you're ready to test it out.


4\. You can test by adding a new contact to your sequence and then check under Event Tracking in Deadline Funnel to confirm their email address was received by Deadline Funnel. 

## Option 3: Integrate Deadline Funnel into an Ontraport Campaign

1\.  Navigate to Contacts > Campaigns and click the campaign you want to integrate with Deadline Funnel or create a new campaign: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b05c9352c7d3a2f9011d6f2/file-xOwELoATfY.png)


2\. Click the '+' for What Happens next, click on 'Advanced' and select 'Send a Webhook': 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b05cae02c7d3a2f9011d713/file-5358J8j0NI.png)


3\. Paste your Deadline Funnel 1) webhook and 2) post data into the boxes shown below and 3) give this webhook a name: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e30494504286364bc948043/file-oNae4Sba4B.png)

You can find the Webhook URL and post data here in your API Settings in
Deadline Funnel:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e3048de2c7d3a7e9ae6da03/file-wRubHzoAPu.png)


4\. Click 'Save and Publish' for your campaign and you're ready to test it out. 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b05ceed2c7d3a2f9011d74d/file-DDaGN8XVCA.png)


5\. You can test by adding a new contact to your campaign and then checking under Event Tracking in Deadline Funnel to confirm the email address was received by Deadline Funnel. 

## Important Note about Email Links

For the API integration to work you MUST use the Deadline Funnel [email
links](http://documentation.deadlinefunnel.com/article/16-expiring-links) in
any of your emails that link to a sales page with a countdown timer, or that
link to a page in your funnel that links to another page with your countdown
timer.

In other words, the API integration requires that your subscribers click one
of the Deadline Funnel email links before they reach a page with a countdown.
This is necessary in order to make sure each subscriber is assigned the
correct deadline.

If you have any questions, send us a message in chat or email us at
[help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com).

#### Having trouble figuring out how to sync up your Ontraport sequence with
your deadline? [Here's a helpful
article.](https://documentation.deadlinefunnel.com/article/612-how-to-time-your-ontraport-campaign-with-your-deadline-funnel-campaign)

