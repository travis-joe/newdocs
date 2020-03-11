# How to time your Ontraport campaign with your Deadline Funnel campaign

Sometimes you want to give your subscribers reminder emails letting them know when their deadline is ending. But what happens if some of your subscribers sign up at 8 AM, and others subscribe at 4 PM on the same day? How can you make sure the reminder emails match the set deadline?

Our documentation below will help you with that exact scenario:

1. Navigate to your Ontraport campaign and ensure that you have a welcome email or other starting point to mark when users are subscribed, and also check to be sure that you have followed the [API setup steps](https://documentation.deadlinefunnel.com/article/251-how-to-integrate-deadline-funnel-with-ontraport-api) to add your webhook URL to the campaign: ![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d93548804286364bc8fc659/file-ARCyB9jPao.jpg) 2. Then you wait until it's 12:00 AM "in my timezone" \(set preferred timezone in Ontraport &gt;&gt; Personal Profile\): ![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d935a7c04286364bc8fc6da/file-BbaMx2mSgJ.jpg) 3. Then you wait until it's 8:00 AM \(again in your timezone\): ![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d935aae2c7d3a7e9ae1db50/file-NVVNtyKIy0.jpg) 4. At this point you can add another email to the campaign, the email will be sent at 8 AM:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d935b2504286364bc8fc6ed/file-Dqjv7cmaf7.jpg) 5. Then set another wait condition for one day later. We know now that each day our emails will be sent out at 8 AM:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d935b9804286364bc8fc6fc/file-SiqoigPAWJ.jpg) 6

Now we'll set the emails to go out each day until the last day is reached:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d935c272c7d3a7e9ae1db6e/file-paplHhipj4.jpg) 7

On the last day we know that our "Day 3" morning email will go out at 8 AM – so we can set another reminder email to go out 12 hours later at 8 PM:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d935dfb04286364bc8fc723/file-35AiEcm6RP.jpg) 8. At this point we are aware that there is only 3 hours and 59 minutes remaining before their deadline runs out. We can send another email if we wish within that time:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5d935ea804286364bc8fc736/file-gV9tC9CHui.jpg)

**Important:** Please note that in this example, the time zone selected in Deadline Funnel and Ontraport is set to EST. You can set this time zone to whatever you wish, but the time zones set in Deadline Funnel and Ontraport _must_ be the same.

That's it! Please be sure to [test your campaign](https://documentation.deadlinefunnel.com/article/660-how-to-test-%20your-deadline-funnel).

If you have any questions, please let us know at [help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com).

