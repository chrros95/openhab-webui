# Basic UI

The Basic UI is a web interface based on Material Design Lite from Google.

## Features

- Responsive layout suitable for various screen sizes
- AJAX navigation
- Live update

## Configuration

```
org.openhab.basicui:defaultSitemap=demo
# Icons can be disabled
org.openhab.basicui:enableIcons=true
# Icons can be shown as PNG or SVG images
# Default: PNG
org.openhab.basicui:iconType=svg
```

## Accessing Sitemaps

The Basic UI has a default layout showing all things and their corresponding items. You may create your own sitemaps and access them through the basic UI in 2 ways.

1. Set the default sitemap via the UI via Settings -> Basic UI -> Configure, and set the Default Sitemap name.

2. Passing the "sitemap" parameter to the URL used to access the server.

Example: http://hostname:8080/basicui/app?sitemap=sitemapname


## Screenshots:

[![Screenshot 1](doc/screenshot-1.png)](doc/screenshot-1-full.png)
[![Screenshot 2](doc/screenshot-2.png)](doc/screenshot-2-full.png)

