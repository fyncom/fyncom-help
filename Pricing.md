#Notes - Convert to HTML, then delete everything before style tags.
Export as HTML and then modify html to use `colspan="3"` in the `<td>` of last 2 rows

```
<td colspan="3" align="center" md-src-pos="680..730">Zapier, Sendgrid, SlickText &amp; FynCom API Key</td>
<td colspan="3" align="center" md-src-pos="755..805">Sales (Simple), Marketing, Basic</td>
```

~~Redirecting the window requires controlling the parent. Use `onclick="window.parent.location.href='link';"` to send to new page. Nothing else works except this.~~
Redirecting the window requires controlling the parent. Use `onclick="window.open('url'), 'target=_blank', 'rel=noopener noreferrer';"` to send to new tab. <br>
You will also want to update the Zapier href links with this (see Integrations row) `target="=_blank", rel="noopener noreferrer"`


```
<td align="center" md-src-pos="6581..6794"><button name="button" onclick="window.open('https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=basic-USD-Monthly&amp;subscription_items[quantity][0]=1'), 'target=_blank', 'rel=noopener noreferrer';">Get Basic</button></td>
<td align="center" md-src-pos="6795..6991"><button name="button" onclick="window.open('https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=standard-USD-Monthly&amp;subscription_items[quantity][0]=1'), 'target=_blank', 'rel=noopener noreferrer';">Get Standard</button></td>
<td align="center" md-src-pos="6992..7188"><button name="button" onclick="window.open('https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=premium-USD-Monthly&amp;subscription_items[quantity][0]=1'), 'target=_blank', 'rel=noopener noreferrer';">Get Premium</button></td>
```


# Pricing
The full value of your monthly subscription is usable for Rewards. Any remaining balance does not roll over at the end of the month. <br>
_If you send out more rewards than your monthly subscription (example, you have a $100 subscription and want to send $110), you may add funds to your account
in the wallet page at any point. Those excess funds stay in your FynCom account and will roll over on a month-to-month basis._

| ![Pricing](https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Graphic+A1.png) |                                                                                                  ![Basic Pricing](https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Basic+A2.png)                                                                                                   |                                             ![Standard Pricing](https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Standard+A3.png)                                              |                                             ![Premium Pricing](https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Premium+A4.png)                                              |
|:-------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|                                          Number of users                                          |                                                                                                                                                    3                                                                                                                                                     |                                                                                                  10                                                                                                  |                                                                                              No limit                                                                                              |
|                                 Rewards Transactions<sup>1</sup>                                  |                                                                                                                                                  10,000                                                                                                                                                  |                                                                                               100,000                                                                                                |                                                                                             Unlimited                                                                                              |
|                                   Rewards Campaigns<sup>2</sup>                                   |                                                                                                                                                    3                                                                                                                                                     |                                                                                              Unlimited                                                                                               |                                                                                             Unlimited                                                                                              |
|                                    Commission (%)<sup>3</sup>                                     |                                                                                                                                                    15                                                                                                                                                    |                                                                                                  10                                                                                                  |                                                                                                 5                                                                                                  |
|                                        Support Speed (Hrs)                                        |                                                                                                                                                    72                                                                                                                                                    |                                                                                                  48                                                                                                  |                                                                                                 12                                                                                                 |
|                                           Integrations                                            | Zapier ([Google Forms](https://zapier.com/shared/6ec3d6005364fc5735a80342fbc878376556d22f), [Calendly](https://zapier.com/shared/d3b8c380ec3e92855d6160075e243e4fc0cab081), [Typeform](https://zapier.com/shared/5605b1ceffcf3fe14d5cdd91717847590d849841) & more), Sendgrid, SlickText & FynCom API Key |
|                                          Email Products                                           |                                                                                                                                     Sales (Simple), Marketing, Basic                                                                                                                                     |
|                                            API Access                                             |                                                                                                                                    &#x2717;                                                                                                                               | &#10004;| &#10004;|
|                                           Custom Builds                                           |                                                                                                                                                   &#x2717;                                                                                                                                                  |&#x2717;|                                                                                        &#10004;                                                                                   |
|                                      Call Rewards - FynCalls                                      |                                                                                                                                                   &#x2717;                                                                                                                                                  |&#x2717;|                                                                                        &#10004;                                                                                   |
|                                                                                                   |                                           <button name="button" onclick="https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=basic-USD-Monthly&subscription_items[quantity][0]=1"  formtarget="_blank">Get Basic</button>                                            | <button name="button" onclick="https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=standard-USD-Monthly&subscription_items[quantity][0]=1">Get Standard</button> | <button name="button" onclick="https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=premium-USD-Monthly&subscription_items[quantity][0]=1">Get Premium</button> |

**Rewards Transactions**<sup>1</sup> <br>
Number of rewards you can send in a month.

**Rewards Campaigns**<sup>2</sup> <br>
Number of active rewards campaign per month.

**Commission**<sup>3</sup> <br>
The commission paid to FynCom per reward. If a response is received for a reward is $1.00, then $1.05 to $1.15 is charged, based on your plan.

[//]: # Note, you wll have to add this yourself into the HTML. Markdown to HTML converter does not do this for you.()
<style>
 th {
     border-right:hidden!important;
     border-left:hidden!important;
     border-top:hidden!important;
 }
 tr {
    border-left:3px solid black;
 }
</style>
