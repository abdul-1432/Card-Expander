# CSS Card Expander

![1](https://github.com/abdul-1432/Card-Expander/assets/124916666/c1609cc1-6d4d-4440-9d53-c296d129f02f)

![2](https://github.com/abdul-1432/Card-Expander/assets/124916666/aa22203b-43d3-4edd-bf1b-9aaace7f2930)


The CSS Card Expander is a simple and customizable card component built with HTML, CSS, and Javascript. It allows you to create expandable cards that reveal more content when clicked, providing a sleek and intuitive user experience for displaying additional information on your web page.

## Features

- Lightweight and easy to integrate into any website.
- Smooth CSS transitions for expanding and collapsing the card content.
- Customizable card design and appearance through CSS.
- Simple and intuitive usage with minimal Javascript.

## Preview

You can [CSS Card Expander Preview](https://codepen.io/abdul-1432/pen/xxQQELy)

## How to Use

1. Include the required CSS and Javascript files in your HTML:

```HTML
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="css/card-expander.css">
</head>
<body>
    <!-- Your content goes here -->
    <script src="js/card-expander.js"></script>
</body>
</html>
```

2. Create the HTML structure for the card:

```HTML
<div class="card-expander">
    <div class="card-header">
        <!-- Card header content (visible all the time) -->
        <h3>Card Title</h3>
    </div>
    <div class="card-content">
        <!-- Additional card content (hidden by default) -->
        <p>Additional information goes here...</p>
    </div>
</div>
```

3. Customize the appearance of the card using the provided CSS classes (`card-expander`, `card-header`, `card-content`, etc.) or create your styles.

4. Initialize the card expander by calling the `initCardExpander()` function in your Javascript file or inline script:

```html
<script>
    document.addEventListener("DOMContentLoaded", function() {
        initCardExpander();
    });
</script>
```

5. Now your card expanders are ready to use! When users click on the card header, the additional content will expand and collapse smoothly.

## Customization

You can easily customize the appearance and behavior of the card expander by modifying the CSS and adjusting the provided classes. The CSS is well-organized and commented to help you understand each part of the card expander's design.

## Compatibility

The CSS Card Expander is designed to be compatible with modern web browsers. It has been tested and confirmed to work well on the latest versions of Chrome, Firefox, Safari, and Edge.

## License

Copyright (c) 2023 by Mohammad Abdul Gafoor (https://codepen.io/abdul-1432/pen/xxQQELy)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT, OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


## Contributing

Contributions to this project are welcome! If you find any bugs, have feature requests, or want to improve the code, please open an issue or submit a pull request.

## Acknowledgments

Thanks to the open-source community for providing valuable resources and inspiration for this project.

## Contact

If you have any questions or need further assistance, you can reach me at [gafoor.mngr@gmail.com](mailto:gafoor.mngr@gmail.com) or through the GitHub repository.

Happy coding!
