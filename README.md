# BlogEssentials
RoteMinecraftIL's blog essentials (CSS).
## How to install
Installing the blog essentials to your website is very easy.

In the `head` section of the html file, write:
``` html
<link rel="stylesheet" href="https://rotemdev.github.io/BlogEssentials/css/blog.css">
```
Or download the `blog.css` file, put it in the website folder and write:
``` html
<link rel="stylesheet" href="blog.css">
```

### Example
``` html
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://rotemdev.github.io/BlogEssentials/css/blog.css">
    <title>example</title>
  </head>
  <body>
    ...
  </body>
</html>
```
## How to uninstall
Just delete lines you added, and all of the custom html tags.

## Contribute
You are free to contribute anything to the project!

## All custom elements
### `<ar-desc>`
#### Description:
The `<ar-desc>` element is an article description element. It contains a string of text.
#### Usage:
``` html
<ar-desc>Article description</ar-desc>
```
#### Style decleration:
``` css
ar-desc {
  font-family: 'Raleway', sans-serif;
  font-weight: 300;
  font-size: 0.65em;
}
```

### `<ar-text>`
#### Description:
The `<ar-text>` element is an article text element. it contains all of the paragraphs, images, etc. of the article.
#### Usage:
``` html
<ar-text>
  <p>Hello world!</p>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed sodales ligula quis sem ultrices, eu efficitur sapien commodo. Nunc
  luctus urna quis consectetur interdum. Vivamus bibendum cursus eros. Maecenas vel fermentum leo. Cum sociis natoque penatibus et
  magnis dis parturient montes, nascetur ridiculus mus. Ut ut lectus ornare, facilisis eros eget, suscipit odio. Mauris commodo sapien
  arcu, nec vehicula libero iaculis vel. Nulla in libero velit. Etiam non sollicitudin tortor.</p>
</ar-text>
```
#### Style decleration:
``` css
ar-text {
  font-size: 0.9em;
}
```
### `<section>`
#### Description:
The `<section>` element is a built-in HTML element, restyled to be an article.
#### Usage:
``` html
<section>
  <h2 class="title">Lorem Ipsum</h2>
  <ar-desc>Lorem ipsum dolor sit amet</ar-desc>
  <ar-text>
    ...
  </ar-text>
</section>
```
#### Style decleration:
``` css
section {
  background-color: #ffffe5;
  width: 15% 85%;
}
```
