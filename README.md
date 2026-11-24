# BabelDash sign-in page

One static page, served by GitHub Pages at
`https://ophirh1.github.io/babeldash-signin/smartthings/`.

[BabelDash](https://github.com/ophirh1/mtauto) opens a SmartThings-controlled gate from a
motorcycle dashboard. SmartThings only accepts `https` redirect URIs for its OAuth sign-in,
so the browser lands here after the rider signs in, and this page hands the `?code=` straight
back to the app (`babeldash://smartthings?code=…`), showing the code as a fallback.

It stores nothing and calls nothing; the code never leaves the rider's phone.

## Privacy policy

`privacy/index.html`, served at `https://ophirh1.github.io/babeldash-signin/privacy/`, is the
privacy policy of the Apex Dash app (the URL given to Google Play and the App Store). Keep it in
step with the app: when what the app sends changes, update the page and its date first.
