# Mailspring Predawn UI theme

A dark UI theme for the [Mailspring](https://getmailspring.com/) email client. This theme is a fork of the [Nylas N1 Predawn UI theme](https://github.com/adambmedia/N1-Predawn) by [Adam Boulanger](https://github.com/adambmedia) and is extensively based on the [Sublime/Atom Predawn UI theme](https://github.com/jamiewilson/predawn) by [Jamie Wilson](https://github.com/jamiewilson).

![Screenshot](ui-predawn-screen.png)

# Installing

1. Download the [Mailspring](https://getmailspring.com/) email client.
2. Download or clone the latest version of the Predawn UI theme from <https://github.com/asparc/ui-predawn>.
3. Make sure that the name of the folder containing the Predawn UI theme is `ui-predawn`, as otherwise Mailspring won't recognize it.
3. Open `Mailspring > Edit > Install Theme...` and select the folder you just downloaded.
4. Enjoy a dark theme that's easy on your eyes.

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