---
title: Magento 2.4.0: 404 error removing rewards points on multi-shipping checkout
link: https://support.magento.com/hc/en-us/articles/360046920131-Magento-2-4-0-404-error-removing-rewards-points-on-multi-shipping-checkout
labels: Magento Commerce Cloud,Magento Commerce,checkout,known issues,multishipping,404 error,2.4.0,shopping cart,rewards points
---

This article provides a workaround for a known issue in Magento 2.4.0 for a "*404 Not Found*" web page error when removing rewards points on a multi-shipping checkout page. Currently, on the multi-shipping checkout page, when trying to remove reward points which were used to pay for an order,  a "*404 Not Found*" page is displayed instead of successful reward points cancellation. This issue will be resolved in with a Magento 2.4.1 patch release.

## Affected products and versions

* Magento Commerce version 2.4.0

* Magento Commerce Cloud version 2.4.0

## Issue

Steps to reproduce

1. Navigate to the storefront and login as a customer.

1. Add at least 2 products to the **Shopping Cart**.

1. Open the **Mini-Cart**.

1. Click the **View and Edit Cart** link.

10. Click the **Check Out with Multiple Addresses** link.

12. Select shipping addresses on the **Ship to Multiple Addresses** page.

14. Click the **Go to Shipping Information** button.

16. Select the **Flat Rate — Fixed Shipping Method** for each address.

18. Click the **Continue to Billing Information** button.

20. Check the **Use Your Reward Points** checkbox on the **Billing Information** page.

22. Click the **Go to Review Your Order** button.

24. Click the **Remove** link for any address to remove the reward points.

Expected results

* The **Shopping Cart** page should appear.

* The “*You removed the reward points from this order.*” message should appear.

Actual result

A "*404 Not Found*” error page appears.

## Workaround

The workaround is to have the buyer navigate back to the **Cart** and remove the reward points from the **Cart** web page. The issue is expected to be fixed in the Magento version 2.4.1 patch, which is scheduled for release in Q4 2020.

## Related reading

* [Magento 2.4.0 known issue - refresh on Customer's Activities does not work](https://support.magento.com/hc/en-us/articles/360046091332)

* [Magento 2.4.0 Known Issue: Raw message data display on Storefront](https://support.magento.com/hc/en-us/articles/360045804332)

* [Magento 2.4.0 Known Issue: Export Tax Rates does not work](https://support.magento.com/hc/en-us/articles/360045850032)

* [Magento 2.4.0 B2B Admin can't add configurable product to quote](https://support.magento.com/hc/en-us/articles/360046801971)

* [Magento 2.4.0 known issue: Orders display error](https://support.magento.com/hc/en-us/articles/360046802271)
