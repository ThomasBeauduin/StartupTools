# Visual Studio Code

## Plug-ins

- Markdown PDF
- Markdown+Math

## Settings

following code to customize headers
``` html
"markdown-pdf.header.height": "1.0cm",
"markdown-pdf.header.contents": "<div style=\"text-align: right; \">Thomas Beauduin<br />MTT Innovation Inc</div>",
"markdown-pdf.border.top": "1.0cm"
```

## Issues

Currently, markdown=pdf doesnt support latex.
``` latex
$$ \sum_{m=1}^T \frac{t}{n} $$
```