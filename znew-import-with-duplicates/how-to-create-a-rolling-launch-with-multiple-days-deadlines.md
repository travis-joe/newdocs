# How to Create A Rolling Launch With Multiple Days Deadlines

The first thing that determines exactly how you do this is which email software you're using. We have direct integrations with many popular ones. In addition, you can do an optin for integration if that works better.

If you want to make sure that subscribers don't skip ahead and can only get to the current day's content, the easiest way to do this is to make the various URLs not so easy to predict.

So instead of  
day-1-video  
day-2-video... etc

Maybe  
day-1-video  
video-day-two-welcome

This way your subscribers need to click the links you send in the emails to access the pages.

\(BTW, this isn't the only way to do it, but the easiest\)

Each page will automatically closed at a time you choose by setting up multiple Deadline Funnel countdowns, one for each page.

You have some options for when you trigger the deadlines.

**A\) Trigger via api the day of**

This is probably the preferred method but requires an api integration with one of the many email softwares we support.

Each deadline will be an evergreen deadline that expires at midnight the same day it's assigned.

Specifically, you'll set up each evergreen deadline as 0 days. Which means "the deadline will be over at midnight the same day it's set for the lead"

Then you set up the automation sequence of your email software to send a webhook \(aka HTTP Post\) to Deadline Funnel the morning before that day's email goes out.

The webhook will set the tracking for this lead in our system, and you must use the Deadline Funnel email link in the email, so when they click the link in your email they'll be properly tracked for that deadline.

**B\) Trigger all on optin**

In this method, each deadline will have a different length:  
0 day  
1 day  
2 days... etc

And you'll start the tracking for all of them when they optin.

If you have additional questions about how to set this up, contact us via chat or email and we'll be happy to help.

