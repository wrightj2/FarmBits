# FarmBits

**Remove/change Powered by Shopwired from footer**

Change the following in views/partials footer.twig

```<a href="{{ global.service_provider.website_url }}" target="_blank">Ecommerce Website Design</a> by {{ global.service_provider.name }}```

To
```<a href="https://www.neuralcandy.com" target="_blank"><strong>Design by NeuralCandy</strong></a>```


Themes > Installed Themes > Page Editor > Views > Partials > product_form.twig

You need to remove the ```<!-- on line 467 and the -->``` on line 481 and then save changes (commenting out the buy now button)

**Remove side menu from category pages**

Add the following at bottom of _components.scss in stylesheets

```
.side-menu {
	display: none;
}
```
