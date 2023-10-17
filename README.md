# Alt Seo

> Alt Seo is a Statamic addon that does something pretty neat.

## Features

This addon does:

- Add's general sitewide SEO tags
- Or page specific SEO tags
- Title, Description, Social Title, Social Description and Social Image


## How to Install

You can search for this addon in the `Tools > Addons` section of the Statamic control panel and click **install**, or run the following command from your project root:

``` bash
composer require alt-design/alt-seo
```

## How to Use

Replace <title> tags with {{ alt_seo:meta }}

For General/Site Wide SEO Tags Select Alt SEO from the Tools section in CP where you can set a general SEO Title and Description for the site. In the Social tab you can set the Title, Description and Image for Facebook and Twitter.

For Page Specific SEO Tags go to Collections > Pages > select your page and in the Alt SEO Tab you can set Title, Description, Social Title, Social Description and Social Image to override the general settings on that page.

You can use variables such as {title} | {site_name}

App name and url are taken from .env file so ensure this data is correct. Images must be stored in assets container.
