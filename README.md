## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/gabrielmacedo/gabrielmacedo.github.com/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/gabrielmacedo/gabrielmacedo.github.com/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

### Leaflet
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.5.1/dist/leaflet.css" />
<script src="https://unpkg.com/leaflet@1.5.1/dist/leaflet.js"></script>

### BPMN.io

<!-- necessary stylesheets -->
<link rel="stylesheet" href="https://unpkg.com/bpmn-js@5.0.3/dist/assets/diagram-js.css" />
<link rel="stylesheet" href="https://unpkg.com/bpmn-js@5.0.3/dist/assets/bpmn-font/css/bpmn.css" />
<script src="https://unpkg.com/bpmn-js@5.0.3/dist/bpmn-modeler.development.js"></script>

### Chatbot TIDO
<script src="//code.tidio.co/bvxhqap4hcy1veunk6wpbvxlangxzpyw.js"></script> 

### Test TinyMCE

<html>
<head>
  <script src="https://cdn.tiny.cloud/1/ijsh89jmmlyuf7bny70pva4nrvxu1sj1gxjd0umvleyvuzc2/tinymce/5/tinymce.min.js"></script>
  <script>tinymce.init({selector:'textarea'});</script>
</head>
<body>
  <textarea>...</textarea>
</body>
</html>

### Hypothesis

<script src="https://hypothes.is/embed.js" async></script>


### EPUB.js

<script src="https://cdn.jsdelivr.net/npm/epubjs/dist/epub.min.js"></script>

<script>
  var book = ePub("url/to/book/");
  var rendition = book.renderTo("area");
  rendition.display();
</script>

### MAPBOX

<script src='https://api.mapbox.com/mapbox-gl-js/v1.3.2/mapbox-gl.js'></script>
<link href='https://api.mapbox.com/mapbox-gl-js/v1.3.2/mapbox-gl.css' rel='stylesheet' />

<div id='map' style='width: 400px; height: 300px;'></div>
<script>
mapboxgl.accessToken = 'pk.eyJ1IjoiZ2FicmllbG1hY2VkbyIsImEiOiJjazFpZWFvb2IwMmExM3JsNWYyZnBuMjNmIn0.36y0cBbEbCVq7VWaCjSYpw';
var map = new mapboxgl.Map({
container: 'map',
style: 'mapbox://styles/mapbox/streets-v11'
});
</script>

### Aeródromos Públicos - Brasil

<iframe class="render-viewer " src="https://render.githubusercontent.com/view/geojson?commit=dc03d43638d9b7d01ab4a23c992bfdc3ee1f839d&amp;enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f6761627269656c6d616365646f2f616e61632f646330336434333633386439623764303161623461323363393932626664633365653166383339642f4165726f64726f6d6f732d4d696e6973746572696f4461496e6672616573747275747572612e67656f6a736f6e&amp;nwo=gabrielmacedo%2Fanac&amp;path=Aerodromos-MinisterioDaInfraestrutura.geojson&amp;repository_id=68941377&amp;repository_type=Repository#1eb59a9a-15fd-49c0-a372-bbb20580307d" sandbox="allow-scripts allow-same-origin allow-top-navigation" title="File display" "width: 100%;
    height: 100%;
    border: 0">
</iframe>
