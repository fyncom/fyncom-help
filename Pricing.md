#Notes1 - Convert to HTML, then delete everything before style tags.

#Notes2 - delete everything between </head and Pricing, but leave the <body tag. Not sure what the above means... but Notes1 allowed visible widgets mobile. This one doesn't.
Export as HTML and then modify html to use `colspan="3"` in the `<td>` of last 2 rows

```
<td colspan="4" align="center" md-src-pos="7361..7460">User Experience When Receiving Rewards + Cashing Out</td>
<td colspan="4" align="center" md-src-pos="10439..10538">Ways You Can Reward Responses (Reward Integrations)</td>
<td colspan="4" align="center" md-src-pos="17981..18080">Developer Tools</td>
<td colspan="4" align="center" md-src-pos="18827..18926">Admin Tools</td>

Delete the empty columns that get created in each row that has a "full row" text
```

~~Redirecting the window requires controlling the parent. Use `onclick="window.parent.location.href='link';"` to send to new page. Nothing else works except this.~~
Redirecting the window requires controlling the parent. Use `onclick="window.open('url'), 'target=_blank', 'rel=noopener noreferrer';"` to send to new tab. <br>
You will also want to update the Zapier href links with this (see Integrations row) `target="=_blank", rel="noopener noreferrer"`


```
[//]: # (<td align="center" md-src-pos="6581..6794"><button name="button" onclick="window.open&#40;'https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=basic-USD-Monthly&amp;subscription_items[quantity][0]=1'&#41;, 'target=_blank', 'rel=noopener noreferrer';">Get Basic</button></td>)

TURNS IMAGES INTO LINKS FOR THE TOP IMAGES - After converting from MD to HTML - replace the table headers with this.
  <th align="center" md-src-pos="2253..2453"><img src="https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Standard+A2_50.png" alt="Standard Pricing" __idea-generated="true" md-src-pos="2298..2408" onMouseOver="this.style.cursor='pointer'" onclick="window.open('https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=standard-USD-Monthly&amp;subscription_items[quantity][0]=1'), 'target=_blank', 'rel=noopener noreferrer';"></th>
  <th align="center" md-src-pos="2454..2697"><img src="https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Pro+A3_.png" alt="Pro Pricing" __idea-generated="true" md-src-pos="2456..2554" onMouseOver="this.style.cursor='pointer'" onclick="window.open('https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=pro-USD-Monthly&amp;subscription_items[quantity][0]=1'), 'target=_blank', 'rel=noopener noreferrer';"></th>
  <th align="center" md-src-pos="2698..2894"><img src="https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Enterprise+A4.png" alt="Enterprise Pricing" __idea-generated="true" md-src-pos="2740..2851" onMouseOver="this.style.cursor='pointer'" onclick="window.open('https://www.fyncom.com/contact'), 'target=_blank';"></th>

FOR THE BUTTONS IN THE LAST CELL
    <td align="center" md-src-pos="6795..6991"><button name="button" style="background-color:#4A90E2;color:white" onMouseOver="this.style.cursor='pointer'" onclick="window.open('https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=standard-USD-Monthly&amp;subscription_items[quantity][0]=1'), 'target=_blank', 'rel=noopener noreferrer';">Get Standard</button></td>
    <td align="center" md-src-pos="6795..6991"><button name="button" style="background-color:#4A90E2;color:white" onMouseOver="this.style.cursor='pointer'" onclick="window.open('https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=pro-USD-Monthly&amp;subscription_items[quantity][0]=1'), 'target=_blank', 'rel=noopener noreferrer';">Get Pro</button></td>
    <td align="center" md-src-pos="6992..7188"><button name="button" style="background-color:#4A90E2;color:white" onMouseOver="this.style.cursor='pointer'" onclick="window.open('https://www.fyncom.com/contact'), 'target=_blank';">Contact Us</button></td>
```


[//]: # (You will want to manually add links into the HTML later too.)

# Pricing
Up to $50 of your monthly subscription is usable for Rewards. Subscription does not roll over at the end of the month. Account top-ups roll over indefinitely.

| ![Pricing](https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Graphic+A1.png) | ![Standard Pricing](https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Standard+A2_50.png) |                 [![Pro Pricing](https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Pro+A3_.png)]("https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=pro-USD-Monthly&subscription_items[quantity][0]=1)                 | ![Enterprise Pricing](https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Enterprise+A4.png) |
|:-------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------:|
|                                   "Use It or Lose It" Credits*                                    |                                                      $50                                                       |                                                                                                                                       $50                                                                                                                                        |                                                     Custom                                                      |
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
|                                    Advanced Data Insights****                                     |                                                       ❌                                                        |                                                                                                                                        ❌                                                                                                                                         |                                                        ✅                                                        |
|                                                                                                   |            <button name="button" onclick="Fix after HTML Conversion (above)">Get Standard</button>             |                                                                                                <button name="button" onclick="Fix after HTML Conversion (above)">Get Pro</button>                                                                                                |              <button name="button" onclick="Fix after HTML Conversion (above)">Contact Us</button>              |

<sup>*</sup>**Use It or Lose It for Standard & Pro Plans** <br>
Your subscription gives you $50 of FynCom credit to use as Rewards each month. Credits are subject to commission and do not roll over.
Remaining Credits can be automated to be delivered as a lottery to a list of customer emails or even employee emails!

<sup>1</sup>**Rewards Campaigns** <br>
The number of active Rewards Campaigns your plan can have at a time.

<sup>2</sup>**Commission** <br>
The commission is based on reward size and is only paid to FynCom when a response is received or desired action completed. 
Here is an example for Standard plans. You create a Rewards Campaign of $1.00 and attach it to a Calendly booking so that anyone who books get rewarded. jamie@bestFakeCompany.com books an event.
Jamie instantly receives $1.00 from your Account Balance and is notified by email.
FynCom receives $0.15 from your Account Balance. 
$1.15 total is deducted from your Account Balance.
Jamie is not charged any fees to withdraw funds or purchase gift cards.

_*If you send out more rewards than your monthly subscription (example, you have a $100 subscription and want to send $110), you may add funds to your account
in the wallet page at any point. Those excess funds stay in your FynCom account and will roll over on a month-to-month basis._

[//]: # Note, you wll have to add this yourself into the HTML. Markdown to HTML converter does not do this for you.()
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
        button {
            font-size: 24px;
        }
        p {
            font-size: 18px;
        }
        strong {
            font-size: 26px;
        }
        h1 {
            font-size: 36px;
        }
</style>
