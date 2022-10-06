# Product Description & Purpose

Pull in your WooCommerce Products with Yext's new WooCommerce Product Connector! WooCommerce is a plug-in with Wordpress Site to help users seamlessly run store, from managing product inventory to capturing sales. With the Addition of the WooCommerce Product connector, you can pull in all of your product information into your Knowledge Graph to be used in the Yext Platform.

The WooCommernce Product connector will pull in data about your product including, but not limited to: product SKU, pricing, inventory levels, shipping dimensions, related products, product category, etc. Note: The connector is configured to run comprehensively on a daily cadence.

This app aligns with the existing Yext Product entity type and creates 8 custom fields:

- Sale Status
- Rich Text Short Description
- Related Product
- Regular Price
- Rating Count
- Average Rating
- Featured Product

Note: Currency will default to most frequently used Currency Country Code based on currency symbol returned. USD will return for $ currency symbols. Users are able to override the currency value by using Transforms to 'Add New Column' and remap custom Currency Country Code.

# Requirements

To use this template you will need to have the following items accessible:

- Wordpress Domain
- Wordpress Account Acccess with WooCommerce Plug-in installed

# Installation Instructions

Before installing the app do the following :
1. Log into your WordPress account and copy down your WordPress domain name
2. (Still on WordPress) Navigate to WooCommerce > Settings > Advanced > REST API and click “Add Key”. Provide a unique description, select “Read” as the permission, and click “Generate API Key”.
3. Copy down the Consumer key and Consumer secret values. These will serve as your Basic Auth username and password, respectively.
