Following are some tips for setting up your email sequence when you integrate
Deadline Funnel with your ESP via the API integration.

In the example below, we are using
[ActiveCampaign](https://documentation.deadlinefunnel.com/article/244-how-to-
integrate-deadline-funnel-with-activecampaign-api) which offers an API
integration with Deadline Funnel and logic or wait conditions in their
automations.

When you are setting up your sales email sequence, we recommend sending
multiple emails on the final day of your campaign, i.e., 9AM, 2PM, and 7PM.

## Video Tutorial:



**Example of a schedule of the emails to send on your final campaign day:**

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b0ee3810428632c466a5944/file-y7XlGwaNzz.png)

## It can be challenging to set up the 3 final day emails based on when
someone opts in:

Many ESPs will send the emails 24 hours after optin, so if you opt in at 11AM,
the follow-up emails will also send at that time, as shown below:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b0eeb820428632c466a597d/file-A5KKIm0tRP.png)

The time someone opted in isn't necessarily the best time to send follow-up
emails. More importantly, you want to make sure your 2nd and 3rd 'final day'
emails don't end up being sent the day 'after' your deadline has expired.

##  Here's how to solve this:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b0f03f50428632c466a5ad3/file-
ZLfOkRFTt5.png)

  1. As soon as someone enters the sequence trigger the http post (webhook) to sync your ESP with Deadline Funnel
  2. Add a wait condition until midnight in your deadline's time zone
  3. Add a 2nd wait condition at 7AM for your deadline time zone
  4. THEN send your first sequence email once the email time has been established as 7AM in your deadline time zone

Be sure to test this by opting in at several different times of day to make
sure your first sequence email is sent at

If you have any questions, please let us know at
[help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com).

