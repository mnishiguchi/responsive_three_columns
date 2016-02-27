# Responsive_1

## Screen density

- Used to be 72dpi 
- Some smart phones have high resolution such as 1000px width, like desktop.
    - How to detect cell phone and desktop?
        - meta tag
        - adaptive web design (load different versions)
        - Responsive design

==

## Responsive design

### Desktop large screen
- Columns

### Mobile small screen
- no images
- stack items

### Why mobile first is better?
- A lot of mobile users only use mobile for viewing website.
- Unnecessary images are not loaded.
- From mobile upwards, we can enhance the website gradually.
- Fewer constraints.

## Simple Pure CSS Drop Down Menu
- http://css-snippets.com/drop-down-navigation/ (Simple)
- http://codepen.io/philhoyt/pen/ujHzd (Hierarchical structure)

## Power of JavaScript

```js
// Get elements.
var wrapper = document.getElementById( "wrapper" );
var logo    = document.getElementById( "logo" );

// Toggle colors.
logo.onclick = function() {
    if ( wrapper.style.color == "red" ) {
      wrapper.style.color = "blue";
    } else {
      wrapper.style.color = "red";
    }
}
```

==

## Web fonts
- Affect pageload depending on how many to select.
- Three ways to include the font (HTML, CSS or JavaScript)

- https://www.google.com/fonts (free)
- http://www.fonts.com/ (paid)

==

## Logo Image
- Google has no way to

```html
<body>
    <h1>
        <img src="logo.jpg" alt="The logo">
    </h1>

</body>

```

```css


```


# responsive_three_columns
