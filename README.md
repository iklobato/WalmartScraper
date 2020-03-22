# WalmartScraper

## This is a product price collection script on a branch of the actual Walmart website.

## HOW IT WORKS:
Using Walmart's own api (which was discovered in the HTTP price-offer request) the script walks through all the products on the branch's main page, collecting:
- Product's name
- Description
- Department name
- Product quantity unit (Kg, unit, meters ...)
- Product image URL
- Brand name
- Bar code
- Prices in different stores

## PRICES:
During the video I demonstrated only the first valid price.
However, a dictionary is returned with all the offer values of the same product in different stores.

## Video demo
[![Demonstration](https://i.vimeocdn.com/video/867741686.webp?mw=700&mh=271)](https://player.vimeo.com/video/399634063)
