The Pre-Launch feature allows you to control which pages people will see
depending on whether their Deadline Funnel tracking has started yet or not.
This works for fixed-date, evergreen, and hybrid campaigns.

### How to use Pre-Launch with an evergreen or hybrid campaign:

Pre-Launch is a great option when you want to set up a three-part campaign.

1\. Pre-access page people will only have access to before their deadline
starts (i.e. an optin page)

2\. Special offer page that subscribers will only have access to once their DF
tracking starts

3\. After URL that they will get redirected to once their deadline expires

1

     In 'Edit Campaign' navigate to Settings and find the Pre-Launch setting just below where you set the length of the deadline: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5be083592c7d3a01757acea9/file-bgyPIDaAxl.png)

2

     The Pre-Launch URL is going to be the page you want them to see before their deadline has started: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5bf44a052c7d3a31944e2920/file-bduK4IdYKY.png)

3

     For the second URL you'll see a dropdown with all of your Funnel Step URLs. This is going to be the page you want them to be redirected to once their deadline has started: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5bf44a0f2c7d3a31944e2922/file-g5svq9Ikdo.png)

Once you've filled in both boxes, hit 'Save' and you're all set!

### How to use Pre-Launch with a fixed-date campaign:

In a fixed-date campaign, the Pre-Launch feature can be used to show people a
page that you want them to see before the special offer is available.

For example, you can create a fixed-date campaign that has a start date of
January 15 and a deadline of January 31. If someone tries to access your
special offer page before January 31, they will be redirected to your Pre-Launch page.

1

     In 'Edit Campaign' navigate to Settings and find the 'Start date enabled' button. Make sure this is turned on, as it will indicate when the Pre-Launch redirect is active. And hit 'Save' before moving on to the next step: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5be492ca2c7d3a31944dbf73/file-s6pX2I96KS.png)

2

     Then navigate below that to the pre-launch section. Enable the setting and then add your two URLs: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5be0842c04286356f0a571c2/file-ZkPao60sI5.png)

### Advanced: using the same pre-launch URL as your "after deadline" URL

In some cases, you may want to use the same URL as your pre-launch URL and
your "after deadline" URL.

Here's how to set that up:

Pre-access page: [www.mysite.com/pre-access?a=b](http://www.mysite.com/pre-access?a=b)  
  
Funnel step URL: [www.mysite.com/special-offer](http://www.mysite.com/special-offer)  
  
After deadline: [www.mysite.com/pre-access](http://www.mysite.com/pre-access)  
  
The key to making this work is to use the extra parameters ("?a=b") at the end
of your pre-access URL, but make sure to not include those parameters in your
funnel step after URL.

## Advanced: Using an opt-in form on your pre-launch page

In some cases, you may want to have an opt-in form on your pre-launch page
that (upon submit) _will then start the user's tracking_ and immediately
redirect to your special offer page.  

To do this, you would want to make sure your funnel step URL is set up. This
is the page a user will be redirected to once they've opted in and their
tracking has begun:  

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d1651ef2c7d3a6ebd22b659/file-6HqB3CT3s0.jpg)

Then you will go into your Deadline Funnel campaign > Settings > Pre-Launch
area and put your opt-in form as the pre-access page, and your funnel step URL
as the "after subscriber is tracked redirect to:" step:  

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d16538404286305cb87dce0/file-DWBasptVrh.jpg)

In this example the MailChimp API webhook is already set up, so if a visitor
signs up using the opt-in form, their email address will be added to the
deadline and they will be tracked by email in the Deadline Funnel > Event
Tracking area.

However, since their IP/cookie has not been tracked yet, they will still see
the opt-in page instead of being redirected to your special offer.

To fix this, we will simply use the email link in the opt-in form's redirect
settings. This will allow Deadline Funnel to track a user's IP/cookies once
they opt-in and give them access to your special offer page:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d16544a04286305cb87dce8/file-ZOxW4zVYc5.jpg)

To copy this link correctly, you will select everything _before the question
mark_ in the link and paste it into your opt-in page's redirect area. Notice
that the part of the URL we _leave out_ is "?em=[email]" in this example:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d1654ab2c7d3a6ebd22b679/file-EQz8q6QXbX.jpg)

Now when the user clicks subscribe, the form will submit the webhook and the
IP/cookie tracking data to DF and redirect them to the special offer page.
That's it!

If you have any questions, please reach out to us in chat (the blue box in the
right hand corner) or let us know at
[help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com).

