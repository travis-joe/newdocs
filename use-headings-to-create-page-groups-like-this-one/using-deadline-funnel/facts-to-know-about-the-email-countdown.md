**Note** :  We just updated our User Interface so it will look different than
it does in this video. We will be updating this video shortly!

Sometimes we hear from clients that when they're testing Deadline Funnel's
countdown image, the time in their test email doesn't match the actual time
they expected to see.

If this is happening to you, this explains why.

###  Google Gmail and some other email systems aggressively cache images.

Caching is a way to speed up showing images.

Google stores a fixed, unchanging version of the countdown timer image in the
email on their server, and whenever they detect that you are opening that same
image again, they load the image from THEIR server, not ours, so the countdown
doesn't update.

When you're testing, it's common to test the countdown image, and then if you
run another test later on, to expect the countdown image in your email to be
different. But since Google already has a copy of that image on their server,
any time you open an email with that image from the same URL, Google doesn't
grab the new image for you... it shows you the one you saw the first time.

Now that you understand how Gmail caching for images works, here is the
solution we created that you saw in the video.  

## How We Fixed the Gmail Caching Issue

Every time you want to include a Deadline Funnel email countdown in your
follow-up emails, click to get a 'fresh' copy of the image URL.

For example, here is the Email Timer Code that I can include in my Day 1
email:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5a9468ef042863534055978f/file-
cP2vQjy2xc.png)

Here is the URL for Day 2, that was created the second time I clicked 'Copy':

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5a9468ff0428635340559791/file-c5LP3FbVFl.png)

And this is the URL for Day 3, that was created the third time I clicked
'Copy':

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5a9469100428635340559795/file-8xiKGeSgOR.png)

Deadline Funnel will add a different parameter to the end of each Image URL so
that your image will show up correctly in Gmail.

This extra parameter on the end of the Deadline Funnel image URL makes Google
believe that they don't have a cached version of this image and Gmail will
fetch the updated countdown image from our server.  

## Testing Your Image

Before you send real leads through your email sequence **it's important to
test. Always test first.**

If you open (or reopen) an email you have sent yourself and you are seeing a
time on the countdown that's different than the one you see on your webpage,
the first thing to do is to hit refresh on your Gmail email tab and you should
see a refreshed version of your email countdown image.

You also should know that some email software systems do not personalize the
test emails that you send to yourself from inside the email editor. This can
interfere with your testing. If you can add one of your emails to your email
software and have that test subscriber go through the sequence as a lead
would, this is an extremely accurate way to test.

Another way to test the email image is to put the email URL from Deadline
Funnel in a browser window... so that caching is not an issue. You can do this
by copying the Image URL from Edit your Campaign << Email Setup, removing the
email address portion at the end and pasting that into a new web browser. Be
sure to **remove the question mark and everything that follows**.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/53974d6ce4b0c76107b109d1/images/5a9469782c7d3a54cdfcd117/file-
XZfVj5NA6z.png)

**If you are viewing the email in Outlook** , you'll notice that you see the
correct time but the countdown isn't animated. This is because Outlook does
not show animated images. This is a deficiency of Outlook.

If you have any questions, please let us know at
[help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com).

