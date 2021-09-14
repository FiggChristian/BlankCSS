# BlankCSS

BlankCSS is a collection of CSS stylesheets that aim to make some kind of image or page, using a completely blank HTML document with no added elements other than the default `<html>` and `<body>`.

This serves no practical purpose other than to try to be clever and creative with CSS and learn cool new ways to use it.

### Rules:

1. No extra HTML elements can be used or appear in the page other than the browser's default `<html>` and `<body>` elements (and the `<head>` since it only holds metadata like the stylesheet and cannot be styled by CSS).
2. No `background-image`s other than `radial-` or `linear-gradient`s since images are basically cheating and don't require the same kind of creativity and CSS know-how.
3. `::before` and `::after` pseudo-elements are allowed to be used since they keep the blank-HTML-document requirement intact and are only targeted/used in CSS.