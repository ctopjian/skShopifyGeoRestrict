#Shopify - Block Country Visit#
JS plugin to be used to block visits from countries *not* listed. The plugin is definitely not bulletproof, but a quick to to combat fraud.
Contact me at charlie@shoppro.io if you need help customizing. 

##Installation##
* npm install
* bower install

##Setup##
To add/remove country codes be sure to edit:

```javascript
cstShopifyGeoApp.settings.db = [];
```
You will also need to update the redirect URL (base64encoded)
```javascript
cstShopifyGeoApp.settings.redirectUrl 	= 'aHR0cDovL3V2Z3JhYi5jb20vcGFnZXMvYmlsbGluZy1lcnJvcg';
```

* Redirect URL is Base64 encoded

##Grunt Commands##
* `grunt` dist
* `grunt` dev

##Dependecies##
* Requires JQuery

##Notes##
* [ISO 3166 Country Codes](http://dev.maxmind.com/geoip/legacy/codes/iso3166/)
* Uses [freegeoip.net](https://docs.npmjs.com/cli/install)


#Contact#
* Email: charlietopjian@gmail.com
* Github: [http://github.com/ctopjian](http://github.com/ctopjian)

#Resources#
* [NPM Install options](https://docs.npmjs.com/cli/install)