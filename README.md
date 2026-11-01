# vinyl-broker agent profile

The [UCP](https://ucp.dev) agent profile of `vinyl-broker`, a personal tool that reads the public
catalogs of a handful of independent record labels' Shopify stores to notify its operator of new
releases and restocks. A human always completes any purchase.

It declares two read-only capabilities, catalog search and catalog lookup (`lookup_catalog`,
to re-read the variants it already knows), and nothing else: it never creates carts or checkouts.

Contact: vinylbroker.drops@gmail.com
