# jQuery Popup Plugin

A simple jQuery plugin to create popups with customizable messages, durations, and types.

## Usage

1. Include the jQuery library, the `popalert-js.js` and the  `popalert-js.css` files in your HTML file:

   ```html
   <!DOCTYPE html>
    <html>
        <head>
            <title>POPALERT-JS</title>
            <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
            <link rel="stylesheet" href="path/to/popalert-js.css">
        </head>
        <body>
            <script src="path/to/popalert-js.js"></script>
            <script>
                $(document).ready(function () {
                    // Example usage
                    $.popup({
                        message: 'This is an info popup!',
                        duration: 3000,
                        type: 'info'
                    });
                });
            </script>
        </body>
    </html>
    ```
    This will display an info popup with the message "This is an info popup!" for a duration of 3000 milliseconds (3 seconds).
2. Customize the options according to your requirements:

- `message` (string): The message to be displayed in the popup.
- `duration` (number): The duration in milliseconds for which the popup should be displayed. (Default: 5000 milliseconds)
- `type` (string): The type of the popup, which determines its appearance. Valid values are 'info', 'success', 'danger', 'primary', or any other custom class defined in your CSS. (Default: 'info')

