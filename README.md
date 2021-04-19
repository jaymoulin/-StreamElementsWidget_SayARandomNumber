# Channel Point Redeemer

Displays a video/image and plays a sound when channel points are redeemed.

[![PayPal donation](https://github.com/jaymoulin/jaymoulin.github.io/raw/master/ppl.png "PayPal donation")](https://www.paypal.me/jaymoulin)
[![Buy me a coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png "Buy me a coffee")](https://www.buymeacoffee.com/jaymoulin)
[![Become a Patron](https://badgen.net/badge/become/a%20patron/F96854 "Become a Patron")](https://patreon.com/jaymoulin)

# Install

1. Create a custom widget
1. Open editor
1. Paste `index.html` content in HTML code
1. Paste `index.css` content in CSS code
1. Paste `index.json` content in fields code
1. Compile `index.js` into `bundle.js` with browserify (just do `make build` if docker and makefile are both installed)
1. Paste `bundle.js` content in JS code

# Settings

You can define a specific title with this peculiar values:

- `{number}` to display given number

Only streamer is available to throw the !d<number> command