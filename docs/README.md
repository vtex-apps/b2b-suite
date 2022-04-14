📢 Use this project, [contribute](https://github.com/vtex-apps/b2b-suite) to it or open issues to help evolve it using [Store Discussion](https://github.com/vtex-apps/store-discussion).

# B2B Suite

<!-- DOCS-IGNORE:start -->
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->

[![All Contributors](https://img.shields.io/badge/all_contributors-0-orange.svg?style=flat-square)](#contributors-)

<!-- ALL-CONTRIBUTORS-BADGE:END -->
<!-- DOCS-IGNORE:end -->

The **B2B Suite** is a collection of VTEX IO apps that allow stores to manage organizations, storefront roles and permissions and checkout settings for B2B commerce relationships.

These capabilities are particularly useful for B2B stores: in commerce relations between businesses, it is essential to simplify the purchase flow, reduce costs, and provide a personalized shopping experience.

B2B customers frequently have distinct roles within their organization, such as professional buyer, manager, or supervisor. Each role is associated with a different set of storefront permissions, depending on the actions the user needs to perform.

Grouping different users from the same company under an organization, as well as defining custom payment methods, product selections and prices for each customer, are also common needs in the B2B context.

In addition, it is often necessary to provide customized options for B2B customers during checkout, such as a specific selection of payment methods per organization or cost center, pre-filled addresses, purchase order numbers, and order quotes.

By installing the **B2B Suite**, you have access to seven apps with the following functionalities for the B2B scenario:

| **App name** | **Description** |
| | |
| [Storefront Permissions](https://developers.vtex.com/vtex-developer-docs/docs/vtex-storefront-permissions) | Stores a predefined set of roles and permissions related to what B2B users can access and do in your storefront, making this information available for other integrated apps to check. This is useful for stores who want to set specific permissions for users with different roles in an organization. |
| [Storefront Permissions UI](https://developers.vtex.com/vtex-developer-docs/docs/vtex-storefront-permissions-ui) | Provides an interface for the [Storefront Permissions](https://developers.vtex.com/vtex-developer-docs/docs/vtex-storefront-permissions) app, communicates with its stored roles and permissions and provides the following features for this scenario: <ul><li><b>Roles management:</b> allows VTEX Admin users to manage B2B roles and associated app permissions through an interface.</li> <li><b>Theme blocks configuration:</b> enables conditional theme blocks so that only users with the required permissions can access determined parts of the content in your storefront.</li></ul> |
| [B2B Organizations](https://developers.vtex.com/vtex-developer-docs/docs/vtex-b2b-organizations) | Enables you to group B2B users into organizations, to which you can assign specific payment methods, price tables, and product collections. This allows all of the organization’s users to share the same commercial conditions. Each organization is further segmented into one or more cost centers, with its own shipping addresses which are available to that cost center's users during checkout. |
| [B2B Quotes](https://developers.vtex.com/vtex-developer-docs/docs/vtex-b2b-quotes) | Enables B2B users to create quotes and saved carts which are then shared with the other members of their organization. Users with the appropriate storefront permissions can modify quotes to apply discounts or change quantities, and the resulting quote can then be used to place an order. |
| [B2B Checkout Settings](https://developers.vtex.com/vtex-developer-docs/docs/vtex-b2b-checkout-settings) | Extends the checkout experience for users who are members of B2B organizations. With this app, you can allow specific payment methods for the user’s organization, provide pre-filled addresses based on each user’s cost center, include a purchase order number in the order, and allow customers to create an order quote before making an actual purchase. |
| [B2B Orders History](https://github.com/vtex-apps/b2b-orders-history) | Provides a new **Orders** page under **My Account** so that B2B users can view all prior orders placed by users in their organization or cost center, depending on their role. |
| [Admin Customers](https://developers.vtex.com/vtex-developer-docs/docs/vtex-admin-customers) | Provides additional customer data management capabilities on the VTEX Admin, allowing store administrators to create, edit and search for customers. |

Make sure you read each app’s documentation to learn more about their capabilities and configurations.

> ⚠️ After installing the **B2B Suite**, make sure to hide the default **Order History** link within **My Account** by configuring `vtex.my-account`. Otherwise, **B2B Orders History** will not work as expected. You can do this at `https://{{accountName}}.myvtex.com/admin/apps/vtex.my-account@1.x/setup/`, by unselecting the **Visible** option in the **Orders** section.

For additional functionalities, you can also install the [Quick Order](https://developers.vtex.com/vtex-developer-docs/docs/vtex-quickorder) app, which creates a custom page in your store aimed at purchases in bulk, offering tools such as uploading a spreadsheet to make bulk orders more agile.

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
