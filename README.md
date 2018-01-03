# Blog list
jQuery Mobile / Cordova RSS Reader for https://app-o-mat.com

# Dependencies (see `www/lib`)

* [jQuery](https://jquery.com/) 2.2.4 (latest that jQueryMobile supports)
* [jQueryMobile](https://jquerymobile.com/) 1.4.5
* [jQuery Mobile Router](https://github.com/azicchetti/jquerymobile-router) (v20130527)
* [Handlebars](http://handlebarsjs.com/) (4.0.11)
* [Fastclick](https://github.com/ftlabs/fastclick) (0.6.11)

## Instructions

After installing Cordova, run the following commands (checked with Cordova 8.0.0)

```
cordova create blog-list
cordova platform add browser
cordova platform add ios
cordova plugin add cordova-plugin-inappbrowser
```

Then, replace `www` in your project folder with the one in this repo.

Watch the videos in this series to see how this was built:

https://app-o-mat.com/video-series/jquery-mobile-cordova-blog-list
