# &lt;cp-progress-bar&gt;

> CanopyTax progress bar consistent with the CanopyTax style guide.

## Install

[Download as ZIP](https://github.com/CanopyTax/cp-progress-bar/archive/master.zip).

## Usage

1. Import polyfill:

    ```html
    <script src="/scripts/webcomponents.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="/custom_elements/cp-progress-bar.html">
    ```

3. Start using it!

    ```html
    <cp-progress-bar></cp-progress-bar>
    ```

## Options

Attribute                   | Options     | Default      | Description
---                         | ---         | ---          | ---
`min-label`                 | *string*    | `0%`         | The text that appears over the left-most side of the progress bar, usually indicating the minimum possible value.
`max-label`                 | *string*    | `100%`       | The text that appears over the right-most side of the progress bar, usually indicating the maximum possible value.
`progress-bar-color`        | *string*    | `"#67BB6A"`  | The browser-interpretable color that the progress indicator will be.
`progress-bar-border-color` | *string*    | `"#67BB6A"`  | The browser-interpretable color that the progress indicator's border will be.
`progress-percent`          | *integer*   | `0`          | The value, inclusive between 0 and 100, that indicates the amount complete.


## History

For detailed changelog, check [Releases](https://github.com/CanopyTax/cp-progress-bar/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
