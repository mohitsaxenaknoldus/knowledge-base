---
title: "MDVA-36615: catalog products grid filter incorrect results"
labels: 2.4.2,QPT 1.0.21,QPT patches,Magento Commerce,Magento Commerce Cloud,Product Grid,catalog,configurable product,search,support tools
---

The MDVA-36615 Magento patch fixes the issue with incorrect product count in the admin product grid. This patch is available when the [Quality Patches Tool (QPT)](https://support.magento.com/hc/en-us/articles/360047139492) 1.0.21 is installed. The patch ID is MDVA-36615. Please note that the issue is scheduled to be fixed in Magento 2.4.3.

## Affected products and versions

 **The patch is created for Magento version:** Magento Commerce Cloud 2.4.2

 **Compatible with Magento versions:** Magento Commerce and Magento Commerce Cloud 2.4.2

>![info]
>
>Note: the patch might become applicable to other versions with new QPT tool releases. To check if the patch is compatible with your Magento version, run `./vendor/bin/magento-patches status` .

## Issue

Incorrect product count in the admin product grid.

 <span class="wysiwyg-underline">Steps to reproduce:</span> 

1. Create simple and configurable products with the same phrase in the name (e.g. "red shirt" / "red shirt xs").
1. On the *Admin* sidebar, go to **Catalog** > **Products** > search for this phrase.
1. Click **Filters** . Set Type to *Configurable Product* .
1. Click **Apply Filters** .

 <span class="wysiwyg-underline">Actual result:</span> 

Correct number in matched product counter.

 <span class="wysiwyg-underline">Expected result:</span> 

Incorrect number in matched product counter.

## Apply the patch

For instructions on how to apply an QPT patch, use the following links depending on your Magento product:

* Magento Commerce: DevDocs [Apply patches using Quality Patches Tool](https://devdocs.magento.com/guides/v2.4/comp-mgr/patching/mqp.html) .
* Magento Commerce Cloud: DevDocs [Upgrades and Patches > Apply patches](https://devdocs.magento.com/cloud/project/project-patch.html) .

## Related reading

To learn more about Quality Patches Tool, refer to:

* [Quality Patches Tool released: a new tool to self-serve quality patches](https://support.magento.com/hc/en-us/articles/360047139492) .
* [Check if patch is available for your Magento issue using Quality Patches Tool](https://support.magento.com/hc/en-us/articles/360047125252) .

For info about other patches available in QPT tool, refer to the [Patches available in QPT tool](https://support.magento.com/hc/en-us/sections/360010506631-Patches-available-in-QPT-tool-) section.