# How do I add the Facebook Pixel to my survey?

## Introduction

Integrating the Facebook Pixel with your survey gives you the ability to create custom audiences in your Facebook ads based on:

* People who visited the survey page
* Leads who completed the survey and chose a specific Question/Answer combination \(i.e. answered "I need more leads" to "What are you struggling with the most?"\)
* Leads who completed the survey and had a specific score \(or score range\) at the end of the survey

This article shows how to set up Facebook Pixel code and standard events in Survey Funnel.

Once you've finished the Survey Funnel setup, [click here](https://www.facebook.com/business/help/666509013483225) to learn how to use those events to create Custom Audiences in Facebook.

If you have any questions about integrating the Facebook Pixel with your survey, please send us a chat message when you're logged in to Survey Funnel or shoot us an email at [help@surveyfunnel.io](mailto:mailto:help@surveyfunnel.io). We're here Monday

* Friday, 9am-5pm EST, and are happy to help.

Before we get started, let's review the two types of Facebook Pixel code you can use with Survey Funnel.

**1. Your Facebook Pixel base code**

This is going to be the main Facebook pixel code [from the Ads Manager](https://www.facebook.com/ads/manager/pixel/facebook_pixel), which looks like this:

  
    !function\(f,b,e,v,n,t,s\){if\(f.fbq\)return;n=f.fbq=function\(\){n.callMethod?  
    n.callMethod.apply\(n,arguments\):n.queue.push\(arguments\)};if\(!f.\_fbq\)f.\_fbq=n;  
    n.push=n;n.loaded=!0;n.version='2.0';n.queue=\[\];t=b.createElement\(e\);t.async=!0;  
    t.src=v;s=b.getElementsByTagName\(e\)\[0\];s.parentNode.insertBefore\(t,s\)}\(window,  
    document,'script','//connect.facebook.net/en\_US/fbevents.js'\);  
    // Insert Your Facebook Pixel ID below.  
    fbq\('init', 'FB\_PIXEL\_ID'\);  
    fbq\('track', 'PageView'\);  
    ![](https://www.facebook.com/tr?id=FB_PIXEL_ID&ev=PageView&noscript=1) \*\*2\. Your standard event code\*\* Standard event code is another layer on top of the Facebook Pixel base code and allows you to send information about specific events to Facebook. You can then use those events to build custom audiences. Here's an example of event code you could use in your survey:  
    fbq\('track', 'Lead', {  
      content\_name: 'Completed Survey XYZ',  
      content\_category: 'Needs More Leads'  
     }\);  
    

For more information on custom events, [click here to go to the Facebook Pixel Implementation Guide](https://www.facebook.com/business/help/952192354843755?helpref=faq_content#addeventcode).

## Set up the Facebook Pixel to track people who take your survey

The first step in integrating the Facebook Pixel is tracking people who visit your survey page. Please note that if you are embedding the survey on your own page, then if you have the main Facebook Pixel already added to your page you can skip this section and move to the next section: **Set up custom events for leads who complete the survey.**

This can be useful for creating a custom ad audience for retargeting to people who visited the page but maybe didn't complete the survey.

1

```text
 To start, go to the Customize tab of your survey, and select General Settings: 
```

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/592f33a00428634b4a33960e/file-%20YoZdtd6VOg.png)

2

```text
 Then add your Facebook pixel code to the Tracking Code section: 
```

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/592f33ed0428634b4a339611/file-%20CFqXCObzXK.png)

Note that when you're adding the Facebook code to this section, you must add the Facebook Pixel base code; the standard event code is optional but we do recommend using it as well.

Here's an example of standard event code you could add directly below your Facebook Pixel base code:

  
    fbq\('track', 'ViewContent', {  
      content\_name: 'Visited Survey XYZ',  
     }\);  
    

In the standard event code above, you can change "Visited Survey XYZ" to reflect the name of your survey and how you want to organize events in your Facebook ads account.

Using both the Facebook Pixel base code and the standard event code above in this area will allow you to create a custom audience in Facebook of everyone who visited the survey page.

## Set up custom events for leads who complete the survey

Finally, we'll set up custom event code for people who complete the survey and match a specific condition.

In this example, we want to create one event/custom audience for people who choose "The thing I need most is more traffic," and then a different event/custom audience for leads who choose "The thing I need most is more conversions:"

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/59024f3a2c7d3a057f88a078/file-%20fa1oS20Ds3.jpg)

1

```text
 The first step is to go to the 'Rules' tab and add a new rule. The rest of the steps outlined below will be done for each of the two rules we create. 
```

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/592f371c0428634b4a33962b/file-%20cFyQHPNoUg.png)

As you can see, we've set the condition to "selects this answer: The thing I need most is more TRAFFIC." So this rule will be triggered after the survey is completed, for anyone who selects that specific answer.

2

```text
 Next, click on "Add custom tracking code" under "Add a new action": 
```

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/592f36fe2c7d3a074e8af6aa/file-%20lC6kt0ZjzF.png)

Here you'll add your standard event code:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5978e2d32c7d3a73488b6767/file-%20smUazexsrX.jpg)

Whenever someone completes the survey and answers "The thing I need the most is more traffic," Facebook will fire the standard event "Needs More Traffic."

You can then [use that event to create a custom audience in Facebook ads](https://www.facebook.com/business/help/666509013483225) just targeting that segment of people.

Note that in this example, we're setting up two rules \(one for each answer choice\) and for each rule we need to follow the steps outlined above.

You could also create rules based on score conditions, or choose to create a catch-all rule that pixels everyone who completes the survey and fires the same standard event.

[Click here to learn how to fire custom events](https://trello.com/c/SBFg0OEy/238-create-whats-this-docs-for-custom-%20answer-events-and-sending-post-data-to-thank-you-page) as people submit each question in the survey.

If you have any questions about this feature, please send us a message in chat.

