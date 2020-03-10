To follow along you need to have integrated your Zapier account with both
Survey Funnel and your email service provider (ESP). We are using MailChimp in
this tutorial, but you can use any ESP that integrates with Zapier.

## Video Tutorial:

## Create your survey:

**Note** :  Before you begin, you should create custom fields inside your
email service provider to hold the UTM information that will be sent from
Zapier.

1

     Create your survey inside Survey Funnel and be sure to include a multiple choice question and optin form: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b895b2d2c7d3a03f89e567c/file-
pb7HWVgK96.png)

2

     Create a catch-all rule with a zapier outcome: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b8840322c7d3a03f89e4ce6/file-
wz4fj7wjJO.png)

3

     Visit your deploy survey link and copy the hosted-URL for your survey: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b8840c10428631d7a8a8f16/file-A8MBXSdfWz.png)

4

     Add your UTM parameters to the end of the URL so you can complete and submit the survey to provide sample data for Zapier to pull. In the video, I added the following UTM parameters to the end of the URL so it looks like this: 

[https://surveyfunnel.io/campaign/16160/deep/surveys/fd87084ec6/?utm_source=facebook&utm_medium=social&utm_campaign=campaign_promotion](https://surveyfunnel.io/campaign/16160/deep/surveys/fd87084ec6/?utm_source=facebook&utm_medium=social&utm_campaign=campaign_promotion)

## Set up the Survey Funnel (Trigger) part of your Zap:

1

     Create a Zap with Survey Funnel as the Trigger and choose 'New Survey Entry': 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b8843130428631d7a8a8f59/file-
ekUOf4Rw7o.png)

2

     Select the name of your survey and the Zapier outcome you chose, then click 'Continue': 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b88438d0428631d7a8a8f60/file-6s41CE1OoE.png)

3

    Let Zapier fetch sample data to test your integration:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b89613b2c7d3a03f89e56bd/file-
NPQC9h4vKJ.png)

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b8960760428631d7a8a98eb/file-6bn0nsrvJc.png)

4

    View the entries to be sure the correct fields are included:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b8962b62c7d3a03f89e56ce/file-y7ol8fZqKM.png)

## Set up the ESP (Action) Part of your Zap:

1

    Choose your ESP for the Zap action:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b89637e0428631d7a8a9918/file-Y2h1aZKozW.png)

2

    Choose the Add/Update Subscriber action:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b89641f0428631d7a8a9921/file-G3mfSjUpaT.png)

3

    Click 'Save + Continue' for your connected email service provider account:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b8964992c7d3a03f89e56ed/file-
DWO5oARkCa.png)

4

    Select your list and match each field you want to pass with the custom fields in your ESP and click 'Continue':

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b8964af0428631d7a8a992a/file-
xnYZFHN8oC.png)

5

    Click 'Send test to MailChimp' to send your test data to your ESP:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b8965792c7d3a03f89e56f4/file-
Of4DppouYb.png)

6

    Click Finish' after your test is successful:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b8967262c7d3a03f89e5709/file-
KHHFaHb963.png)

7

    Name your Zap and turn it on:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b8967520428631d7a8a994e/file-
zdqRvSDTcw.png)

##  Confirm with your ESP:

1\. Navigate to your list in your ESP account to confirm that the email and
the UTM custom fields were passed:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5b89687c2c7d3a03f89e5717/file-4RxBmdtOeq.png)

That's it!

If you have any questions, please let us know at
[help@surveyfunnel.io](mailto:mailto:help@surveyfunnel.io).

