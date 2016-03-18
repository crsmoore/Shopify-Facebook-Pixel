# Shopify-Facebook-Pixel
Code to integrate the new Facebook pixel with your Shopify store.

The theme-snippet section of code is installed in the <head> section of your theme.liquid on Shopify. This will allow you to take advantage of tracking of searches, contact form submissions and add to cart as conversions. This is useful for several reasons especially if you have a non traditional store and want to consider any of these a conversion.

The thank-you-page-snippet goes in the additional content and scripts section of the Shopify admin. It is located mid way down the page at <your-store-address>/admin/settings/checkout. This allows you to track the actual dollar amount of the conversion in Ad Manager. This is the code that 90% of Shopify stores would need to track actual sales as a conversion. 

Make sure to replace <YOUR PIXEL ID> with your unique pixel ID. 
