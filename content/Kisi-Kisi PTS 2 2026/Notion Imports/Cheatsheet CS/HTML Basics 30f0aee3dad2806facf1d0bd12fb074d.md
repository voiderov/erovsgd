# HTML Basics

Owner: Erov
Last edited time: February 25, 2026 6:06 PM

# HTML Foundations — Quick Reference

## 1. Introduction to HTML and CSS

HTML (HyperText Markup Language) is the skeleton of every webpage — it defines the **structure and content** (headings, paragraphs, images, links). CSS (Cascading Style Sheets) handles the **visual presentation** — colors, fonts, layout, spacing. They are separate concerns: HTML = what's there, CSS = how it looks.

---

## 2. Elements and Tags

Everything in HTML is an **element**, written with an opening and closing tag:

```
<p>This is a paragraph.</p>
```

- **Opening tag**: `<p>`
- **Closing tag**: `</p>`
- **Content**: what's in between
- Some elements are self-closing (void elements) like `<img />` and `<br />`
- Elements can be **nested** inside each other to build structure

---

## 3. HTML Boilerplate

Every HTML file starts with a standard skeleton:

```
<!DOCTYPE html><html lang="en">  <head>    <meta charset="UTF-8" />    <meta name="viewport" content="width=device-width, initial-scale=1.0" />    <title>Page Title</title>  </head>  <body>    <!-- your content goes here -->  </body></html>
```

- `<!DOCTYPE html>` — tells the browser it's modern HTML5
- `<head>` — metadata (title, charset, linked CSS, etc.) — not visible on page
- `<body>` — everything the user actually sees

---

## 4. Working with Text

Key text elements:

| Element | Purpose |
| --- | --- |
| `<h1>` – `<h6>` | Headings (h1 = largest/most important) |
| `<p>` | Paragraph |
| `<strong>` | Bold / important text |
| `<em>` | Italic / emphasized text |
| `<br>` | Line break |
| `<span>` | Inline container for styling a piece of text |

---

## 5. Lists

Two main types:

```
<!-- Unordered (bullet) list --><ul>  <li>Item one</li>  <li>Item two</li></ul><!-- Ordered (numbered) list --><ol>  <li>First step</li>  <li>Second step</li></ol>
```

- `<ul>` = unordered (bullets), `<ol>` = ordered (numbers)
- `<li>` = each list item, used inside both

---

## 6. Links and Images

```
<!-- Link --><a href="https://example.com" target="_blank">Visit Example</a><!-- Image --><img src="photo.jpg" alt="A description of the photo" />
```

- `<a>` creates a hyperlink; `href` is the destination URL; `target="_blank"` opens in new tab
- `<img>` embeds an image; `src` is the file path or URL; `alt` is the accessibility description (always include it!)
- Images are **inline** and **void** (no closing tag needed)