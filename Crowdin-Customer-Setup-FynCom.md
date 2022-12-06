# Crowdin Rewards: Get Translations done more quickly

--------

**In order to get started, you must purchase a FynCom Subscription, deposit funds, create a Rewards Campaign, setup your Crowdin Webhook, and submit your 1st file URL.** <br>
_Note: Please email your crowdin file URL (editor view) to support+crowdin@fyncom.com. Email us for any other questions or fast help_

**Overview** </br>
Our goal is to help you to get your translations completed as quickly as possible. Our product makes automated micropayments to your translators on a per-word basis. Rewards are distributed immediately upon approval of translation. Your approvers are also eligible for rewards. **Right now, you can test the simplest version of our product. Choose one single "Reward per Word" value for every suggested translation that gets approved. 75% goes to the translator who made the suggestion. 25% goes to the reviewer who approved the suggestion.** </br>
Rewards can be as low as $0.0000000000000000000000001 per word if you wish. Typically, we see companies rewarding values like $0.005 per word, but it depends on your budget and how much you value your translations. Here are some features we have planned for the future and think you might like. However, we want to hear what features you would like and how we can best serve your needs. Just send us an email at suppport+crowdin@fyncom.com to let us know what your goals are.

* Planned features for future updates
  * Upload your project file URL into your FynCom dashboard page (1st feature we will add, if you like this soft launch / overall idea)
  * Create Rewards of different values for each "Source Language -> Target Language" in a specific file
  * A/B test different Reward values for multiple files at the same time
  * A/B test different Reward values for multiple files/projects/languages at the same time
    * This might create too much overhead for you. We think that having a single reward for all your translations might be best to start. You can always change the value of the single reward as often as you want by creating a new Rewards Campaign.

## Simple overview: Setting up your FynCom subscription

A simple overview of how to start is below. Detailed instructions are at the bottom.

* You must <a href="https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=basic-USD-Monthly&subscription_items[quantity][0]=1" target="_blank">[create a FynCom Customer account]</a> to fund the micropayments and set reward values + input the Crowdin file to reward.
  * Create a single Rewards Campaign and upload the URL of the file/language you want to trial. **If you want to try multiple languages and/or a set of files - please send those URLs to us by email**. For now, just try a single file and see if it works for you. </br>
* Your translators and approvers must create a <a href="https://www.fyncom.com/crowdin-rewards-for-translations-user-setup" target="_blank">[FynCom User account]</a> and input their Crowdin username to receive their rewards.</br>

## Detailed overview: Setting up your FynCom subscription

1. Create a <a href="https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=basic-USD-Monthly&subscription_items[quantity][0]=1" target="_blank">[FynCom Subscription]</a>. $20/month is the starting plan.<br>
2. <a href="https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=basic-USD-Monthly&subscription_items[quantity][0]=1" target="_blank">[Add funds to your account in the Wallet page]</a>.
3. <a href="https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=basic-USD-Monthly&subscription_items[quantity][0]=1" target="_blank">[Create a Rewards Campaign]</a> and **include "Crowdin" as part of your campaign name**. Rewards are denominated in $ USD.
   * The example screenshot below is meant to to be used for a single campaign that specifically rewards transaltions from Estonian to Esperanto for a specfiic project (home page).
      * _Please note: your first campaign will be "prefilled". Create your 1st prefilled campaign, then you can edit the fields and and create your 2nd campaign which has your actual Rewards Campaigns details._
4. Update your Webhook in your Crowdin settings page to post data to this URL. See the image below for the exact configuration.
   * <https://server.fyncom.com/v2/webhooks/crowdin>
      * Ensure that "Translation.Suggested" and "Translation.Added" are included. For the best experience, post all your Webhook data here. We plan to automate as much of your rewards processes as possible, including rewards by project updated / file added / language added, etc.
5. Open your file in editor view. Select the language you want and copy the URL.
   * Paste the URL into an email and send it to us at suppport+crowdin@fyncom.com. Later, we will add a page into the settings of your FynCom dashboard or even in Crowdin itself, where you can paste this URL. Please bear with us as we build this out for you. Thank you!

## Getting your translators activated

1. There are several Crowdin translators already active from previous FynCom/Crowdin campaigns. FynCom publishes each company & project file on its [on its website](https://www.fyncom.com/crowdin-rewards-for-translations-user-setup). So any FynCom affiliated translators can discover your project and start translating for you.
   * We also update our translators when a new company joins the list
2. If you need to get your existing translators to sign up and know you're rewarding them, a simple email campaign, blog post, website update, or social media update works best. Just send your translators to [this page](https://www.fyncom.com/crowdin-rewards-for-translations-user-setup), so they can get setup.