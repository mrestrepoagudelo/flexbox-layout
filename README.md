<h1> Layout Flexbox </h1>
Layout made with flexbox

Example available at https://mrestrepoagudelo.github.io/layoutflexbox/

<h3>Include Layout Flexbox CSS:</h4>

```html
  <link href="m-layout.css" rel="stylesheet">
```

<h3>Example:</h4>

```html
<div class="m-layout" style="width: 800px; height: 500px;">
    <div class="m-top">
        <p>Top region</p>
    </div>
          
    <div class="m-middle">
        <div class="m-left">
            <p>Left region</p>
        </div>

        <div class="m-center">
            <div style="height: 800px;"><p>Center region</p></div>
        </div>

        <div class="m-right">
            <p>Right region</p>
        </div>
    </div>
          
    <div class="m-bottom">
        <p>Bottom regoin</p>
    </div>
</div>
```


<h3>CSS Classes:</h4>

`m-layout` <br>
Class to style the div containing the tabs<br><br>
`m-top` <br>
Class to style the top region<br><br>
`m-bottom` <br>
Class to style the bottom region<br><br>
`m-middle` <br>
Class to give style to the middle region. This region is the one containing the left, right and center regions <br><br>
`m-center` <br>
Class to style the center region<br><br>
`m-left` <br>
Class to style the left region<br><br>
`m-right` <br>
Class to style the right region<br><br>

<h3>Note:</h4>
It doesn't matter if you create the messy regions. Regions will be sorted automatically thanks to flexbox "order" property.
