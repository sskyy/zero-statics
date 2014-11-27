# zero-statics #

This module let you use express' static middleware.

## Usage ##

1. Add dependency to your module package.json file like:

```
{
	"name" : "YOUR_MODULE_NAME",
	"zero" : {
		"dependencies" : {
			"statics" : "^0.0.1"
		}
	}
}
```

2. declare `static` in your module :

```
{
	statics : [{
		'url_prefix' : FILE_PATH
	}]
}
```
