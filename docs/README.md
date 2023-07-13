📢 Use this project, [contribute](https://github.com/vtex-apps/b2b-suite) to it or open issues to help evolve it using [Store Discussion](https://github.com/vtex-apps/store-discussion).

# B2B Suite

<!-- DOCS-IGNORE:start -->
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->

[![All Contributors](https://img.shields.io/badge/all_contributors-0-orange.svg?style=flat-square)](#contributors-)

<!-- ALL-CONTRIBUTORS-BADGE:END -->
<!-- DOCS-IGNORE:end -->

**B2B Suite** is a collection of VTEX IO apps that allow stores to manage organizations, storefront roles and permissions, and checkout settings for B2B commerce relationships.

These features are particularly useful for B2B stores: in commerce relations between businesses, it is essential to simplify the purchase flow, reduce costs, and provide a personalized buying experience.

B2B customers frequently have distinct roles within their organization, such as professional buyers, managers, or supervisors. Each role is associated with a different set of storefront permissions, depending on the actions the user needs to perform.

Grouping different users from the same company under an organization and defining custom payment methods, product selections, and prices for each customer are also everyday needs in B2B.

In addition, it is often necessary to provide customized options for B2B customers during checkout, such as a specific selection of payment methods per organization or cost center, pre-filled addresses, purchase order numbers, and order quotes.

By installing the **B2B Suite**, you have access to seven apps with the following features for B2B:

| **App name** | **Description** |
| - | - |
| [Storefront Permissions](https://developers.vtex.com/docs/apps/vtex.storefront-permissions) | Stores a predefined set of roles and permissions related to what B2B users can access and do in the storefront, which other integrated apps can check. This is useful for stores that want to set specific permissions for users with different organizational roles. |
| [Storefront Permissions UI](https://developers.vtex.com/docs/apps/vtex.storefront-permissions-ui) | Provides an interface for the [Storefront Permissions](https://developers.vtex.com/docs/apps/vtex.storefront-permissions) app, communicates with its stored roles and permissions, and provides the following features for this scenario. <ul><li><b>Role management:</b> Allows VTEX Admin users to manage B2B roles and associated app permissions through an interface.</li>  <li><b>Theme block configuration:</b> Enables conditional theme blocks so only users with the required permissions can access specific content in your storefront.</li></ul> |
| [B2B Organizations](https://developers.vtex.com/docs/apps/vtex.b2b-organizations) | Enables you to group B2B users into organizations to which you can assign specific payment methods, price tables, and product collections. This allows all organization users to share the same commercial conditions. Each organization is further segmented into one or more cost centers, with its own shipping addresses, which will be available for cost center users at checkout. |
| [B2B Quotes](https://developers.vtex.com/docs/apps/vtex.b2b-quotes) | Enables B2B users to create quotes and saved carts, which are then shared with the other members of their organization. Users with the appropriate storefront permissions can modify quotes to apply discounts or change the amount of items, so the resulting quote can then be used to place an order. |
| [B2B Checkout Settings](https://developers.vtex.com/docs/apps/vtex.b2b-checkout-settings) | Extends the checkout experience for users who are members of B2B organizations. With this app, you can allow specific payment methods for the user's organization, provide prefilled addresses based on the cost center of each user, add a purchase order number to the order, and allow customers to create an order quote before placing the order. |
| [B2B Orders History](https://developers.vtex.com/docs/apps/vtex.b2b-orders-history) | Provides a new **Orders** page under **My Account** so that B2B users can view all previous orders placed by users in their organization or cost center, depending on their role. |
| [Admin Customers](https://developers.vtex.com/docs/apps/vtex.admin-customers) | Provides additional customer information management capabilities on the VTEX Admin, allowing store administrators to create, edit, and search for customers. |

Make sure to read the documentation for each app to learn more about their features and settings.

> ⚠️ After installing **B2B Suite**, make sure to hide the default **Order History** link within **My Account** by configuring `vtex.my-account`. Otherwise, **B2B Orders History** will not work as expected. You can do this at `https://{{accountName}}.myvtex.com/admin/apps/vtex.my-account@1.x/setup/`, by unselecting the **Visible** option in the **Orders** section.

For additional features, you can also install the [Quick Order](https://developers.vtex.com/docs/apps/vtex.quickorder) app, which creates a custom page in your store aimed at bulk purchases, offering tools such as uploading a spreadsheet to make bulk orders more agile.

## Frequently Asked Questions

### How do I fix the schema issue?

If you are getting alerts on B2B apps regarding a schema issue, please follow the steps below:

1. Open the VTEX Admin, and click the Master Data link on the left side of the screen. 
   ![Alt text](https://raw.githubusercontent.com/vtex-apps/b2b-suite/main/docs/assets/schema-1.png "Step one") 

2. After logging in, click **Advanced settings** as shown in the image below: 
   ![Alt text](https://raw.githubusercontent.com/vtex-apps/b2b-suite/main/docs/assets/schema-2.png "Step two") 

3. Click the last link in the list: 
   ![Alt text](https://raw.githubusercontent.com/vtex-apps/b2b-suite/main/docs/assets/schema-3.png "Step three") 
   
4. Click **Data Entities**, find the CL row, and click the **Edit** button as shown in the image below: 
   ![Alt text](https://raw.githubusercontent.com/vtex-apps/b2b-suite/main/docs/assets/schema-4.png "Step four") 

5. Find the unchecked field that is nullable and check it. Only the **email** field must be unchecked. 
   ![Alt text](https://raw.githubusercontent.com/vtex-apps/b2b-suite/main/docs/assets/schema-5.png "Step five") 
   
6. Click **Save**.
   ![Alt text](https://raw.githubusercontent.com/vtex-apps/b2b-suite/main/docs/assets/schema-6.png "Step six") 
   
7. Click the **Publish** button to apply the changes: 
   ![Alt text](https://raw.githubusercontent.com/vtex-apps/b2b-suite/main/docs/assets/schema-7.png "Step seven")

<!-- DOCS-IGNORE:start -->

## Contributors ✨

Thanks goes to these wonderful people:

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind are welcome!

<!-- DOCS-IGNORE:end -->
