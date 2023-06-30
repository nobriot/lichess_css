# Lichess overlay for funny knights

I have made this Firefox CSS customization that I use for Lichess with
the cburnet pieces, feel free to use it too.

You need to take the contents from userContent.css and copy it in your Firefox
userContent.css. Follow the [Reddit Firefox CSS Guide](https://www.reddit.com/r/FirefoxCSS/wiki/index/tutorials/).

Images are base64 encoded in the CSS file. You can select only the knights
or black king customizations if you like only one of them.

It looks like this:

[pieces_with_customizations](./assets/pieces_with_customizations.png).

## Modify the images/assets

If you want to make derivative, feel free to take from the assets folder
and modify them. I started from the SVG, generated a large PNG that I then
modified in GIMP

When you have the PNG available, you can base64 encode it and update the CSS file.
For example:

```console
lichess_css> base64 assets/black_king.png
```
