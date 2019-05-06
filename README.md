jQeury.textareafullscreen
=============

Jquery plugin textarea fullscreen mode

# Install
Insert this code before tag `</head>`
```
<script src="//code.jquery.com/jquery-3.4.1.min.js"></script>
<script src="/jquery.textareafullscreen/jquery.textareafullscreen.js"></script>
<link rel="stylesheet" href="/jquery.textareafullscreen/textareafullscreen.css">
```
# Use
```
$(document).ready(function() {
	$('#demo').textareafullscreen({
		overlay: true, // Overlay
		maxWidth: '80%', // Max width
		maxHeight: '80%', // Max height
	        extButtons: '<a href="#" class="tx-icon-save fas fa-save"></a>', //Add custom button
                fontAwesome: true, //Use FontAwesome - you must include all css and js from it 
	});
});
```
# Additional button css
```
.tx-editor-wrapper .tx-editor .tx-icon-save {
    position: absolute;
    right: 5px;
    top: 25px;
    width: 18px;
    height: 16px;
    cursor: pointer;
    z-index: 3;
  }
```

[Demo](http://creoart.github.io/jquery.textareafullscreen)
