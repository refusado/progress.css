# Progress.css

A simple and dynamic way to create horizontal and/or circular progress bars **without javascript**. The library aims to provide an easy and customizable implementation of progress bars with HTML allowing users to integrate them seamlessly into their projects and display a progress as they wish without much effort.

## Features

- Easily create horizontal and circular progress bars.
- No javascript is required.
- Label next to the progress bar.
- Customize the fill color and percentage of the progress bars.
- Insert text inside the progress bar.
- Edit the progress bar as any element on the page without worrying about breaking styles.
- Simple and intuitive implementation.

## Getting Started

To start using the Progress.css, follow these steps:

1. Include the CSS file in your project:

```html
<link rel="stylesheet" href="path/to/progress.css">
```

2. Add the appropriate class to your HTML elements:

`pss-bar` for a horizontal progress bar.

`pss-rad` for a circular progress indicator.

3. Customize the progress bar:

You can set the `--pss-fill` and `--pss-color` CSS variables in `style=""` attribute to modify the percentage and fill color of the progress bar. Add a color in the center of the circular bars with `--pss-center` variable. ***To change the background color of any progress bar, just set the `background-color` property of the element as usual.

If you want a label to the progress bar, add the `data-pss=""` attribute with the text you want in the value.

To insert a text inside the progress bar elements, simply include the desired text content within the HTML element!

## Examples

Here are some examples demonstrating the usage of Progress.css:

```html
<!-- Minimum: just "--pss-fill" variable; -->
<div class="pss-bar" style="--pss-fill: 75%"></div>

<!-- Setting the bar color: add "--pss-color" variable; -->
<div class="pss-bar" style="--pss-fill: 75%; --pss-color: #b13"></div>

<!-- Adding a label: insert "data-pss" attribute -->
<div class="pss-bar" style="--pss-fill: 18%" data-pss="18%"></div>

<!-- Inserting a text: put the text inside the element tag -->
<div class="pss-bar" style="--pss-fill: 72%">72% complete</div>

<!-- Radial minimum: using "pss-rad" class instead "pss-bar" -->
<div class="pss-rad" style="--pss-fill: 81%"></div>

<!-- Radial center color: add "pss-center" variable -->
<div class="pss-rad bar-5" style="--pss-fill: 15%; --pss-center: #70F"></div>

```

## Contributing

Contributions are welcome! If you'd like to contribute to project, please follow these steps:

1. Fork the repository and clone it to your local machine.
2. Make your changes, whether it's a bug fix, feature enhancement, or documentation improvement.
3. Test your changes to ensure they work as intended.
4. Commit your changes with messages.
5. Push your changes to your forked repository.
6. Submit a pull request to the main repository.

Thank you for considering contributing to Progress.css! Your help is greatly appreciated.

## License

This project is licensed under the  MIT License. See the [LICENSE](https://github.com/refusado/progress.css/blob/main/LICENCE) file for more information about the terms of use.