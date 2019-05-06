### Demo
<textarea id="demo"></textarea>
<script>
    $(document).ready(function() {
        $('#demo').textareafullscreen();
    });
</script>
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
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"></script>
<script src="/jqeury.textareafullscreen/jquery.textareafullscreen.js"></script>
<link rel="stylesheet" href="/jqeury.textareafullscreen/textareafullscreen.css">
```
# Use
```
$(document).ready(function() {
	$('#demo').textareafullscreen({
		overlay: true, // Overlay
		maxWidth: '80%', // Max width
		maxHeight: '80%' // Max height
	});
});
```