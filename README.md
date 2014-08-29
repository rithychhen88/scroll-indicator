Scrollbar Indicator
================

Scrollbar Indicator is useful for lengthy webpages. It helps indentifying the current location on a giving page. The Scrollbar Indicator can also be used to navigate through the content of a page. It is really simple to set up.

Checkout the [demo](http://rithychhen.com/jquery/scrollbar)


##Dependencies 

Scrollbar Indicator requires the following libraries:

1. The latest Jquery, which you can download from [here](http://jquery.com/).
2. The latest jqueryUI, you can download from [here](http://jqueryui.com/).

##Getting started

Download the latest code from [here](https://github.com/rithychhen88/scroll-indicator).

##How to use Scrollbar Indicator

Include the following css files into the header

``` 
   <link href="http://example.com/css/jquery-ui.min.css" rel="stylesheet">
   
   <link href="http://example.com/css/jquery-scrollbar-indicator.css" rel="stylesheet">
```

nclude the javascript files into the page
```
	<script src="http://example.com/js/jquery.min.js"></script>

	<script src="http://example.com/js/jquery-ui.js"></script>

	<script src="http://example.com/js/jquery-scrollbar-indicator.js"></script>
```

HTML decoration for your images goes like this
```
<div id="scrollbar"></div>
```

Include the following near the end of the page or in a seperate javascript file
```
<script type="text/javascript">
    $("#scrollbar").scrollbarIndicator();
</script>
```
### Initialization options

The following are the initialization options and their default values
```
handleColor: "#556b2f"

backgroundColor: "#e9e9e9"

height: 400
```

You can override any of these values during initialization.
```
<script type="text/javascript">
    $("#scrollbar").scrollbarIndicator({
        "handleColor": "pink",
        "backgroundColor": "yellow",
        "height": 400
    });
</script>
```

