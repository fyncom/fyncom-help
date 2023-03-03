#Notes2 - delete everything between </head> <body> and Pricing. Make sure you leave the <body> tag.
Export as HTML and then modify html as instructed in multiline comment below.

~~Redirecting the window requires controlling the parent. Use `onclick="window.parent.location.href='link';"` to send to new page. Nothing else works except this.~~
Redirecting the window requires controlling the parent. Use `onclick="window.open('url'), 'target=_blank', 'rel=noopener noreferrer';"` to send to new tab. <br>
You will also want to update the Zapier href links with this (see Integrations row) `target="=_blank", rel="noopener noreferrer"`

```
MODIFY HTML WITH BELOW CODE

HOTJAR IFRAME CODE IS NOT VIABLE INTO HEAD AND BODY. WILL RESTRICT JS

TURNS IMAGES INTO LINKS FOR THE TOP IMAGES - After converting from MD to HTML - replace the table headers with this.
  <th align="center" md-src-pos="2253..2453"><img src="https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Standard+A2_50.png" alt="Standard Pricing" __idea-generated="true" md-src-pos="2298..2408" onMouseOver="this.style.cursor='pointer'" onclick="window.open('https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=standard-USD-Monthly&amp;subscription_items[quantity][0]=1'), 'target=_blank', 'rel=noopener noreferrer';"></th>
  <th align="center" md-src-pos="2454..2697"><img src="https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Pro+A3_.png" alt="Pro Pricing" __idea-generated="true" md-src-pos="2456..2554" onMouseOver="this.style.cursor='pointer'" onclick="window.open('https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=pro-USD-Monthly&amp;subscription_items[quantity][0]=1'), 'target=_blank', 'rel=noopener noreferrer';"></th>
  <th align="center" md-src-pos="2698..2894"><img src="https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Enterprise+A4.png" alt="Enterprise Pricing" __idea-generated="true" md-src-pos="2740..2851" onMouseOver="this.style.cursor='pointer'" onclick="window.open('https://www.fyncom.com/contact'), 'target=_blank';"></th>

FOR THE 4 COLUMN TEXST
      <td colspan="4" align="center" md-src-pos="7361..7460">User Experience When Receiving Rewards + Cashing Out</td>
<td colspan="4" align="center" md-src-pos="10439..10538">Ways You Can Reward Responses (Reward Integrations)</td>
<td colspan="4" align="center" md-src-pos="17981..18080">Developer Tools</td>
<td colspan="4" align="center" md-src-pos="18827..18926">Admin Tools</td>
Delete the empty columns that get created in each row that has a "full row" text

FOR THE BUTTONS IN THE LAST CELL
    <td align="center" md-src-pos="6795..6991"><button name="button" style="background-color:#4A90E2;color:white" onMouseOver="this.style.cursor='pointer'" onclick="window.open('https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=standard-USD-Monthly&amp;subscription_items[quantity][0]=1'), 'target=_blank', 'rel=noopener noreferrer';">Get Standard</button></td>
    <td align="center" md-src-pos="6795..6991"><button name="button" style="background-color:#4A90E2;color:white" onMouseOver="this.style.cursor='pointer'" onclick="window.open('https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=pro-USD-Monthly&amp;subscription_items[quantity][0]=1'), 'target=_blank', 'rel=noopener noreferrer';">Get Pro</button></td>
    <td align="center" md-src-pos="6992..7188"><button name="button" style="background-color:#4A90E2;color:white" onMouseOver="this.style.cursor='pointer'" onclick="window.open('https://www.fyncom.com/contact'), 'target=_blank';">Contact Us</button></td>

NOTE: YOU NEED 2 ELEMENTS - 1 for mobile and 1 for desktop.

Use this CSS Code in the Style tags for mobile. Hide desktop on mobile and hide mobile on desktop. Don't stretch too far on mobile or you'll lose horizontal scroll

<table class="small" md-src-pos="22759..23113">

   <style>
       th {
           border-right:hidden!important;
           border-left:hidden!important;
           border-top:hidden!important;
       }
       tr {
            border-left:2px solid black;
       }
</style>

```


[//]: # (You will want to manually add links into the HTML later too.)

# Pricing
A part of your monthly subscription is usable for Rewards. Subscription does not roll over at the end of the month. Account top-ups roll over indefinitely.

| ![Pricing](https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Graphic+A1.png) | ![Standard Pricing](https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Standard+A2_50.png) |                 [![Pro Pricing](https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Pro+A3_.png)]("https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=pro-USD-Monthly&subscription_items[quantity][0]=1)                 | ![Enterprise Pricing](https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Enterprise+A4.png) |
|:-------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------:|
|                                   "Use It or Lose It" Credits*                                    |                                                      $20                                                       |                                                                                                                                       $50                                                                                                                                        |                                                     Custom                                                      |
|                                          Sender Accounts                                          |                                                       3                                                        |                                                                                                                                        10                                                                                                                                        |                                                      100+                                                       |
|                                   Rewards Campaigns<sup>1</sup>                                   |                                                       5                                                        |                                                                                                                                        20                                                                                                                                        |                                                    Unlimited                                                    |
|                                      Commission<sup>2</sup>                                       |                                                      30%                                                       |                                                                                                                                       15%                                                                                                                                        |                                                       5%                                                        |
|                                              Support                                              |                                                     Email                                                      |                                                                                                                             Priority, Email & Phone                                                                                                                              |                                                Dedicated Manager                                                |
|                       User Experience When Receiving Rewards + Cashing Out                        |
|                                  User Dashboard to Manage Funds                                   |                                                       ✅                                                        |                                                                                                                                        ✅                                                                                                                                         |                                                        ✅                                                        |
|                                      User Gift Card Cashout                                       |                                                       ✅                                                        |                                                                                                                                        ✅                                                                                                                                         |                                                        ✅                                                        |
|                                "1 Click Redeem" Email Notification                                |                                                       ❌                                                        |                                                                                                                                        ✅                                                                                                                                         |                                                        ✅                                                        |
|                                    Branded Email Notifications                                    |                                                       ❌                                                        |                                                                                                                                        ✅                                                                                                                                         |                                                        ✅                                                        |
|                        Ways You Can Reward Responses (Reward Integrations)                        |
|                                      Google Calendar Rewards                                      |                                                       ✅                                                        |                                                                                                                                        ✅                                                                                                                                         |                                                        ✅                                                        |
|                                         Calendly Rewards                                          |                                                       ✅                                                        |                                                                                                                                        ✅                                                                                                                                         |                                                        ✅                                                        |
|                                       Google Forms Rewards                                        |                                                       ✅                                                        |                                                                                                                                        ✅                                                                                                                                         |                                                        ✅                                                        |
|                                         Typeform Rewards                                          |                                                       ✅                                                        |                                                                                                                                        ✅                                                                                                                                         |                                                        ✅                                                        |
|                                          Zapier Rewards                                           |                                                       ✅                                                        |                                                                                                                                        ✅                                                                                                                                         |                                                        ✅                                                        |
|                                           Email Rewards                                           |                                                       ✅                                                        |                                                                                                                                        ✅                                                                                                                                         |                                                        ✅                                                        |
|                                           Text Rewards                                            |                                                       ✅                                                        |                                                                                                                                        ✅                                                                                                                                         |                                                        ✅                                                        |
|                                           Call Rewards                                            |                                                       ❌                                                        |                                                                                                                                        ❌                                                                                                                                         |                                                        ✅                                                        |
|                                        Salesforce Rewards                                         |                                                       ❌                                                        |                                                                                                                                        ❌                                                                                                                                         |                                                        ✅                                                        |
|                                        Custom Integrations                                        |                                                       ❌                                                        |                                                                                                                                        1                                                                                                                                         |                                                    As needed                                                    |
|                                          Developer Tools                                          |
|                                            API Access                                             |                                                       ❌                                                        |                                                                                                                                        ✅                                                                                                                                         |                                                        ✅                                                        |
|                                            Admin Tools                                            |
|                                    Rewards Campaign Dashboard                                     |                                                       ✅                                                        |                                                                                                                                        ✅                                                                                                                                         |                                                        ✅                                                        |
|                                     Data Analytics Dashboard                                      |                                                       ❌                                                        |                                                                                                                                        ✅                                                                                                                                         |                                                        ✅                                                        |
|                                  Min Value / Max Engagement Tips                                  |                                                       ❌                                                        |                                                                                                                                        ✅                                                                                                                                         |                                                        ✅                                                        |
|                                   Optimal Rewards Data Insight                                    |                                                       ✅                                                        |                                                                                                                                        ✅                                                                                                                                         |                                                        ✅                                                        |
|                                Advanced Data Insights<sup>3</sup>                                 |                                                       ❌                                                        |                                                                                                                                        ❌                                                                                                                                         |                                                        ✅                                                        |
|                                                                                                   |            <button name="button" onclick="Fix after HTML Conversion (above)">Get Standard</button>             |                                                                                                <button name="button" onclick="Fix after HTML Conversion (above)">Get Pro</button>                                                                                                |              <button name="button" onclick="Fix after HTML Conversion (above)">Contact Us</button>              |

<sup>*</sup>**Use It or Lose It for Standard & Pro Plans** <br>
Your subscription gives you FynCom credit to use as Rewards each month, inclusive of commission. No roll overs.

<sup>1</sup>**Rewards Campaigns** <br>
The number of active Rewards Campaigns your plan can have at a time.

<sup>2</sup>**Commission** <br>
The commission is based on reward size and is only paid to FynCom when a response is received or desired action completed. <br>
Here is an example for Standard plans. <br>
You create a Rewards Campaign of $1.00 and attach it to a Calendly booking so that anyone who books get rewarded. <br>
- jamie@bestFakeCompany.com books an event.
- $1.15 total is deducted from your Account Balance.
- Jamie instantly receives $1.00 from your Account Balance and is notified by email.
  - FynCom receives $0.15 from your Account Balance. 
  - Jamie is not charged any fees to withdraw funds or purchase gift cards.

Here is the same sample for all plans. <br>

|                                           |       |       |        |
|-------------------------------------------|-------|-------|--------|
| Reward To Recipient                       | $1.00 | $1.00 | $1.00  |
| Commission to FynCom                      | $0.30 | $0.15 | $0.05  |
| Amount deducted from your FynCom balance  | $1.30 | $1.15 | $1.05  |


<sup>3</sup>**Advanced Data Insights** <br>
Be the first to know the optimal rewards sizes to deliver to certain demographics and at which point of the journey to deliver said rewards.




[//]: # Note, you wll have to add this yourself into the HTML. Markdown to HTML converter does not do this for you. <- this seems false now? IDK()
<style>
        th {
            border-right:hidden!important;
            border-left:hidden!important;
            border-top:hidden!important;
            width: 23%;
        }
        th:first-child {
            width: 31%;
        }
        tr {
            border-left:3px solid black;
        }
        table td:first-child {
            font-size: 22px;
            font-weight: bold;
        }
        table td {
            font-size: 24px;
        }
        table.small {
            /* table-layout: auto; */
            width: 600px;
            white-space:nowrap;
            max-width:100%;
        }
        table.small td:first-child {
            font-size: 14px;
            font-weight: bold;
            width: 31%;
        }
        table.small td {
            font-size: 12px;
        }
        button {
            font-size: 24px;
        }
        p {
            font-size: 12px;
        }
        strong {
            font-size: 16px;
        }
        h1 {
            font-size: 36px;
        }
</style>
