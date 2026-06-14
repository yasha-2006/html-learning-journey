# HTML Links
HTML links are created using the `<a>` (anchor) tag.
Links allow users to navigate from one webpage to another.

## Syntax

```html
<a href="URL">Link Text</a>
```

Example:

```html
<a href="https://www.google.com">
    Visit Google
</a>
```

## The href Attribute

The `href` attribute specifies the destination URL.

Example:

```html
<a href="https://www.github.com">
    GitHub
</a>
```

## Opening Links in a New Tab

Use the `target="_blank"` attribute.

```html
<a href="https://www.github.com" target="_blank">
    Open GitHub
</a>
```

## Email Links

Use `mailto:`.
```html
<a href="mailto:test@gmail.com">
    Send Email
</a>
```
When clicked, the default email application opens.

## Telephone Links

Use `tel:`.

```html
<a href="tel:+911234567890">
    Call Us
</a>
```
Useful for mobile devices.

## Linking to Local Files

Example:

```html
<a href="about.html">
    About Page
</a>
```
This opens another HTML page in the same folder.


## Linking to Different Folders

Example:

```html
<a href="../index.html">
    Home
</a>
```
`..` means one folder up.


## Links Table

*  `href` -> Destination URL 
* `target="_blank"` -> Open in new tab 
*  `mailto:` -> Send email 
* `tel:` -> Make a call 

---

## Questions

### What is the `<a>` tag?

The `<a>` tag creates hyperlinks.

### What is the purpose of `href`?

It specifies the destination URL.

### What does `target="_blank"` do?

It opens the link in a new browser tab.

### How do you create an email link?

```html
<a href="mailto:test@gmail.com">
    Email Me
</a>
```

### How do you create a phone link?

```html
<a href="tel:+911234567890">
    Call Me
</a>
```

---

## Revision

- `<a>` → Anchor Tag
- `href` → Link destination
- `target="_blank"` → New tab
- `mailto:` → Email link
- `tel:` → Phone link


