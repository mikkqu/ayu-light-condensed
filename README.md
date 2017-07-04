# ayu Bright Condensed

Modification of ayu Sublime Text 3 theme

![Screenshot](http://i.imgur.com/0UehD5H.png?3)

## Motivation

I've been looking for a UI theme that would satify all my requirements and `ayu` turned out to be closest one.

However, some parts were controversial in my opinion such as:
- Some UI elements are too sparse
- Font choice for code is questionable and not consistent (Roboto Mono)
- Colors could be tweaked a bit to look better

So I decided to use it as a reference and to rework it to make it fit perfectly to my taste.

A bunch of corrections were made:
- Combined bright and dark background for sidebar and main area
- Make consistent use of Menlo font (included in OS X since 10.6) all over the theme
- Changed CSS properties for pretty much every element, fixed spacing between elements
- Changed section layout of a sidebar

If you have the similar feel of beauty, you probably may save youself from some frustration.
Check this out and see if you like it as much as me.

## Installation

1. Move the directory inside your sublime `/Packages` directory. *(Preferences > Browse packages...)*
2. Put these two lines into your Preferences.sublime-settings

```json
    "theme": "ayu-light.sublime-theme",
    "color_scheme": "Packages/ayu/ayu-light.tmTheme",
```

3. Enjoy your new Sublime Text look.
