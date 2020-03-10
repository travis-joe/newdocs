_**Note** : Custom answer events are currently only an option for multiple
choice (radio) questions._

Custom answer events give you the ability to fire custom Javascript events as
soon as someone selects a specific answer and goes to the next question.

You can use this with custom events in
[Facebook](https://www.facebook.com/business/help/952192354843755), [Google
Analytics](https://developers.google.com/analytics/devguides/collection/analyticsjs/events),
[Google Tag
Manager](https://support.google.com/tagmanager/answer/6106961?hl=en#CustomEvents),
[Segment](https://segment.com/docs/sources/website/analytics.js/#track), and
many others.

1

     To get started, click on "add scoring, branch logic, and custom events" in the 'questions' tab of Survey Funnel: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5978d8432c7d3a73488b6707/file-
OpNRMG8TQZ.jpg)

2

     Then, enter the code you want triggered as soon as someone chooses that specific answer option: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5978dfa3042863033a1b676d/file-V34apKNBEC.jpg)

**Note: don't include <script> or </script> tags in your custom event, because
we automatically wrap custom answer events in opening and closing script
tags.**

In this case, we're firing a Facebook custom event as soon as someone selects
this specific answer.

If you're firing custom events for analytics, you'll need to add your main
tracking code (for Facebook, Google, etc.) to the page where you're embedding
the survey (or to Customize >> General Settings >> Tracking Code, if you're
using the hosted survey) in order for the custom answer events to work:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5978e0a62c7d3a73488b6752/file-
YSIz4JAd5V.jpg)

If you have any questions, please contact us on chat or let us know at
[help@surveyfunnel.io](mailto:mailto:help@surveyfunnel.io).

