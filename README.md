# WooCommerce XRP

A payment gateway for WooCommerce to easily accept [XRP](https://ripple.com/xrp) as a payment method.

## Requirements

* PHP 7.0+ (it *might* work with PHP 5.6, but not tested)
* WordPress 5.1+
* WooCommerce 3.5.6+
* You need to have [cURL](https://curl.haxx.se) installed.
* You need an account at [XRPL Webhook](https://webhook.xrpayments.co) (see blow)

## Installing

* Grab the [latest version](https://github.com/empatogen/woocommerce-xrp/archive/master.zip) of the plugin and unzip it in your /wp-content/plugins directory.
* Go to your _Settings > Plugins_ page and **activate** the plugin.
* Create a free account at [XRPL Webhook](https://webhook.xrpayments.co) and obtain your **API keys**. This is required as the plugin uses this webhook to update the checkout page whenever a payment is made.
* Go to _WooCommerce > Settings > Payments_ and configure the XRP payment gateway.


## License

Please see [LICENSE](https://github.com/empatogen/woocommerce-xrp/blob/master/LICENSE).

## Acknowledgments

* A huge thank you to both [Ripple](https://ripple.com/) and [XRPL Labs](https://xrpl-labs.com/) for being awesome!
* Thanks to [Chronos Ananké](https://twitter.com/AnankeChronos) for helping out with translation! (French)
* Thanks to **everyone** who helped out testing! Plenty of bugs got nailed and lots of new features added.
