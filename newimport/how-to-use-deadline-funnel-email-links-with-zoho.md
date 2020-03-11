You can use Deadline Funnel email links in your Zoho emails but you may need
to make a small edit to the email link and image link that you will see in
your Email Setup within Deadline Funnel:

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5ab40b20042863478ea7cf78/file-uNoAOksS1c.png)

![](https://s3.amazonaws.com/helpscout.net/docs/assets/53974d6ce4b0c76107b109d1/images/5ab40a6c042863478ea7cf6e/file-J82wrpGx8G.png)By
default, we show the Zoho placeholder in the links and image code as
**${Contacts.Email}**.

But if you are using Zoho CRM for Leads (instead of Contacts), Zoho CRM with a
non-English account, or Zoho campaigns, you will need to manually change the
**${Contacts.Email}** placeholder in your Deadline Funnel link/code to the
correct one, as outlined below.

## Email Placeholder for Zoho CRM:

Zoho CRM has different email placeholders, depending on whether you are using
a Leads template or a Contacts template.

If you are using a Contacts template, the email placeholder will be
${Contacts.Email}, which you can copy directly from the Email Setup >> Email
Links in Deadline Funnel

If you are using a Leads template, the email placeholder will be
${Leads.Email} and you will need to edit the email link you copy from Deadline
Funnel to use ${Leads.Email} at the end. The resulting Email Link will look
like this:

    
    
    http://dfl3.us/go/1848/vhUulE/1493322076?em=${Leads.Email}
    

The image code will look like this:

    
    
    <img style="display:block;border:none;outline:none;width:400px;opacity:1;max-width:100%" src="https://dfimage.com/email-image/3243/kchmKY/1521577080?em=${Leads.Email}&e40ec=1270628395&VFEw0=Gcvdq" border="0" width="400"/><br>  
    

## Email Placeholder for Zoho CRM (for non-English accounts):

If you have a Spanish-language account, the placeholder at the end of your
email link will need to be edited to either ${Leads.Correo electrónico} or
${Contacts.Correo electrónico}, depending on whether you're using a Leads or
Contact template.

If you have a different language Zoho account, the email placeholder will be
personalized differently. Contact us via chat or through the  [help
desk](mailto:mailto:help@deadlinefunnel.com) and let us know what other
lanugage you are using.

## Email Placeholder for Zoho Campaigns:

If you are using Zoho Campaigns, you will use $[EMAIL]$ as your email
placeholder. In this instance, you would edit the Email Link from your Email
Setup >> Email Links to be:

    
    
    http://dfl3.us/go/1848/vhUulE/1493322076?em=$[EMAIL]$  
    

And your image code will look like this:

    
    
    <img style="display:block;border:none;outline:none;width:400px;opacity:1;max-width:100%" src="https://dfimage.com/email-image/3243/kchmKY/1521577080?em=$[EMAIL]buffer_3amp;e40ec=1270628395&VFEw0=Gcvdq" border="0" width="400"/>  
    

If you have any questions, please let us know at
[help@deadlinefunnel.com](mailto:mailto:help@deadlinefunnel.com).

