# Shopify-Facebook-Pixel
Code to integrate the new Facebook pixel with your Shopify store. 

There are 2 places to install the pixel code on your Shopify store to take full advantage of the conversion tracking. The first will install in the theme.liquid and the second installs in the additional content and scripts section of the admin. The code has been modified to include the appropriate Shopify liquid in order to include the actual sale price of each item as well as to reduce duplicate conversions. 

The theme-snippet section of code is installed in the <head> section of your theme.liquid on Shopify. This will allow you to take advantage of tracking of searches, contact form submissions and add to cart as conversions. This is useful for several reasons especially if you have a non traditional store and want to consider any of these a conversion.

The thank-you-page-snippet goes in the additional content and scripts section of the Shopify admin. It is located mid way down the page at <your-store-address>/admin/settings/checkout. This allows you to track the actual dollar amount of the conversion in Ad Manager. This is the code that 90% of Shopify stores would need to track actual sales as a conversion. The if statement at the top is to prevent duplicates since the Thank You page is also the track order page for Shopify and you don't want to count a conversion every time the customer checks the tracking. 

Make sure to replace <YOUR PIXEL ID> with your unique pixel ID. 
