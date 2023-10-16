[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/zprwltzm)
# Typography CSS library
**Author:** *Veronika Látová*
## Demo site
Link to **[demo](https://pslib-cz.github.io/2023-l4-web-typographic-library-VeronikaLatova/)** site for preview.
## Description
TypoLib is a free typographic library, originally created as a school project.
You can implement this library (CSS) into your HTML code and save the time you would spend with styling. This library offers a variety of styles for headings, text, lists, buttons, tables, images and even gallery (more likely a picture alignment). You don't have to worry about color palette either! TypoLib provides a pallete of colors, you can change whenever you like.

**Don't hestitate and download the file, and link it into your project (via Implementation).
Have a great time exploring!**
## Implementation
1. Download TypoLib
2. Add CSS file (library.css) into the folder with your project
3. Link this CSS file into your document's head section.
```html
<link href="library.css" rel="stylesheet">
```
## Colours
TypoLib has predefined colors. But it is up to you, whether you want to use them. If you want, you can simply change them. You will find this color palette in the beginning of the CSS file.
```css
:root {
    --darkestpurple: #1A1423;
    --darkpurple: #372549;
    --gray: #5f5d5e;
    --pink: #B75D69;
    --light: #EACDC2;
    --white: #ffffff;
}
```
## Font
Font used in this library is called: "Hanken Grotesk". You can find this font on [Google Fonts](https://fonts.google.com/). All you have to do is to copy these links and insert them into your file's `<head>`
```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Hanken+Grotesk:ital,wght@0,400;0,700;1,400&display=swap" rel="stylesheet">
```
## Headings
You can use headings from `<h1>` to `<h5>`. Font sizes are:
* `h1`: 3.25em
* `h2`: 2.75em
* `h3`: 2.25em
* `h4`: 2em
* `h5`: 1.75em
## Text
Default text has `1rem` size. Other tags you can use to make your text more interesting:
- `<b>` for **bold** text
- `<i>` for *italic* text
- `<a>` for text with hypertext link (don't forget to add "href" :D)
- `<s>` for ~~striked~~ text
- `<mark>` for colorfuly marked word or text
- `<small>` for smaller text
## Buttons
## Lists
## Table
## Photos
