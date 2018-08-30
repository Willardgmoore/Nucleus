.. _selling_your_product:

Selling your product
==================================================

You can use Crowdsourcer.io to make sales of the products you make in a project, or even to receive donations from people who want to help out financially. All the money you earn, whether that's from sales, donations or external sources, gets distributed evenly between all contributors. For more information on how money gets split between everyone, see the :ref:`payout_policy`.

To sell your product :ref:`via the Platform or using Widgets <sell_through_csio>` costs |shopRate| on each sale. Using the :ref:`Payroll feature  <sell_through_third_party>` costs |payRate|. These numbers are subject to change and this documentation can quickly become out of date. For a live and up-to-date rate, check the `Support page <https://crowdsourcer.io/support>`_.

How to start selling
--------------------

Once your project has reached 20 C.Pts you'll notice a small notification on the sidebar (if you're the project creator). After clicking the link you'll be taken to a page where you'll be asked to detail the products you're going to sell and how you're going to sell them. Please be as informative as possible as it will help to ensure your application to start selling is accepted quickly. It should not take more than 48 hours before you're accepted, but if you don't receive an email alerting you to this, feel free to resend the form. If there are issues preventing us from enabling sales in your project we'll reach out to you either via the email address you used to register your account or via your project's chat.

Creating products
-----------------

Once your project has been enabled for sales you may start creating products. Products can be sold on Crowdsourcer.io or through your own site using Widgets (Detailed below). When sold through Crowdsourcer.io, products show up on your project page after they're approved and can be purchased by customers directly on the platform. If, however, you don't want to sell you products on the site, you may disable them from being sold by Crowdsourcer.io, limiting you to sales via Widgets.

Products go through a few stages:

- Creating: Where you set up your product.
- Review: After submitting your product it'll be reviewed by Crowdsourcer.io staff.
- Live: Once approved your product can start to be sold!

In the review stage please note that you can not modify your product, so if you forgot something, please contact us via https://crowdsourcer.io/contact-us. Once your product is live any changes made have to be reviewed and until changes are approved, the original version will still be in effect. For instance, if you change the name from "My Product" to "My Product v2", until the change is reviewed, your customers will still see "My Product".

.. note:: Using products to make sales either on the Crowdsourcer.io platform, or via widgets on your own site will incur a fee of |shopRate|. This is subject to change and this documentation can quickly become out of date. For a live and up-to-date rate, check the `Support page <https://crowdsourcer.io/support>`_.

.. _create_serial_keys:

Serial Keys
____________

If you're selling a product hosted on another platform (like a game on Steam or an App on a store), or your product needs to be registered with a license before all the features can be unlocked, then using the Serial Key product is a good way to go. All you need is at least 10 exported or generated Keys for your software, ready to upload. 

To create a Serial Key product go to "Store Manager" from your project's :ref:`mission_control` and press "Add New Product". Ensure "Serial Key" is selected from the "Product Type" section and fill out the information. On submission you must have uploaded at least 10 serial keys. If your stock of keys ever drops below 10 we'll send a stock warning to your email address.

.. _create_digital_downloads:

Digital Downloads
__________________

Digital downloads are a great way of distributing `DRM <https://en.wikipedia.org/wiki/Digital_rights_management>`_-free downloads. For instance, if you're selling a digital comic book, an album or a small game, then this could be the product type for you. Currently we're limiting the size of files that can be uploaded (currently 500MB but check the site for up-to-date figures) due to technical limitations in our virus scanning - but we hope to have this increased with time. If your product exceeds this, consider using a third party provider to host your product and use Serial Keys (above) to distribute the content.

To create a *Digital Download* go to the "Store Manager" in your :ref:`mission_control` and press "Add New Product". Ensure "Digital Download" is selected from the "Product Type" section and fill out the information. You'll need to have uploaded a single file (that will become your download product) before you can submit your product to review. Please note that for obvious reasons a file that fails our virus scan will fail review.

.. _create_donations:

Donations
___________

The final product type currently available is simply a donation product. These allow you to receive money for no product, great if you're working on Open Source software or similar. Donations don't require any specific preparation as with the other product types, so all you need to do is set a price, give it a name, and decide whether or not you want to hide it from Crowdsourcer.io website (meaning you can only make sales through the widget - see below).

To add a *Donation* press "Add New Product" from the "Store Manager" in your :ref:`mission_control`. Ensure "Donation" is selected from the "Product Type" section and fill out the remaining information.

.. _using_widgets:

Using Widgets
-------------

Widgets are a great way of selling products through your own website. To create a widget head to the "Store Manager" in your :ref:`mission_control`. If you want a branded checkout and emails for your customers, click "Receipt and Checkout branding" and upload the relevant logos and colour schemes. Next, click on a product for which you'd like to make a widget and press "Create Widget". You'll be redirected to the *Widget builder* where you can customise and ultimately generate the code for your widgets to be embedded on your site.

The widget flow is simple:

1. Embed "Buy now" and/or "Add to Cart" buttons on your site.
2. Customer clicks buttons on your site.
3. Customer is redirected to an optionally branded and whitelabelled Checkout page on Crowdsourcer.io.
4. Confirmation and product redemption emails (optionally branded) are sent to the customer.
5. Customer is redirected back to your site.

When the sale is complete, a redirect is sent with a URL parameter of "csioStatus", set to either "success", "failed" or "aborted" so you can appropriately handle the result of the purchase. E.g. my-website.com/my/destination/url?csioStatus=success. You can set up a specific URL to redirect to when you create the widget. If none is added, the customer will be redirected back to the last page they were on.

.. note:: Please note that if you embed an "Add to Cart" button, you must also embed the "Cart dropdown". The Cart dropdown may require tweaking to make it work well with your theme but don't change the overall structure or IDs of elements as it may fail to function correctly. The dropdown uses an embedded version of `Bootstrap <https://getbootstrap.com>`_ that should not interfere with your own Bootstrap integration.

.. _running_payroll:

Running Payroll
---------------

If Crowdsourcer.io can't provide the right product for you, or if you can only sell your product on a third party store (such as an App on the iOS App Store), what do you do then? Easy, all you have to do is run your profits through the Payroll system. All this does is allows you (the creator of a project) to pay into the project and distribute those earnings to *both* you and and all your fellow contributors - meaning you shouldn't take a cut before paying in as you too will be paid by the payroll algorithm. For more information on how money will be split, see the :ref:`payout_policy`.

To run Payroll:

1. Go to the "Sales" page in your :ref:`mission_control`.
2. Click "Earned money outside of Crowdsourcer.io?" and enter an amount greater than $20.
3. Click "Run Payroll".
4. Confirm the information on the confirmation page and fill in your payment information after pressing "Pay with card".
5. You should be redirected back to the Sales page and should receive an email receipt with the amount you paid.

.. note:: Using the Payroll feature to pay yourself and contributors in the project will incur a fee of |payRate|. This is subject to change and this documentation can quickly become out of date. For a live and up-to-date rate, check the `Support page <https://crowdsourcer.io/support>`_.

.. warning:: You are required by the Terms and Conditions of the platform to pay you and your fellow contributors any profits earned outside of the site, through the Payroll system. When a contributor (or project creator) contributes to a project, they do not relinquish their Intellectual Property rights and instead allow the project to use that IP to generate an income, provided that income is paid through the Payroll system. When such a time comes as to be able to log expenses in the Crowdsourcer.io platform, then all externally acquired *revenue* must be paid in via the Payroll system. For more information please see Crowdsourcer.io's `Terms and Conditions <https://crowdsourcer.io/terms>`_.

.. _creator_obligations:

Creator Obligations
---------------------------

As a creator of a project, you're required to pay yourself and your fellow contributors using the Payroll feature when sales are made outside of the Crowdsourcer.io platform. As you do not own the copyrights of the work fellow contributors have put into your project, to comply with international copyright/IP laws, you are required to pay them. Under the Terms and Conditions that you've agreed to when using Crowdsourcer.io, this remuneration *must* be performed using the Payroll system. For further information, please see the `Terms and Conditions <https://crowdsourcer.io/terms>`_.

It is also your responsibility to ensure any activities are performed legally in your country of residence. This includes ensuring correct levels of taxation are paid, company registration is completed (if required) and any other specific, relevant and domestic laws are complied with.