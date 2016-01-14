#Pay with Amazon Theme Integration for Mozu Core8#

This repository is a branch of the PayWithAmazon-Theme repository, provided for backwards-compatibility. This repository contains the full source files for the Mozu [Core8](https://github.com/Mozu/core-theme/tree/core8) theme, with the required changes to enable Pay with Amazon on your Mozu storefront. These theme changes support the Pay with Amazon Application by Mozu. Go to the [Mozu App Marketplace](https://www.mozu.com/marketplace/) to learn more about the app and to request installation on your tenant. 

**Note:** This repo is NOT using the latest version of the Mozu Core theme. If you want to update your Mozu theme to match the latest Core, go to the master PayWithAmazon-Theme repository.

##File Additions and Changes##

**Note:** Use GitHub’s [Compare Changes](https://help.github.com/articles/comparing-commits-across-time/) functionality to see full diffs of the following files.

The Pay with Amazon Integration adds the following files:
* `resources/images/amazonpay60x38.png`
* `scripts/modules/amazonpay.js`
* `scripts/modules/eventbus.js`
* `scripts/modules/models-amazoncheckout.js`
* `scripts/pages/amazon-checkout.js`
* `templates/modules/checkout/amazon-shipping-billing.hypr.live`
* `templates/modules/checkout/payment-paybyamazon.hypr.live`
* `templates/pages/amazon-checkout.hypr`

And edits the following files:
* `labels/en-US.json`
* `scripts/pages/cart.js`
*	`scripts/pages/checkout.js`
*	`scripts/pages/location.js`
*	`scripts/pages/product.js`
*	`stylesheets/modules/cart/cart-table.less`
*	`stylesheets/modules/common/form-step.less`
*	`stylesheets/pages/checkout.less`
*	`templates/back-office/packing-slip.hypr`
*  `templates/email/order-confirmation.hypr`
*	`templates/email/order-refund-issued.hypr`
*	`templates/modules/cart/cart-table.hypr.live`
*	`templates/modules/checkout/checkout-payment.hypr.live`
*	`templates/modules/checkout/payment-selector.hypr.live`
*	`templates/modules/checkout/step-payment-info.hypr.live`
*	`templates/modules/checkout/step-shipping-address.hypr.live`
*	`templates/modules/page-header/utility-nav.hypr`
*	`templates/pages/checkout.hypr`
*	`package.json`
*	`theme.json`



##Additional Resources

* [Pay with Amazon Application by Mozu Configuration Guide](https://www.mozu.com/docs/guides/mozu-apps/pay-with-amazon-app-by-mozu.htm)*
* [Introduction to Mozu Themes](https://www.mozu.com/docs/developer/themes/introduction.htm)
* [Mozu Theme Generator 2.0](https://www.npmjs.com/package/generator-mozu-theme) (npm Package)

**Note:** You must log in with your Mozu Developer Account credentials to access content at [https://www.mozu.com/docs/guides](https://www.mozu.com/docs/guides/guides.htm)
