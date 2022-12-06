# Crowdin Rewards: Get Translations done more quickly.

--------

**In order to get started, you must purchase a FynCom Subscription, deposit cash, create a Rewards Campaign, and setup your Crowdin Webhook.** <br>
_Note: Once you tell us which project/file/language you want to reward, we will Your translators must sign up through app.fyncom. com to connect their <a href="https://www.fyncom.com/crowdin-rewards-for-translations-user-setup" target="_blank">[Crowdin username]</a>. Once they are signed up, their "Translation Suggested" entries will be recorded and their "Translations Approved" will finalize the transactions.
If your translators have not created an account on app.fyncom.com, they may STILL BE ELIGIBLE for rewards... but they must create an account and get a translation approved ater their account is created.  It is ONLY once you or your team has approved a translation, that a reward will be distributed. Please ensure you have updated your preferred projects / files / langauges through FynCom or have emailed support@fyncom.com with your desired files/languages to be rewarded.
Currently, 75% of the reward value goes to the translator and 25% of the word value goes to the approver. 
who are listed below - otherwise your translation will not be eligible for a reward. The person who translates a word gets 75% of the reward, the person who 
approves the translation gets 25% of the reward. Rewards are distributed immediately upon approval of translation_.

Our goal is to help you to get your translations completed as quickly as possible. Our product makes automated micropayments to your translators on a per-word basis. It also rewards your approvers. Right now, you can test the simplest version of our product. One single reward value for every suggested translation that gets approved. 75% goes to the translator who made the suggestion. 25% goes to the reviewer who approved the suggestion. </br> 
Rewards can be as low as $0.0000000000000000000000001 per word if you wish. Typically, we see companies rewarding values like $0.005 per word, but it depends on your budget and how much you value your translations. </br>
Here are some features we have planned for the future and think you might like. However, we want to hear what features you would like and how we can best serve your needs. Just send us an email at suppport+crowdin@fyncom.com to let us know what your goals are.
* Create Rewards of different values for each "Source Language -> Target Language" in a specific file
* A/B test different Reward values for multiple files at the same time.
* A/B test different Rewards for multiple files/projects/languages at the same time.
  * This might create too much overhead for you. We think that having a single reward for all your translations might be best to start. You can always change the value of the single reward as often as you want by creating a new Rewards Campaign.

A simple overview is below. Detailed instructions are at the bottom. 
* You must <a href="https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=basic-USD-Monthly&subscription_items[quantity][0]=1" target="_blank">[create a FynCom Customer account]</a> to fund the micropayments and set reward values + input the Crowdin file to reward.
   * Create a single Rewards Campaign and upload the URL of the file/language you want to trial. If you want to multiple languages for a single file or project - please send those URLs to us by email. For now, just try a single file and see if it works for you. </br> 

* Your translators must create a <a href="https://www.fyncom.com/crowdin-rewards-for-translations-user-setup" target="_blank">[FynCom User account]</a> and input their Crowdin username to receive their rewards.</br>


## Setting up your FynCom subscription

1. Create a <a href="https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=basic-USD-Monthly&subscription_items[quantity][0]=1" target="_blank">[FynCom Subscription]</a>.<br>
2. <a href="https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=basic-USD-Monthly&subscription_items[quantity][0]=1" target="_blank">[Add funds to your account in the Wallet page]</a>. 
3. <a href="https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=basic-USD-Monthly&subscription_items[quantity][0]=1" target="_blank">[Create a Rewards Campaign]</a> and include "Crowdin" as part of your campaign name - Rewards are denominated in $ USD.
   * The example shown in photos is meant to to be used for a single campaign that specifically rewards transaltions from Estonian to Esperanto for a specfiic project (home page)
   * Note: your first campaign will be prefilled. Create your 1st prefilled campaign, then refresh and create your 2nd campaign which has your actual Rewards Campaigns details.
4. Update your Crowdin project to post Webhook data to this URL. See the image below for the exact configuration.
   * https://server.fyncom.com/v2/webhooks/crowdin
   * Ensure that "Translation.Suggested" and "Translation.Added" are included. For the best experience, please post all your Webhook data here. We plan to automate as much of your rewards processes, including rewards by project / file / language.
      * <a href="https://translations.nano.org/nano-org#languages" target="_blank">[Nano Foundation]</a>
         * Translate English words into <a href="https://translations.nano.org/nano-org/ha" target="_blank">[Hausa]</a>, 
        <a href="https://translations.nano.org/nano-org/ig" target="_blank">[Igbo]</a>, 
        or <a href="https://translations.nano.org/nano-org/yo" target="_blank">[Yoruba]</a>













## -Remove Delete / Saveing for later Setting up your Crowdin username

   ![An image showing the location of your Zapier API Key](https://fyncom-static-files.s3.us-west-1.amazonaws.com/help/Successful+Crowdin+Username.png) <br><br>
3. Now, you are ready to get rewarded for your translations! Go to any of our Approved Organizations' Crowdin pages and start translating.
   * Approved Organizations
      * <a href="https://translations.nano.org/nano-org#languages" target="_blank">[Nano Foundation]</a>
         * Translate English words into <a href="https://translations.nano.org/nano-org/ha" target="_blank">[Hausa]</a>, 
        <a href="https://translations.nano.org/nano-org/ig" target="_blank">[Igbo]</a>, 
        or <a href="https://translations.nano.org/nano-org/yo" target="_blank">[Yoruba]</a>
