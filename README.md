# md-lightbox
A lightbox directive for Angular Material

##Demo
[Plunkr](http://embed.plnkr.co/wbfUWDZQAfgVPwFtOZFC)

##Requirements
* Angular Material
* Angular Material Icons (For the close button)

##Use
* Include `mdLightbox` in your module.
* Adds the class `image-click` so the pointer cursor will show

```
<img ng-src="{{image}}" md-lightbox md-lightbox-title="TITLE">

<img src="http://google.com/image.jpg" md-lightbox md-lightbox-title="TITLE">
```

###Fields
* `md-lightbox`: Required
* `md-lightbox-title`: Adds a title to the bar. Not Required

##Files
* Directive: `mdLightbox.js`
* Partial: `lightbox.html`
