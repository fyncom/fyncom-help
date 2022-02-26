# Attaching FynCom Rewards to your Sendgrid Emails

_________________

## Setting up Sendgrid integration

First, please make sure that you or your organization have input your Sendgrid API key 
through the [FynCom settings page](https://dashboard.fyncom.com/settings#).

- Navigate to the “Email” tab in the left-hand navigation sidebar.
- Select “Marketing Email”. 

[//]: # (note, this is a design library image.... you seem to be discussing marketing email, but that is not visualized here.)
  ![Select the marketing email tab of Sendgrid as displayed in this image](https://fyncom-static-files.s3.us-west-1.amazonaws.com/help/1.png)

- Select the Rewards Campaign you want to associate with this send.
- Select the Draft Template
  - These drafts are pulled directly from your Sendgrid account using the API key your organization admin has added through the 
  [Settings page](https://dashboard.fyncom.com/settings#).
  
    ![Update your Sendgrid API key in the settings of your FynCom Dashboard](https://fyncom-static-files.s3.us-west-1.amazonaws.com/help/2.png)
  
    - If you need a walk through on how to set up your Sendgrid drafts, please check out this [tutorial](https://docs.google.com/document/d/1NiAXX3wbmdDjg34J8NldwhPxIxUbt8w4Bk6Nnxw7cR4/edit?usp=sharing)
    - The subject of that draft will appear, helping you know which email draft is selected.

    |  Before Selecting Draft  |                                                              After Selecting Draft                                                              |
    |:-----------------------------------------------------------------------------------------------------------------------------------------------:|:-----------------------:|
      | ![email page without template selected goes here](https://fyncom-static-files.s3.us-west-1.amazonaws.com/help/3.png)| ![After selecting the draft, the subject of that draft is visible](https://fyncom-static-files.s3.us-west-1.amazonaws.com/help/5.png) |
    
    - Note: If there are any incomplete fields in your draft, the dashboard will let you know with an error message. If you see any of these error messages,
    please go into your Sendgrid account and fix that error for that draft located in your ["Single Sends"](https://mc.sendgrid.com/single-sends?view=raw).
    ![Your FynCom dashboard will display an error message if your Sendgrid draft is not ready to send](https://fyncom-static-files.s3.us-west-1.amazonaws.com/help/4.png)

- Now just hit the “Send email” and you’re done!
  - You can see how many people have gotten rewards from your campaigns by using the [“Transactions”](https://dashboard.fyncom.com/campaign/transaction) page in FynCom
  - If you want to see email details like opens, clicks, etc., you can do that through Sendgrid’s campaign details for that particular campaign.
  ![After successful send, you will see a green box near the top of your screen](https://fyncom-static-files.s3.us-west-1.amazonaws.com/help/6.png)
