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
For button styling, there are several steps you have to follow to make it work.
There are 3 different types of buttons:
- `class="button--basic"` for basic button
- `class="button--reversed"` for basic button, but with reversed colors
- `class="button--noclick"` for a no-clickable button
There are shared properties between these buttons, they are written in `class="button"`
So if you want to use any of these buttons, use tag `<a>` and add class like in an example:
```html
<a class="button button--basic">Button</a>
```
## Lists
There are two types of lists. Ordered list `<ol>` and unordered `<ul>` list. `<li>` is an item in both of them. In this library, styled lists have for example bigger space between lines and bold numbers in the beginning of a list.
This is just an example, how to create ordered and unordered lists:
### Ordered list
```html
                <ol>
                    <li>Programming Languages
                        <ol>
                          <li>C</li>
                          <li>C++</li>
                          <li>Java</li>
                          <li>Python</li>
                        </ol>
                    </li>
                    <li>Web Technologies
                        <ol>
                          <li>HTML</li>
                          <li>CSS</li>
                          <li>JavaScript
                            <ol>
                                <li>React</li>
                                <li>Angular</li>
                                <li>Vue</li>
                            </ol>
                          </li>
                          <li>Bootstrap</li>
                        </ol>
                    </li>
                </ol>
```
### Unordered list
```html
                <ul>
                    <li>Milk</li>
                    <li>Flour</li>
                    <li>Eggs</li>
                    <li>Bread
                        <ul>
                            <li>Wheat</li>
                            <li>Wholegrain</li>
                        </ul>
                    </li>
                    <li>Sugar</li>
                </ul>
```
## Table
A table in TypoLib is styled with simplicity and to make your info nicely structured.
When creating a table, there are several tags we can use. Here they are with their usage:
- `<table>`: Defines a table.
   
- `<caption>`: Provides a table caption.

- `<thead>`: Groups table header content.

- `<tbody>`: Groups main table content.

- `<tfoot>`: Groups table footer content.

- `<th>`: Defines a header cell.

- `<td>`: Defines a data cell.

- `<tr>`: Defines a table row.

Here is an example of a usage in a code:
```html
                <table>
                    <caption>Table of data</caption>
                    <thead>
                        <tr>
                            <th>Name</th>
                            <th>Job</th>
                            <th>Salary</th>
                            <th>Drivers licence</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Martina</td>
                            <td>Assistant</td>
                            <td>35K</td>
                            <td>Yes</td>
                        </tr>
                        <tr>
                            <td>Sarah</td>
                            <td>Teacher</td>
                            <td>40K</td>
                            <td>Yes</td>
                        </tr>
                        <tr>
                            <td>Eric</td>
                            <td>Manager</td>
                            <td>85K</td>
                            <td>Yes</td>
                        </tr>
                        <tr>
                            <td>Peter</td>
                            <td>Marketing Specialist</td>
                            <td>65K</td>
                            <td>No</td>
                        </tr>
                    </tbody>
                </table>
```
## Photos
