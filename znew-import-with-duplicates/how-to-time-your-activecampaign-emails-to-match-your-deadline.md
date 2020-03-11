# How to Time Your ActiveCampaign Emails to Match Your Deadline

![](https://fast.wistia.com/embed/medias/srn2zw3dqm/swatch)

Sometimes you want to give your subscribers reminder emails letting them know when their deadline is ending. But what happens if some of your subscribers sign up at 8 AM, and others subscribe at 4 PM on the same day? How can you make sure the reminder emails match the set deadline?

Our documentation below will help you with that exact scenario:

1. Navigate to your ActiveCampaign automation and ensure that you have a tag or other starting point to mark when users are subscribed, and also check to be sure that you have followed the [API setup steps](https://documentation.deadlinefunnel.com/article/244-how-to-integrate-deadline-funnel-with-activecampaign-api) to add your webhook URL to the automation: ![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d3f44d42c7d3a2ec4bf8ff5/file-KHcpGVdwBv.jpg) 2. In this example, we've set the campaign to be 3 days and to end at 11:59 PM EST on the final day: ![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d3f48960428634786758f41/file-BHdA0Ag6eX.jpg) 3. So we see that when the user signs up, three things happen. A tag is added to the user which kicks off our automation, and then a webhook is sent back to Deadline Funnel to trigger the deadline, and our first email goes out to our subscriber. We then want to add two conditional statements which will allow us to line up our emails with the deadline:
2. Set one "wait until" timer to wait until 0 \(12 AM\)
3. Set one more "wait until" timer to 8 AM the next day

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d3f4ac30428634786758f74/file-EJ7v83O27w.jpg)

1. Now we'll set the emails to go out each day until the last day is reached:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d3f4d520428634786758fb0/file-rQ7RuMBhMd.jpg) 4. On the last day we know that our "Day 3" morning email will go out at 8 AM – so we can set another two reminder emails to go out 9 hours before the deadline ends and 3 hours before the deadline is reached, respectively:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d3f4e502c7d3a2ec4bf90ab/file-uEiQC1Hnh4.jpg)

**Important:** Please note that in this example, the time zone selected in Deadline Funnel and ActiveCampaign is set to EST. You can set this time zone to whatever you wish, but the time zones set in Deadline Funnel and ActiveCampaign _must_ be the same.

That's it! Please be sure to [test your campaign](https://documentation.deadlinefunnel.com/article/660-how-to-test-%20your-deadline-funnel).

We are available on chat or at help@deadlinefunnel.com if you have any questions.

