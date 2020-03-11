# Timing tips for AWeber

In this guide we will cover how you can use Send Windows in your AWeber campaign to sync up the timing of your deadline with the timing of your emails.

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5c6ef9b9042863543ccd4b81/file-DdI6ySIA1M.png)

In the screenshot above, we have it set to send the first message in the campaign immediately, and then that's followed by two wait conditions, the second immediately following the first:

* Send at 12:00am on any day \(attached to a 1 minute wait event\)
* Send at 9am on any day \(also attached to a 1minute wait event\)

What that logic does is send the first message as soon as someone starts the campaign, and then waits until the next day at 9am to send the next email.

You can use that logic along with a "X days at 11:59pm" Deadline Funnel campaign to sync the timing.

So for example, the campaign shown in the screenshot above would match up with a "2 day at 11:59pm" evergreen campaign, because the first email gets sent immediately \(day 0\), and the next email is sent on day 1, and then the final email is sent on day 2.

If you have any questions, feel free to reach out to us in live chat in the bottom right hand corner or shoot us an email at help@deadlinefunnel.com

