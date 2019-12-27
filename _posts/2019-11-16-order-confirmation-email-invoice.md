---
layout: post
title:  "Add a link to the invoice in Order Confirmation Email"
---

When a customer places an order on your store, Shopify sends an email, called the _Order Confirmation_ email, that informs the customer about their order. This email includes a link to the order, products purchased & their quantities, shipping & billing addresses and the payment method used.

With Invoice Printer Pro, you can place a link to the invoice for their order in this email. When customers click on this link, they will be redirected to a PDF invoice that they can choose to print or download to their device.

<br/>

<img src='/assets/img/order-confirmed.png' width='50%'/>

<br/>

To add this link to your Order Confirmation Email, you will need to add a tiny snippet of code to your Order Confirmation Email Template.

1. In your Shopify admin dashboard, click __Settings__ -> __Notifications__
2. Here, click on the __Order Confirmed__ notification. You will be directed to a page that lets you edit the the template.
3. Open this video guide to find out where exactly you should paste the snippet of code - [Video Guide](https://www.youtube.com/watch?v=QxK2zmv671U)
4. Finally, copy and paste this code to the template -

`<!-- Invoice Printer Pro Email Code START --><table class='container' style='margin-bottom:25px'><tr><td><h4><a href='https://app.invoicefalcon.com/pdfs/{{ "{{ id " }}}}.pdf?shopify_domain=invoicefalconstore.myshopify.com'>Download Invoice</a></h4></td></tr></table><!-- Invoice Printer Pro Email Code END -->`

Note - _Replace 'invoicefalconstore.myshopify.com' with your store's myshopify link._

Click _Save_ and that's it! Your Order Confirmation email will now include a link to the invoice of that order. :)