uiConstruction First Release
=======================================================

### Make a Under Construction with Jquery

uiConstruction.js is a plugin for jQuery that adds a beautiful and parameterized a form Under Construction. It works in all modern browsers including touch devices.


#### Usage

**HTML code:**
```html
<div id="ui-construction"></div>
```

**JavaScript code:**
```javascript
$('#ui-construction').uiConstruction({
		Company:	"Company Name",
		Title: 		"Our Website is Under Construction",
		SubTitle: "We'll be here soon with a new website.",
		Theme:		"black",
		Slide: 		{
						img:[
								'path-image/name-image-1.jpg',
								'path-image/name-image-2.jpg'
							],
						delay:10000,
						duration:'slow'
					}
});
```

#### Requirements

jQuery 1.7 or later

#### Browser support
* Chrome, Safari 5, Firefox, IE 7 or later

#### License
Released under a non-commercial BSD license
