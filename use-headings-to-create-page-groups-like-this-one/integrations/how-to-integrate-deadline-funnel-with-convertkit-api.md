# How to Integrate Deadline Funnel with ConvertKit \(API\)

The API integration with ConvertKit is the easiest and most flexible way to integrate Deadline Funnel with your ConvertKit account.

**Important** : You will need to complete the setup of your first evergreen campaign before you will see the API integrations link in the left nav.

## Video Tutorial:

## Integrate Deadline Funnel with your ConvertKit account:

1. Click on API Integrations in the left menu. ![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b4e064d2c7d3a03f89caf39/file-%20YqIQz3YyF0.png)

2. To complete the integration, you will need your 1\) API Key and 2\) API Secret from your ConvertKit account. Navigate in ConvertKit to Account Settings:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b6c71762c7d3a03f89d85c3/file-%20BjwP3qljIJ.png)

3. Copy and paste the corresponding keys into Deadline Funnel, then click 'Connect ConvertKit':

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b4e0a062c7d3a03f89caf66/file-4ZdJm6QkBS.png)

## Set Up the Webhook for ConvertKit:

1. On the next screen you'll need to select an existing tag in your ConvertKit account, or create a new tag by simply typing into the drop-down field we have provided. This tag will be used to trigger the deadline:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5cfa8d0504286333a2645201/file-%20fYvqPgLuLj.jpg)

2. Then you will select the custom field that stores each lead's unique deadline. You can select a custom field you already have or create a new field by typing directly into the box. Go ahead and name it "deadlinetext" if you're not sure what to call it, you can always change it later. Then click 'Create New Webhook':

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5cfa8d2204286333a2645204/file-%20CZO33MhNCB.jpg)

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5cfa8d3d04286333a2645205/file-%20ZCNu7IWZhc.jpg)

3. Now if you click 'View Rule in ConvertKit' you will see your new rule in ConvertKit that will trigger your deadline when the tag you selected is applied:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b4e0c812c7d3a03f89caf8b/file-%20CL2Fo6Qgld.png)This will create a rule in ConvertKit that will trigger the webhook when the tag is applied to a subscriber. Now you just need to set up a rule in ConvertKit that will add the tag to a subscriber based on various actions \(ie. they enter a sequence, submit a form, etc.\)

## **Set up a rule in ConvertKit:**

1. Navigate to Automations and select 'Rules':

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/59cd3418042863033a1d36ba/file-%20Swf6BjGcbV.png)

2. Click '+ Add Rule':

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/59cd344a042863033a1d36bd/file-%20uNASEtMAxR.png)

3. In this example, we selected 'Subscribes to a form' as the trigger, selecting the correct form, and selected 'Add tag' as the action, selecting the tag that will trigger Deadline Funnel and clicked 'Save Rule':

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/59cd3525042863033a1d36c5/file-%20RUB4m0qn4I.png)

You have a few options for how to trigger the tag, including triggering when someone is added to a sequence or when another tag is added, but in this example we used "Subscribes to a form". So now once someone subscribes to that form, ConvertKit will apply the tag, and the tag will tell Deadline Funnel to start the countdown.

**Note** : If you want to integrate several different funnels with ConvertKit, you will simply repeat these steps and create a new API integration and tag for each countdown, as well as separate automations. This creates a system where Tag A triggers Campaign A, while Tag B triggers Campaign B.

## Additional Feature: Bulk Actions

**Note** : If you want to add several people to a Deadline Funnel campaign you can now do that using ConvertKit's Bulk Actions.

1. Navigate to Subscribers, select the subscriber\(s\) you want to tag and click 'Bulk Actions':

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b6c725f2c7d3a03f89d85d3/file-%20wgvuegwj8P.png)

2. Then click 'Tag':

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b6c72992c7d3a03f89d85d6/file-%20QQ5J9RCDJW.png)

3. Select the tag that triggers your Deadline Funnel campaign and click 'Save':

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b6c731e0428631d7a89d0ee/file-%20Fe9sd3icrT.png)

You can tag as many subscribers as you want to trigger.

4. After the ConvertKit system finishes adding the tags, you can return to 'Event Tracking' and you will see that the email you tagged in ConvertKit is being tracked by Deadline Funnel.

## Test your integration:

## Important Note about Email Links

For the API integration to work you MUST use the Deadline Funnel [email links](http://documentation.deadlinefunnel.com/article/16-expiring-links) in any of your emails that link to a sales page with a countdown timer, or that link to a page in your funnel that links to another page with your countdown timer.

In other words, the API integration requires that your subscribers click one of the Deadline Funnel email links before they reach a page with a countdown. This is necessary in order to make sure each subscriber is assigned the correct deadline.

If you have any questions, send us a message in chat or email us at [help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com).

