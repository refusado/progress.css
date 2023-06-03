
![Demo](./assets/banner.png)
A simple and dynamic way to create horizontal and/or circular progress bars **without javascript**. The library aims to provide an easy and customizable implementation of progress bars with HTML allowing users to integrate them seamlessly into their projects and display a progress as they wish without much effort.

## Features
- Easily create horizontal and circular progress bars.
- No javascript is required.
- Insert labels/texts.
- Customize colors and sizes quickly and easily.
- Edit the progress bar as any element on the page without worrying about breaking styles.
- Create groups of multiple progress bars
- Simple and intuitive implementation.

## Getting Started
To start using the Progress.css, follow these steps:

1. Include the CSS file in your project:

    #### Using npm
    Install
    ```
    npm install progress.css
    ```
    And include the file in your html
    ```html
    <link rel="stylesheet" href="path/to/progress.css">
    ```
    #### Via CDN
    You can also just include the file in your html via CDN without installing.
    ```html
    <link rel="stylesheet" href="https://unpkg.com/progress.css/progress.min.css">
    <!-- Or -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/refusado/progress.css/progress.min.css">
    ```

2. Make your element a progress bar:
    #### One by one
    Add the `data-pss` attribute to your HTML tag and it will become a progress bar. To choose the percentage, type the value of the percentage into the CSS variable `--pss-value`. ⚠️ Do not put the `%` symbol, just the number.
    ```html
    <div data-pss style="--pss-value: 94"></div>
    ```
    
    #### Many at once
    If you want to style several at once, use the `data-pss-container` attribute on the container of the elements you want to turn into progress bars.
    ```html
    <div data-pss-container>
      <div style="--pss-value: 25"></div>
      <div style="--pss-value: 50"></div>
      <div style="--pss-value: 75"></div>
      <div style="--pss-value: 100"></div>
    </div>
    ```


3. Customize the progress bar:
    #### Horizontal and cirular bars
    The `data-pss` attribute will create a horizontal progress bar by default, but if you want a radial progress bar instead,t add the value "rad" to this attribute.

    ```html
      <div data-pss="rad" style="--pss-value: 30"></div>
    ```
    #### Variables
    These are the CSS variables that define the progress bar settings, they all have a default value but can be changed by reassigning the variable value. This can be done either in the document styles CSS file or in inline CSS.

    | Variable                   | Description |
    |----------------------------|-------------|
    | `--pss-value`  | Percentage filled. Default: **65** |
    | `--pss-left`   | Color of the left fill. Default: **#08a33e** |
    | `--pss-right`  | Color of the right fill. Default: **#DDF4F9** |
    | `--pss-center` | Center color of radial progress bars. Default: **#14975a** |
    | `--pss-width`  | Radial progress bar width. Default: **.4em** |

    #### Texts/labels
    To add text to a horizontal progress bar, use the `aria-label="[text]"` attribute. You can also add the text inside the element's tag, the difference is that this text will not be centered inside the filled part of the bar. It's recommended that you use the first method.

    ```html
    <div data-pss style="--pss-value: 48" aria-label="48%"></div>
    ```
    For radial progress bars there is no additional attribute, just place your text inside the element
    ```html
    <div data-pss="rad" style="--pss-value: 80">8/10</div>
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

## Autor

Refu

- [Discord](https://discord.com/users/412685400847679508)
- [Github](https://github.com/refusado)
- [Youtube](https://www.youtube.com/@refusado)
- [Email](mailto:refusado@gmail.com)
- [Twitter](https://twitter.com/refusado)

## License

This project is licensed under the  MIT License. See the [LICENSE](https://github.com/refusado/progress.css/blob/main/LICENSE) file for more information about the terms of use.