### Demo

<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css" integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf" crossorigin="anonymous">

<style>

.tx-editor-wrapper .tx-editor .tx-icon-save {
    position: absolute;
    right: 5px;
    top: 25px;
    width: 18px;
    height: 16px;
    cursor: pointer;
    z-index: 3;
  }	
</style>	

<script>
    $(document).ready(function() {
        $('#demo').textareafullscreen( {
		overlay: true,
		maxWidth: '80%',
		maxHeight: '80%',
	        extButtons: '<a href="#" class="tx-icon-save fas fa-save"></a>',
                fontAwesome: true,
	});
    });
</script>

<textarea id="demo"></textarea>

```
<textarea id="demo"></textarea>
<script>
    $(document).ready(function() {
        $('#demo').textareafullscreen();
    });
</script>
```
# Install
Insert this code before tag `</head>`
```
<script src="//code.jquery.com/jquery-3.4.1.min.js"></script>
<script src="/jqeury.textareafullscreen/jquery.textareafullscreen.js"></script>
<link rel="stylesheet" href="/jqeury.textareafullscreen/textareafullscreen.css">
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
