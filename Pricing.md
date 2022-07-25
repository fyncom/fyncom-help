#Notes - Convert to HTML, then delete everything before style tags.
Export as HTML and then modify html to use `colspan="3"` in the `<td>` of last 2 rows
```
<td colspan="3" align="center" md-src-pos="680..730">Zapier, Sendgrid, SlickText &amp; FynCom API Key</td>
<td colspan="3" align="center" md-src-pos="755..805">Sales (Simple), Marketing, Basic</td>
```
Redirecting the window requires controlling the parent. Use `onclick="window.parent.location.href='link';"` to send to new page. Nothing else works except this.
```
<td align="center" md-src-pos="6581..6794"><button name="button" onclick="window.parent.location.href='https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=basic-USD-Monthly&amp;subscription_items[quantity][0]=1';">Get Basic</button></td>
<td align="center" md-src-pos="6992..7188"><button name="button" onclick="window.parent.location.href='https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=premium-USD-Monthly&amp;subscription_items[quantity][0]=1';">Get Premium</button></td>
<td align="center" md-src-pos="6795..6991"><button name="button" onclick="window.parent.location.href='https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=standard-USD-Monthly&amp;subscription_items[quantity][0]=1';">Get Standard</button></td>
```

Table borders, put this in td
```
border:none;
```

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

# Pricing
The full value of your monthly subscription is usable for Rewards. Any remaining balance does not roll over at the end of the month.
_You may top up your account funds over your monthly price at any point. Those funds stay in your FynCom account and DO roll over on a month per month basis._

| ![Pricing](https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Graphic+A1.png) |                                                        ![Basic Pricing](https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Basic+A2.png)                                                        |                                             ![Standard Pricing](https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Standard+A3.png)                                              |                                             ![Premium Pricing](https://fyncom-static-files.s3.us-west-1.amazonaws.com/pricing/Pricing+Premium+A4.png)                                              |
|:-------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|                                          Number of users                                          |                                                                                                          3                                                                                                          |                                                                                                  10                                                                                                  |                                                                                              No limit                                                                                              |
|                                 Rewards Transactions<sup>1</sup>                                  |                                                                                                       10,000                                                                                                        |                                                                                               100,000                                                                                                |                                                                                             Unlimited                                                                                              |
|                                   Rewards Campaigns<sup>2</sup>                                   |                                                                                                          3                                                                                                          |                                                                                              Unlimited                                                                                               |                                                                                             Unlimited                                                                                              |
|                                    Commission (%)<sup>3</sup>                                     |                                                                                                         15                                                                                                          |                                                                                                  10                                                                                                  |                                                                                                 5                                                                                                  |
|                                        Support Speed (Hrs)                                        |                                                                                                         72                                                                                                          |                                                                                                  48                                                                                                  |                                                                                                 12                                                                                                 |
|                                           Integrations                                            |                                                                                    Zapier, Sendgrid, SlickText & FynCom API Key                                                                                     |
|                                          Email Products                                           |                                              Sales (Simple), Marketing, Basic                                                                                                                                       |
|                                                                                                   | <button name="button" onclick="https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=basic-USD-Monthly&subscription_items[quantity][0]=1"  formtarget="_blank">Get Basic</button> | <button name="button" onclick="https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=standard-USD-Monthly&subscription_items[quantity][0]=1">Get Standard</button> | <button name="button" onclick="https://fyncom.chargebee.com/hosted_pages/checkout?subscription_items[item_price_id][0]=premium-USD-Monthly&subscription_items[quantity][0]=1">Get Premium</button> |


**Rewards Transactions**<sup>1</sup> <br>
Number of rewards you can send in a month.

**Rewards Campaigns**<sup>2</sup> <br>
Number of active rewards campaign per month.

**Commission**<sup>3</sup> <br>
The commission paid to FynCom per reward. If a response is received for a reward is $1.00, then $1.05 to $1.15 is charged, based on your plan.
