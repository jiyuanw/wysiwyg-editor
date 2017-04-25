![WYSIWYG HTML Editor](https://raw.githubusercontent.com/froala/wysiwyg-editor/master/editor.jpg)



# Froala Editor [![Build Status](https://travis-ci.com/froala-labs/froala-editor-js-2.svg?token=6qHm2TpvBKAAVFCrJa9X&branch=master)](https://travis-ci.com/froala-labs/froala-editor-js-2)

Froala WYSIWYG HTML Editor is one of the most powerful JavaScript rich text editors ever.

- Slim - only add the plugins that you need ([30+ official plugins](https://www.froala.com/wysiwyg-editor/docs/plugins))
- Client frameworks integrations
- Server side SDKs for [PHP](https://www.froala.com/wysiwyg-editor/docs/sdks/php), [Node.JS](https://www.froala.com/wysiwyg-editor/docs/sdks/nodejs),  [.NET](https://www.froala.com/wysiwyg-editor/docs/sdks/dotnet), [Java](https://www.froala.com/wysiwyg-editor/docs/sdks/java), and [Python](https://www.froala.com/wysiwyg-editor/docs/sdks/python)
- Code is well commented
- [Online documentation](https://www.froala.com/wysiwyg-editor/docs) up to date
- Simple to extend - the plugins are all well commented and simple to use as a basis for your own plugins
- Well maintained - [frequent releases](https://www.froala.com/wysiwyg-editor/changelog)
- Great support - [Help Center](https://wysiwyg-editor.froala.help)
- Reasonable [licensing](https://www.froala.com/wysiwyg-editor/pricing)




## Browsers support <sub><sup><sub><sub>made by <a href="https://godban.github.io">godban</a></sub></sub></sup></sub>

| [<img src="https://raw.githubusercontent.com/godban/browsers-support-badges/master/src/images/edge.png" alt="IE / Edge" width="16px" height="16px" />](http://godban.github.io/browsers-support-badges/)</br>IE / Edge | [<img src="https://raw.githubusercontent.com/godban/browsers-support-badges/master/src/images/firefox.png" alt="Firefox" width="16px" height="16px" />](http://godban.github.io/browsers-support-badges/)</br>Firefox | [<img src="https://raw.githubusercontent.com/godban/browsers-support-badges/master/src/images/chrome.png" alt="Chrome" width="16px" height="16px" />](http://godban.github.io/browsers-support-badges/)</br>Chrome | [<img src="https://raw.githubusercontent.com/godban/browsers-support-badges/master/src/images/safari.png" alt="Safari" width="16px" height="16px" />](http://godban.github.io/browsers-support-badges/)</br>Safari | [<img src="https://raw.githubusercontent.com/godban/browsers-support-badges/master/src/images/opera.png" alt="Opera" width="16px" height="16px" />](http://godban.github.io/browsers-support-badges/)</br>Opera | [<img src="https://raw.githubusercontent.com/godban/browsers-support-badges/master/src/images/safari-ios.png" alt="iOS Safari" width="16px" height="16px" />](http://godban.github.io/browsers-support-badges/)</br>iOS Safari | [<img src="https://raw.githubusercontent.com/godban/browsers-support-badges/master/src/images/chrome-android.png" alt="Chrome for Android" width="16px" height="16px" />](http://godban.github.io/browsers-support-badges/)</br>Chrome for Android |
| --------- | --------- | --------- | --------- | --------- | --------- | --------- |
| IE10, IE11, Edge| last 3 versions| last 3 versions| last 3 versions| last 3 versions| last 3 versions| last 3 versions




## Get Started

Froala WYSIWYG HTML Editor requires [jQuery](http://jquery.com/) 1.11.0 or higher and the iconic font named [Font Awesome](http://fortawesome.github.io/Font-Awesome/) 4.4.0. You may also use older versions of Font Awesome, but some of the editor's icons will not appear. 

```html
<!-- Include CSS for icons. -->
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.4.0/css/font-awesome.min.css" rel="stylesheet" type="text/css" />

<!-- Include Editor style. -->
<link href="https://cdnjs.cloudflare.com/ajax/libs/froala-editor/2.5.1/css/froala_editor.pkgd.min.css" rel="stylesheet" type="text/css" />
<link href="https://cdnjs.cloudflare.com/ajax/libs/froala-editor/2.5.1/css/froala_style.min.css" rel="stylesheet" type="text/css" />

<!-- Create a tag that we will use as the editable area. -->
<!-- You can use a div tag as well. -->
<textarea></textarea>

<!-- Include jQuery lib. -->
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>

<!-- Include Editor JS files. -->
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/froala-editor/2.5.1//js/froala_editor.pkgd.min.js"></script>

<!-- Initialize the editor. -->
<script> 
  $(function() { 
    $('textarea').froalaEditor() 
  }); 
</script>
```

For more details on customizing the editor, please check the editor [documentation](https://www.froala.com/wysiwyg-editor/docs).



## Download

- npm: `npm install froala-editor`
- bower: `bower install froala-wysiwyg-editor`
- CDN: https://cdnjs.com/libraries/froala-editor
- Angular JS: https://github.com/froala/angular-froala
- Angular 2: https://github.com/froala/angular2-froala-wysiwyg
- Aurelia: https://github.com/froala/aurelia-froala-editor
- CakePHP: https://github.com/froala/wysiwyg-cake
- Django: https://github.com/froala/django-froala-editor
- Ember: https://github.com/froala/ember-froala-editor
- Knockout: https://github.com/froala/knockout-froala
- Meteor: https://github.com/froala/meteor-froala
- Ruby on Rails: https://github.com/froala/wysiwyg-rails
- React JS: https://github.com/froala/react-froala-wysiwyg/
- Reactive: https://github.com/froala/froala-reactive
- Symfony: https://github.com/froala/KMSFroalaEditorBundle
- Vue JS: https://github.com/froala/vue-froala-wysiwyg/
- Yii2: https://github.com/froala/yii2-froala-editor
- Wordpress: https://github.com/froala/wordpress-froala-wysiwyg




## Resources

- Demo: [www.froala.com/wysiwyg-editor](http://www.froala.com/wysiwyg-editor)
- Download Page: [www.froala.com/wysiwyg-editor/download](https://www.froala.com/wysiwyg-editor/download)
- Documentation:  [froala.com/wysiwyg-editor/docs](https://www.froala.com/wysiwyg-editor/docs)
- License Agreement: [www.froala.com/wysiwyg-editor/terms](https://www.froala.com/wysiwyg-editor/terms)
- Support: [wysiwyg-editor.froala.help](https://wysiwyg-editor.froala.help/hc/en-us)
- Issues [Repo guidelines](https://github.com/highcharts/highcharts/blob/master/repo-guidelines.md)




## Reporting Issues

We use GitHub Issues as the official bug tracker for the Froala WYSIWYG HTML Editor. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the Froala WYSIWYG Editor. The issue that you are about to report may be already fixed in the latest master branch version: https://github.com/froala/froala-wysiwyg/tree/master/js.
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed. A [JSFiddle](https://jsfiddle.net) is always welcomed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.




## Technical Support or Questions

If you have questions or need help integrating the editor please [contact us](https://www.froala.com/wysiwyg-editor/contact) instead of opening an issue.



## Licensing

In order to use the Froala Editor you have to purchase one of the following licenses according to your needs. You can find more about that on our website on the [pricing plan page](https://www.froala.com/wysiwyg-editor/pricing).



## Useful links

* Official website:  [froala.com/wysiwyg-editor](https://www.froala.com/wysiwyg-editor)
* Official download: [froala.com/wysiwyg-editor/pricing](https://www.froala.com/wysiwyg-editor/pricing)
* Changelog:  [froala.com/wysiwyg-editor/changelog](https://www.froala.com/wysiwyg-editor/changelog)
* Licensing: [froala.com/wysiwyg-editor/terms](https://www.froala.com/wysiwyg-editor/terms)
* FAQ: [wysiwyg-editor.froala.help](https://wysiwyg-editor.froala.help/hc/en-us)
* Support: [froala.com/wysiwyg-editor/contact](https://wysiwyg-editor.froala.help/hc/en-us)
