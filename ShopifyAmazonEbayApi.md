[← Back](README.md)

# API access to the Shopify, Amazon & Ebay websites.

Below are the details on how to aquire the API access token and credential from the above platforms.

![Visual Guide](asset/SODownloads.png)

# Extracting new orders to process from your Shopify store
To successfully import orders and their items, ensure the Shopify SKU field for each product matches the item number in your mini-WMS app.

**Shopify Integration Requires:**  
- Your Shopify store URL. (e.g., https://5e6595-3.myshopify.com).  
- Your Shopify API access token. (e.g., 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9).  
  
**Steps to create the access token:**
Log in to Shopify Admin:
Go to your Shopify store admin panel.

**Navigate to Apps:**
In the left-hand menu, click on Apps.

**Develop Apps:**
Click on Apps and sales channel settings.
A new page will open. Click on Develop Apps and choose to allow custom apps.

**Create New App:**
Click on the Create an App button and enter the app name.

**Configure API Scopes:**
Select the following permissions:

Customer read only.
Fulfillment read only.
Orders read only.
Install the App:
Once configured, click Save.
After saving, click Install app and confirm the installation if prompted.

**Generate API Access Token:**
After installation, go to the API credentials section.
Click Reveal token once to view your Admin API access token.
Copy this token and use it in the Setup → Systemctrl screen of your app.

**Store the Token Securely:**
Make sure to store the access token securely as it provides access to your Shopify store. This is a one-time process and does not need to be repeated.

# Amazon Integration: Requires:  
- Your Amazon marketplace.  
- Amazon client ID.  
- Amazon client secret.  
- Amazon refresh token.  

# eBay Integration: Requires:  
- Your eBay API OAuth token.  

