# How to Integrate Deadline Funnel and Shopify

## Introduction

Deadline Funnel can help boost your sales for your marketing campaigns in Shopify! 😎

**Important notes:**

* The direct integration with Shopify outlined in this guide is a beta integration
* It is available to Deadline Funnel customers on the [Pro plan or higher](https://deadlinefunnel.com/pricing)
* This integration is currently available for customers using ActiveCampaign or ConvertKit 
* We will be adding Shopify support for more email platforms very soon!
* If you don't have access to this Shopify integration yet, please [refer to this guide](https://documentation.deadlinefunnel.com/article/437-how-to-add-a-countdown-to-shopify) for how to add Deadline Funnel to a Shopify page

**How it works:**

* Set up an automation in ActiveCampaign or ConvertKit that starts a 3-day deadline for that subscriber.
* Deadline Funnel will create a unique discount code in Shopify for that subscriber, and store that discount code in the subscriber record in ActiveCampaign or ConvertKit.
* Once the deadline has expired, the subscriber will no longer be able to use that discount code.

We're here to help! Contact us on live chat \(bottom right corner of the screen\) Monday - Friday, 8am-5pm ET. Or you can shoot us an email any time at help@deadlinefunnel.com. :\)

## Add the Deadline Funnel tracking code to Shopify

1. In Shopify, go to **Online Store &gt;&gt; Themes:**

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e30380104286364bc947b2d/file-1zacxVPhB5.png)

2. Click **Actions &gt;&gt;** **Edit code:**

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5bc0fbdb042863158cc75dc5/file-oCbLsQUlsU.png)

3. Select **theme.liquid:**

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e303a5a04286364bc947b60/file-KecbhVxEr0.png)

4. Copy the tracking code from your Deadline Funnel account:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e30391b2c7d3a7e9ae6d4ec/file-hxZKfwY4C2.png)

5. Paste the Deadline Funnel tracking code into theme.liquid right before the closing &lt;/head&gt; tag:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5bc0ff3a2c7d3a04dd5b9c7e/file-zP1PwteG4p.png)

6. Click **Save:**

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5bc0ff62042863158cc75dfa/file-Z27hQ3PJg8.png)

## Create a new Deadline Funnel campaign

1. Create a new campaign, and select your email platform \(currently only AcitveCampaign and ConvertKit are supported\) and select Shopify as your landing page builder:

![](https://paper-%20attachments.dropbox.com/s_0331A8D4D8BB1DA8DA5DF792EAC3AFC72E962B2AFD06158A53469AB5347A163A_1573165933867_Shopify-%20Create-A-Campaign-1.png)

2. Select the **Shopify** blueprint:

![](https://paper-%20attachments.dropbox.com/s_0331A8D4D8BB1DA8DA5DF792EAC3AFC72E962B2AFD06158A53469AB5347A163A_1573166072409_Shopify-%20Create-A-Campaign-2.png)

3. Add your deadline settings:

![](https://paper-%20attachments.dropbox.com/s_0331A8D4D8BB1DA8DA5DF792EAC3AFC72E962B2AFD06158A53469AB5347A163A_1573166127514_Shopify-%20Create-A-Campaign-3.png)

4. Then you'll be redirected to the **Quick Start Guide.** Click on **Start Setup** under **Integrate With Shopify:**

![](https://paper-%20attachments.dropbox.com/s_0331A8D4D8BB1DA8DA5DF792EAC3AFC72E962B2AFD06158A53469AB5347A163A_1573166167398_Shopify-%20QSG.png)

## Integrate with Shopify

1. Enter your **shop URL** \(i.e. _store-name.myshopify.com_ \) and click **Connect to Shopify:**

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5e302f262c7d3a7e9ae6d439/file-2mdPlFx4lj.png)

2. Select your **discount type** , **discount amount** , and **products** that you will be integrating with this campaign:

![](https://paper-%20attachments.dropbox.com/s_0331A8D4D8BB1DA8DA5DF792EAC3AFC72E962B2AFD06158A53469AB5347A163A_1573166291834_Shopify-%20Integration-1.png)

## Integrate with ActiveCampaign or ConvertKit

Start by following the steps in the ActiveCampaign or ConvertKit guides to integrate your email platform with Deadline Funnel:

* [ConvertKit](https://documentation.deadlinefunnel.com/article/391-how-to-integrate-deadline-funnel-with-convertkit-api)
* [ActiveCampaign](https://documentation.deadlinefunnel.com/article/244-how-to-integrate-deadline-funnel-with-activecampaign-api)

When using the Shopify integration, you’ll notice there’s an additional step for selecting a custom field that will store the unique Shopify discount code for each subscriber:

![](https://paper-%20attachments.dropbox.com/s_0331A8D4D8BB1DA8DA5DF792EAC3AFC72E962B2AFD06158A53469AB5347A163A_1576098746090_df-%20shopify-coupon.png)

Once a subscriber goes through the Deadline Funnel webhook in your ActiveCampaign or ConvertKit automation, a discount code will be automatically generated in Shopify and will only be valid for that subscriber for the duration of their deadline:

![](https://paper-%20attachments.dropbox.com/s_0331A8D4D8BB1DA8DA5DF792EAC3AFC72E962B2AFD06158A53469AB5347A163A_1576098807524_shopify-%20discount.png)

That subscriber's unique discount code will also be added to a custom field in ActiveCampaign or ConvertKit:

![](https://paper-%20attachments.dropbox.com/s_0331A8D4D8BB1DA8DA5DF792EAC3AFC72E962B2AFD06158A53469AB5347A163A_1576098793958_shopify-%20coupon-ac.png)

You can then use this custom field to dynamically display the subscriber’s discount code in your emails, as they’ll need to use the code when checking out on your page.

Deadline Funnel will automatically remove expired discount codes from your Shopify store.

## Funnel Steps

When you set up the Shopify integration, your Shopify product page will automatically be added to your Deadline Funnel Funnel Steps:

![](https://paper-%20attachments.dropbox.com/s_0331A8D4D8BB1DA8DA5DF792EAC3AFC72E962B2AFD06158A53469AB5347A163A_1573685584179_Shopify-%20Funnel-Steps.png)

It’s very important that your Shopify funnel steps are created through the integration and not manually, in order for everything to work. As long as the funnel step is created through the Shopify integration, the floating bar will only be visible for subscribers in your ActiveCampaign or ConvertKit sequence who have clicked the Deadline Funnel email link to access your Shopify product page.

## Email Links

For this integration to work you must use the Deadline Funnel [email links](https://documentation.deadlinefunnel.com/article/16-expiring-links) in any of your emails that link to a sales page with a countdown timer, or that link to a page in your funnel that links to another page with your countdown timer.

In other words, the API integration requires that your subscribers click one of the Deadline Funnel email links before they reach a page with a countdown. This is necessary in order to make sure each subscriber is assigned the correct deadline.

## Conclusion

Once you have all these pieces in place, you’re all set! If you have any questions about the process, feel free to reach out to us in chat or shoot us an email at help@deadlinefunnel.com

