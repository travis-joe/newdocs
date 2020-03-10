1

    "Send post data to thank you page" is an option that automatically sends the survey data to your thank you page as $_POST data, if selected as shown here: 

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5978d29b2c7d3a73488b66d7/file-v32EUccFls.jpg)

In order for the $_POST data to be sent to your thank you page, you need to
first set up a rule in your survey with a "redirect to thank you page" action.

Then, when someone is redirected to your thank you page, all of the survey
data will be included in the $_POST data on that page. Here's an example:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5978d3872c7d3a73488b66de/file-
CyZUOfgA9P.jpg)

You can then access that data on your thank you page via custom code, that you
would need to create to parse the data, and then display it on the page or
send it off to another platform.

2

    "Send name and email to thank you page URL" sends the name and email address of the person submitting the survey to your thank you page URL. 
In order to use this option you need to have an optin form added as an element
to your survey, and you also need to set up a thank you page redirect under
the Rules tab.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/59fcb74d0428633199242e93/file-
McKKKjmQkx.jpg)

As an example, if you have this option enabled, and you also have a redirect
enabled so that people go to "https://surveyfunnel.io" after the survey is
submitted, then your thank you page URL would look like this:

[https://surveyfunnel.io/?score=0&sfname=John&sfemail=test@test.com](https://surveyfunnel.io/?score=0&sfname=John&sfemail=test@test.com)

Then you can add custom code to your thank you page to retrieve these GET
parameters ( **sfname** and **sfemail).**

If you have any questions, please contact us on chat or let us know at
[help@surveyfunnel.io](mailto:mailto:help@surveyfunnel.io).

