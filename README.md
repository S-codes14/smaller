# SmallerSites


## Drag and drop website designer javascript library.
Built with jQuery and Bootstrap 4.

Using [Startbootstrap new page](https://startbootstrap.com/template-overviews/new-page/) for demo page and Bootstrap 4 components.

### Features

* Components and blocks/snippets drag and drop.
* Undo/Redo operations.
* One or two panels interface.
* File manager and component hierarchy navigation.
* Add new page.
* Live code editor.
* Image upload with example php script included.
* Page download or export html or save page on server with example php script included.
* Components/Blocks list search.
* Bootstrap 4 components.
* Youtube, Google maps, Charts.js etc widgets.

By default the editor comes with Bootstrap 4 and Widgets components and can be extended with any kind of components and inputs.

## Usage

```html
<!-- jquery-->
<script src="js/jquery.min.js"></script>
<script src="js/jquery.hotkeys.js"></script>

<!-- bootstrap-->
<script src="js/popper.min.js"></script>
<script src="js/bootstrap.min.js"></script>

<!-- builder code-->
<script src="libs/builder/builder.js"></script>	
<!-- undo manager-->
<script src="libs/builder/undo.js"></script>	
<!-- inputs-->
<script src="libs/builder/inputs.js"></script>	
<!-- components-->
<script src="libs/builder/components-bootstrap4.js"></script>	
<script src="libs/builder/components-widgets.js"></script>	


<script>
$(document).ready(function() 
{
	Smaller.Builder.init('demo/index.html', function() {
		//load code after page is loaded here
		Smaller.Gui.init();
	});
});
</script>
```
For editor html and components/input javascript templates check editor.html

For css changes edit scss/editor.scss and scss/_builder.scss



## License

Apache 2.0
