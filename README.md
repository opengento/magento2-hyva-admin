# Replace Magento2 admin grids by Hyvä admin grid

[Hyvä grid](https://github.com/hyva-themes/magento2-hyva-admin) is a module created by [Vinai Kopp](https://github.com/Vinai) to make creating grids and forms in the Magento 2 adminhtml area joyful and fast.
It does not use any UI components.

Hyva Admin provides tools to create your custom grids or replace standard ones.

In Magento 2 we can find 2 type of grids, slow ones but highly customizable (Product Grid) and pretty fast ones (Catalog Price Rule).

This Opengento module replace all **slow** Magento 2 grids.

## Composer installation

Important: **Composer 2 is mandatory**.

Magento 2 Community:

```
composer require opengento/module-magento2-hyva-admin
bin/magento setup:upgrade
```

## Grids replaced

Legend:

> ✅ included					
> 🔜 coming soon (in progress)							
> ❌ not going to be included

| Magento 2 Community                                        | ✅ | 🔜 | ❌ | Comment      |
|------------------------------------------------------------|----|----|----|--------------|
| Sales > Orders                                             | 🔳 |    |    |              |
| Sales > Invoices                                           | 🔳 |    |    |              |
| Sales > Shipments                                          | 🔳 |    |    |              |
| Sales > Credit Memos                                       | 🔳 |    |    |              |
| Sales > Billing Agreements                                 |    |    | 🔳 | Dropped.     |
| Sales > Transactions                                       | 🔳 |    |    |              |
| Catalog > Products                                         |    | 🔳 |    |              |
| Catalog > Products Edit Form > Reviews (+)                 |    |    |    |              |
| Customers > All Customers                                  |    | 🔳 |    |              |
| Customers > Now Online                                     |    |    |    |              |
| Customers > Login as Customer Log                          |    |    |    |              |
| Customers > Customer Groups                                |    | 🔳 |    |              |
| Customers > Newsletter Subscribers                         |    | 🔳 |    |              |
| Customers > Listening Request                              |    | 🔳 |    |              |
| Marketing > Promotions > Catalog Price Rule                | 🔳 |    |    | Already Fast |
| Marketing > Promotions > Cart Price Rules                  | 🔳 |    |    | Already Fast |
| Marketing > Communications > Email Templates               | 🔳 |    |    | Already Fast |
| Marketing > Communications > Newsletter Templates          | 🔳 |    |    | Already Fast |
| Marketing > Communications > Newsletter Queue              | 🔳 |    |    | Already Fast |
| Marketing > Communications > Newsletter Subscribers        | 🔳 |    |    | Already Fast |
| Marketing > SEO & Search > URL Rewrites                    |    | 🔳 |    |              |
| Marketing > SEO & Search > Search Terms                    | 🔳 |    |    | Already Fast |
| Marketing > SEO & Search > Search Synonyms                 |    |    | 🔳 | Dropped.     |
| Marketing > SEO & Search > Site Map                        | 🔳 |    |    | Already Fast |
| Marketing > User Content > All Reviews                     | 🔳 |    |    | Already Fast |
| Marketing > User Content > Pending Reviews                 | 🔳 |    |    | Already Fast |
| Content > Pages                                            |    | 🔳 |    |              |
| Content > Blocks                                           |    | 🔳 |    |              |
| Content > Widgets                                          | 🔳 |    |    | Already Fast |
| Content > Templates                                        |    | 🔳 |    |              |
| Content > Design > Configuration                           |    | 🔳 |    |              |
| Content > Design > Themes                                  |    | 🔳 |    |              |
| Content > Design > Schedule                                | 🔳 |    |    | Already Fast |
| Reports > *                                                |    |    | 🔳 | Dropped.     |
| Stores > Settings > All Stores                             | 🔳 |    |    | Already Fast |
| Stores > Settings > Terms and Conditions                   | 🔳 |    |    | Already Fast |
| Stores > Settings > Order Status                           | 🔳 |    |    | Already Fast |
| Stores > Inventory > Sources                               |    | 🔳 |    |              |
| Stores > Inventory > Stocks                                |    | 🔳 |    |              |
| Stores > Taxes > Tax Rules                                 | 🔳 |    |    | Already Fast |
| Stores > Taxes > Tax Zones and Rates                       | 🔳 |    |    | Already Fast |
| Stores > Attributes > *                                    | 🔳 |    |    | Already Fast |
| System > *                                                 | 🔳 |    |    | Already Fast |

(cf Hyvä [Theme Matrix](https://hyva.io/hyva-themes-feature-matrix))

## Documentation

The Hyvä Admin documentation is available [here](https://github.com/hyva-themes/magento2-hyva-admin/tree/main/doc).

## Support & Contribution

Feel free to raise a new [request](https://github.com/opengento/magento2-hyva-admin/issues) to the issue tracker or contribuate to this repository.

## Authors

- **Opengento Community** - *Lead* - [![Twitter Follow](https://img.shields.io/twitter/follow/opengento.svg?style=social)](https://twitter.com/opengento)
- **Frédéric MARTINEZ (PH2M)** - *Maintainer* - [![Twitter Follow](https://img.shields.io/twitter/follow/FredMartinez.svg?style=social)](https://twitter.com/FredMartinez)
- **Ravinder (Redmonks)** - *Fork* - [![Twitter Follow](https://img.shields.io/twitter/follow/_redChamps.svg?style=social)](https://twitter.com/_redChamps)
- **Contributors** - *Contributor* - [![GitHub contributors](https://img.shields.io/github/contributors/opengento/magento2-hyva-admin.svg?style=flat-square)](https://github.com/opengento/magento2-hyva-admin/graphs/contributors)

This repository is a fork from [Redmonks - Hyva Sales Grids](https://github.com/redmonks/magento2-module-hyva-admin-sales-grids).

## License

Copyright 2021 Vinai Kopp & Hyvä Themes BV

The module is released under the BSD-3 Clause license - see the [LICENSE](./LICENSE) details.

***That's all folks!***

