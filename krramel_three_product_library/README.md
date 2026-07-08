# KRRAMEL Three Product Local Library

Generated: 2026-07-09 02:27:06+0800

## Main Files

- `krramel_three_products.sqlite`: normalized SQLite database.
- `krramel_three_product_library.json`: full JSON export with products, parameters, SKUs, reviews, media, images, screenshots, and text records.
- `exports/`: CSV exports for product overview, parameters, SKU options, reviews, review media, images, screenshots, and text.
- `assets/images/`: downloaded product/detail/review images organized by item id.
- `assets/screenshots/`: screenshots captured during browser extraction.
- `image_gallery.html`: local gallery for reviewing all downloaded images.

## Counts

- Products: 3
- Parameters: 33
- SKU/options: 47
- Reviews: 609
- Review media records: 1518
- Image manifest rows: 1422
- Downloaded unique local images: 1391
- Screenshots: 24

## SQLite Tables

`products`, `product_texts`, `product_params`, `sku_options`, `reviews`,
`review_media`, `images`, `screenshots`, `qa`, `recommendations`,
`source_files`, `library_stats`.
