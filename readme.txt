=== Enhanced Paypal Shortcodes ===

Contributors: CharlyLeetham
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=DXBKBP7Q5FSGC
Tags: paypal, shortcode, buy now, subscribe
Requires at least: 2.8
Tested up to: 2.9.2
Stable tag: trunk

Description:  Easily embed a fully functional paypal buy now, subscribe or hosted button using shortcodes. Supports Wishlist Member

== Description ==

This program is distributed in the hope that it will be useful,
You should have received a copy of the GNU General Public License
== Installation ==
1. Install Enhanced Paypal Shortcodes from the Wordpress Repository
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Place [paypal type="paynow" amount="12.99" email="payments@arvoreentreasures.com" item_no="12345657" name="Description" no_shipping="1" no_note="1" currency_code="USD" imageurl="https://www.paypal.com/en_US/i/btn/btn_paynowCC_LG.gif" rm="2" notifyurl="http://notifyurl.com" notifyurl2="http://notifyurl.com" returnurl="http://returnurl.com" scriptcode="scriptcode" imagewidth="100px"]
== Frequently Asked Questions ==
Parameters for Shortcode for all Paypal buttons
imagewidth = the width of the paypal image
name = Description of product / service
noshipping = Prompt for Shipping address
nonote = Prompt payers to include a note (Paynow buttons only)
currencycode = The currency for the transaction
rm = The return method. This will only work if returnurl is also set. This variable is often required by membership type software
notifyurl = The URL to send payment advice too. Often required for IPN or other notifications
returnurl = The URL to which the payer’s browser is redirected after completing the payment; for example, a URL on your site that displays a “Thank you for your payment” page.
scriptcode = the link to any script code that you may need to include.  e.g For Jrox JAM, some script code is added to the paypal buttons. Usage /foldername/scriptcode.php
Paynow Button only parameters
Subscribe Button only parameters
Trial Period 1:
D for Days, allowable entries for p1: 1 to 90
Trial Period 2:
D for Days, allowable entries for p2: 1 to 90
The full subscription Payment:
D for Days, allowable entries for p3: 1 to 90
sra = Reattempt on failure. If a recurring payment fails, PayPal attempts to collect the payment two more times before canceling the subscription.
textalign = the alignment of the image / text within the div
float = position of the div on the page
marginleft = the amount of space between the div and the text to the left of the div (particularly good to use when using float=right)
marginright = the amount of space between the div and the text to the right of the div
marginbottom = the amount of space to the line below the div
Subscribe Button with 2 trial periods and recurring Monthly payments.
Hosted Button
Adding formatting to Hosted Button
All formatting options work on three button types.
== Screenshots ==
None
== Changelog ==
0.1 - Initial release
== Upgrade Notice ==