---
title: Web Publishing Part 1 - HTML
date: 2018-05-3 22:49:09
comments: false
---

## Web Publishing Part 1 - HTML

> Author: Zhenghao Wu
> 
> Last edited on 28 April 2018
> 
> For CPGU IT Tutorial Class (2018 Spring)

### Basic Information

- HTML (Hypertext Markup Language)
- HTML consists of **elements**, each of which may be modified by some number of **attributes**.

```html
<tag_name attribute1="item1" attribute2="item2"> Contents </tag_name>
```

### Document

- `<html>`
  The HTML `<html>` element represents the root (top-level element) of an HTML document, so it is also referred to as the root element. All other elements must be descendants of this element.
- `<head>`: provides general information (metadata) about the document, including its title and links to its scripts and style sheets.
- `<title>`: Defines the title of the document, shown in a browser's title bar or on the page's tab.
- `<body>`: There can be only one `<body>` element in a document.

example:
```HTML
<html>
  <head>
    <title>Document title</title>
  </head>
  <body>
    <p>This is a paragraph</p>
  </body>
</html>
```

#### Content sectioning
Content sectioning elements allow you to organize the document content into logical pieces.

- `<h1> <h2> <h3> <h4> <h5> <h6>`: represent six levels of section headings. `<h1>` is the highest section level and `<h6>` is the lowest.

#### Text content
Placed between the opening `<body>` and closing `</body>` tags.
These elements identify the purpose or structure of that content.

- `<p>`
- `<hr>`
- list
  - `<ul>`: unordered list of items, typically rendered as a bulleted list. 
  - `<ol>`: ordered list of items, typically rendered as a numbered list.
  - `<li>`: an item in a list. It must be contained in a parent element(`<ul>` or `<ol>`).


#### Inline text semantics
Use the HTML inline text semantic to define the meaning, structure, or style of a word, line, or any arbitrary piece of text.

- `<b>`
- `<i>`
- `<u>`
- `<s>`
- `<br>`
- `<a>`: anchor
  - `href`: Contains a URL or a URL fragment that the hyperlink points to.
  - `target`: Specifies where to display the linked URL.
    - `_self`: Load the URL into the same browsing context as the current one. This is the default behavior.
    - `_blank`: Load the URL into a new browsing context. This is usually a tab, but users can configure browsers to use new windows instead.
    - `_parent`: Load the URL into the parent browsing context of the current one. If there is no parent, this behaves the same way as `_self`.
    - `_top`: Load the URL into the top-level browsing context (that is, the "highest" browsing context that is an ancestor of the current one, and has no parent). If there is no parent, this behaves the same way as `_self`.

example:
```HTML
1. Linking to an external location
<a href="https://www.mozilla.com/">External Link</a>

2. Creating an email link
<a href="mailto:nowhere@mozilla.org">Send email to nowhere</a>
```

#### Image

- `<img>`
  - `alt`: the alternative text describing the image.
  - `src`: The image URL. **This attribute is mandatory for the `<img>` element.**
  - support formats: jpg, gif, png, svg, bmp, etc.

Sample:
```html
1. An image
<img src="mdn-logo-sm.png">

2. An image with Alternative text
<img src="mdn-logo-sm.png" alt="MDN">

3. Image link
<a href="/"><img src="mdn-logo-sm.png" alt="MDN"></a>
```

#### Table content

- `<table>`
  - `<thead>`
    - `<th>`: table head
  - `<tbody>`
    - `tr`: table row
    - `td`: table data
- `colspan`

example:
```HTML
<table>
  <thead>
    <tr>
      <th>Student ID</th>
      <th>Name</th>
      <th>Major</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>3741255</td>
      <td>Jones, Martha</td>
      <td>Computer Science</td>
    </tr>
    <tr>
      <td>3971244</td>
      <td>Nim, Victor</td>
      <td>Russian Literature</td>
    </tr>
    <tr>
      <td>4100332</td>
      <td>Petrov, Alexandra</td>
      <td>Astrophysics</td>
    </tr>
  </tbody>
</table>
```

#### Absolute Path & Relative Path
The path with reference to current directory is called relative. The path with reference to root directory is called absolute. 

One has to be calculated with respect to another URI. The other does not.

```html
Completely relative:
<img src="uic.png">

Absolute in all respects:
<img src="http://uichcc.com/images/uic.png">
```

reference:
> [Mozilla MDN web docs](https://developer.mozilla.org)
> [StackOverflow](https://stackoverflow.com)

### 接下来

[返回上一层](../../) | [下载PDF版](html.pdf)