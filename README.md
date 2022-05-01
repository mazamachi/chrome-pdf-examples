# Chrome pdf examples

Chromium generate 28,198 pages for the simple [HTML page](https://mazamachi.github.io/chrome-pdf-examples/examples/flex-gap.html).
i.e.

```html
<!DOCTYPE html>
<html>
    <body>
        <div style="display: flex; gap: 10px;"></div>
    </body>
</html>
```

Even if [another dom exists](https://mazamachi.github.io/chrome-pdf-examples/examples/flex-gap-along-with-content.html), the number of pages is 28,198.

If [some child elements exists](https://mazamachi.github.io/chrome-pdf-examples/examples/flex-gap-with-child.html), Chromium correctly generate 1 page.

If [`gap` is not specified](https://mazamachi.github.io/chrome-pdf-examples/examples/flex.html), Chromium correctly generate 1 page.
