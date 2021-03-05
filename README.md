# FarmBits

Remove/change Powered by Shopwired from footer

Change the following in views/partials footer.twig

```<a href="{{ global.service_provider.website_url }}" target="_blank">Ecommerce Website Design</a> by {{ global.service_provider.name }}```

To
```<a href="{{ global.service_provider.website_url }}" target="_blank">Ecommerce Website Design</a> by {{ global.service_provider.name }}```
