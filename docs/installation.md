This guide will describe the way in which The Wishlist can be installed in your Shopify store. To be able to undertake this, you will need administrative privileges for your store.

There are a few steps required for this installation:

1. Log into Shopify as an administrator
2. Create a “Custom Application”
3. Configure the privileges required for The Wishlist to be able to operate for your store
4. Capture the store credentials and pass them to The Wishlist Co to complete the installation

The following details describe each of these steps in detail.

## Login

The first step required when installing The Wishlist is to log into Shopify using an account that has administrative privileges.

At the Shopify login prompt, enter your credentials.

![Shopify signin](assets/shopify-sign-in)

## Create application

Once you're logged into Shopify using an adminstrative account, you will be able to create a custom application to install The Wishlist.

In the menu on the left-hand-side of the screen, choose **Settings**.

![Shopify settings](assets/shopify-open-settings.png)

When the settings page is displayed, select **Apps and sales channels**.

![Shopify app and sales channels](assets/shopify-app-and-sales-channels.png)

Next, pick the **Develop apps** button.

![Shopify develop apps](assets/shopify-develop-apps.png)

Note: If this is the first time you have created a custom application, then you will be shown an intermediate screen that confirms you want to start developing apps on your store. You will need to enable custom app development by clicking the **Allow custom app development** button.

The next step is to create the basis of the custom application, so click the **Create an app** button.

![Shopify create app](assets/shopify-create-an-app.png)

You'll next be asked to enter the application details.

![Shopify app details](assets/shopify-app-details.png)

1. The application name can be anything of your choice, and will be used to identify The Wishlist application from this point on. Choosing The Wishlist would be a good choice.
2. Select the application developer. This can be the email address of the store owner, or any account associated with the store that has the **Develop apps** permission.

Your custom application has now been created.

## Capture required privileges

When you first create your custom application, you will be show the application configuration screen. It has four tabs:

- Overview
- Configuration
- API Credentials
- App settings

By default, you'll be on the Overview tab. On that tab, there's a button labelled **Configure Admin API Scopes**. Click that button.

![Shopify admin API scopes](assets/shopify-admin-api-scopes.png)

## Administration scopes

When you click that button you will be shown a long list of all the possible “scopes” that are available for a Shopify store. These are analogous to the functions that an online store can perform — reading customer details, understanding browser analytics, applying discounts, etc.

As you scroll through the scopes, you will need to select the scopes that The Wishlist requires in order to operate correctly. For most of these, both read and write permission is required. When you select the “write” permission, the “read” permission will be automatically selected for you.

The following scopes are required:

- Reading and writing customer details

![Shopify customer scope](assets/shopify-scope-customer.png)

- Reading and writing inventory details

![Shopify inventory scope](assets/shopify-scope-inventory.png)

- Reading and writing locations

![Shopify locations scope](assets/shopify-scope-locations.png)

- Reading customer orders

![Shopify orders scope](assets/shopify-scope-orders.png)

- Reading and writing product listings

![Shopify product listing scope](assets/shopify-scope-product-listings.png)

- Reading and writing products

![Shopify product scope](assets/shopify-scope-products.png)

- Reading and writing script tags

![Shopify script tag scope](assets/shopify-scope-script-tags.png)

- Reading shop locales

![Shopify shop locales scope](assets/shopify-scope-locales.png)

- Reading and writing store content

![Shopify store content scope](assets/shopify-scope-store-content.png)

When you have selected all of the correct scopes, click the **Save** button.

Note: There are 16 scopes that should have been selected — you can verify this by checking how many Shopify indicates have been selected.

![Shopify save scope](assets/shopify-scope-save.png)

## Installation

After you save your changes, Shopify will confirm the selected scopes, and offer you a button to install the application. Click that **Install app** button.

![Shopify install](assets/shopify-install-app.png)

When you click the install button, Shopify will confirm that you want to install the application. Click **Install**.

![Shopify install confirm](assets/shopify-install-app-confirm.png)
