The API integration with Infusionsoft is the easiest and most flexible way to
integrate Deadline Funnel with your Infusionsoft account.

**Important** : You will need to complete the setup of your first evergreen
campaign before you will see the API integrations link in the left nav.

**Note: Make sure you are logged into your Infusionsoft Account before
beginning.**

##  **Video Tutorial:**

![](https://fast.wistia.com/embed/medias/vudcwlgjdo/swatch)

1\.  Click on API Integrations and then click 'Add a New Integration' and select Infusionsoft 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5bd9ba7e2c7d3a01757a9ed0/file-JOd3hEZFOg.png)


2\. Click 'Allow' on the next page: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5a7e10480428634376d0008c/file-GIT5qxWcD4.png)


3\. On the next screen you'll need to select the group/tag 'Custom Fields'. Then you'll need to create a Custom Field - 
     We call this the 'deadline text' field, and it's just a field in Infusionsoft that stores each contact's unique deadline. 
     The good news is that you can create that field from Deadline Funnel while you're setting up the integration. 
     Go ahead and name it 'deadlinetext' if you're not sure what to call it. You can always change it later: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b4cbb9c2c7d3a03f89c9d34/file-4YVZryipZZ.png)

(If you don't see Custom Fields in the form group drop-down it's likely
because you haven't created any custom fields in InfusionSoft yet. In this
case, please create your custom field in your Infusionsoft account and then
integrate it with Deadline Funnel.)


4\. Copy your Deadline Funnel webhook: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b4cbc802c7d3a03f89c9d44/file-LoHZCKGyAe.png)


5\. Go into your campaign sequence in Infusionsoft and add "Send HTTP Post" at the point in the sequence where you want the deadline to begin. 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d0b7ec52c7d3a6b51c6a891/file-8RG6OwToZo.jpg)


6\. Double-click on 'Send HTTP Post' and 1) paste your Deadline Funnel webhook into the 'Post URL' box, 2) remove the Name/Value Pair, then 3) slide 'Draft' to 'Ready': 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5a96ee442c7d3a754951330e/file-yUrGDubZbw.png)

Make sure to publish your campaign. Now the deadline will begin for each
contact as soon as they reach the HTTP Post in your automation

## Testing the API Integration:

If you haven't run a test yet, please log in to Infusionsoft and add a
subscriber to your automation/sequence/list so that the Deadline Funnel
webhook gets triggered.

You can also wait for the webhook to happen, and then check under Event
Tracking in Deadline Funnel to confirm the email address was received by
Deadline Funnel.

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

If you have any questions, please let us know at
[help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com).

