# Writing an HTML Boilerplate

An HTML boilerplate is the basic starting structure for any HTML document. It contains essential elements that every webpage needs. Here's a tutorial on creating a proper HTML boilerplate.

## 1. Basic Structure

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document Title</title>
  </head>
  <body>
    <!-- Content goes here -->
  </body>
</html>
```

- **<!DOCTYPE html>**: Declares that this is an HTML5 document
- **html element**: The root element of the page with language attribute
- **head element**: Contains metadata about the document
- **body element**: Contains the visible content of the webpage

_Example_:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My First Webpage</title>
  </head>
  <body>
    <h1>Hello, World!</h1>
  </body>
</html>
```

> Tip: Always include the viewport meta tag for proper mobile responsiveness, and specify the correct character encoding with UTF-8.

## 2. Adding Essential Meta Tags

To enhance your webpage's SEO and functionality, you can add more meta tags in the head section.

_Example_:

```html
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="A brief description of your page" />
  <meta name="keywords" content="HTML, CSS, JavaScript" />
  <meta name="author" content="Your Name" />
  <title>Enhanced Webpage</title>
</head>
```

## 3. Linking External Files

Your HTML boilerplate can include links to external CSS and JavaScript files.

_Example_:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Complete Webpage</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1>Welcome to my website</h1>
    <script src="script.js"></script>
  </body>
</html>
```

For more information on HTML boilerplates and best practices, check out the [MDN HTML docs](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)

![HTML Boilerplate Structure](https://images.unsplash.com/photo-1542831371-29b0f74f9713?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)
