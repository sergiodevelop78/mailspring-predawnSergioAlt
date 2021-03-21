# Predawn for Mailspring

A dark theme for the [Mailspring](https://getmailspring.com/) email client, inspired by the [Predawn](https://github.com/jamiewilson/predawn) theme for Atom/Sublime Text.

<p align="center">
<img alt="Screenshot Plain" src="fig/predawn-screen-plain.png" width="70%">
<img alt="Screenshot HTML" src="fig/predawn-screen-html.png" width="70%">
</p>

# Installing

1. Download the [Mailspring](https://getmailspring.com/) email client.
2. Download or clone the latest version of the Predawn theme from <https://github.com/asparc/predawn>.
3. Open `Mailspring > Edit > Install Theme...` and select the folder you just downloaded.
4. Enjoy a polished dark theme that's easy on your eyes!

# Configuring

## Brightness suppression

Emails with white backgrounds are made less bright by the theme, to ease your eyes. If you dislike that option, open the file `styles/ui-variables.less` and change the line

    @message-filter-undo:  hue-rotate(-180deg) invert(85%);

to 

    @message-filter-undo:  hue-rotate(-180deg) invert(100%);

## Accent color

It's quite straightforward to replace the orange accent color by another color of your choosing:

- Replace all occurrences of `@orange` and `@orange-prefilter` in `styles/ui-variables.less`.
- Change the color of all orange icons in `style/images`. 

That's it!

# ToDo

- [ ] Fine-tune for MacOS (Mac users are welcome to contribute :-))
- [ ] Include calendar feature, once it's fully operational.