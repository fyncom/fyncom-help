# Setting up Sendgrid Drafts

--------
[//]: # (todo Address the "basic" vs "advanced" payment plan here.... Simple emails can indeed send conditional rewards emails....)
**\*The only emails that will be able to trigger FynCom rewards are the ones you send from the** [FynCom dashboard](https://dashboard.fyncom.com/)**.**

## Setting up Sendgrid integration

First, please make sure that you or your organization have input your Sendgrid API key through the [FynCom settings page](https://dashboard.fyncom.com/settings#).

### From the Design Library.

One of the preferred ways our organization uses Sendgrid is to create a [Design Template](https://mc.sendgrid.com/design-library/your-designs) email. These are 
reusable templates that can be used to create Marketing Email sends or Transactional Email sends. Here, we will use this to create a Marketing Email draft.

_**NOTE: <span style="color:#FF5A5F">You should NOT send from the Sendgrid page**</span>, only use Sendgrid to design your email. <br>
The FynCom dashboard will allow you to send this email. You MUST send this email from the FynCom dashboard because that is where you select the Rewards 
Campaign that should be associated with this email._

- Navigate to ["Design Library"](https://mc.sendgrid.com/design-library/your-designs) of your Sendgrid account.<br>
![The design library gives you reusable templates](https://fyncom-static-files.s3.us-west-1.amazonaws.com/help/4+Setting+up+Sendgrid+Drafts.png)
    - Click the 3 dots to the right of the name of the template you want to use. (If you don't already have a template here, please create one, then continue with these guidelines)
      - Select "Create Single Send"
          - Select "Design Editor"<br>
          ![When done filling out the required fields in Sendgrid, you are ready to head to FynCom dashboard to send](https://fyncom-static-files.s3.us-west-1.amazonaws.com/help/3+Setting+up+Sendgrid+Drafts.png)
            - Advanced users can try the Code Editor, but we prefer the Design Editor for simple, yet powerful email templating.
- At this point, you will be sent to the Sendgrid email design page where you can fine-tune the body of the email. Here, you should update these mandatory fields.<br>
  ![When done filling out the required fields in Sendgrid, you are ready to head to FynCom dashboard to send](https://fyncom-static-files.s3.us-west-1.amazonaws.com/help/2+Setting+up+Sendgrid+Drafts.png)
    - Single Send Name
      - This is for your internal records and this will show up in the FynCom dashboard.
    - From Sender
        - This is the email that your recipients will see as the "From" email.
    - Subject
        - This is the subject your recipients will see
    - Send To
        - Select the list of contacts you want this email to go out to.
    - Unsubscribe Group
        - Select the unsubscribe group you want to be associated with this send. 
- Sendgrid will auto-save this draft for you as you work, but just to be safe, click the "Save" button at the top. Do NOT send this yet. [Next, we will go into 
the FynCom dashboard to attach a reward campaign to your draft and then send from your FynCom dashboard.](https://docs.google.com/document/d/19K9DL0ahJOlMT2bxzHfp1OsuvOzu7kgdDVIRdz3VOrQ/edit#)
![When done filling out the required fields in Sendgrid, you are ready to head to FynCom dashboard to send](https://fyncom-static-files.s3.us-west-1.amazonaws.com/help/1+Setting+up+Sendgrid+Drafts.png)


