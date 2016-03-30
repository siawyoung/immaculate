# Immaculate

A beautiful, ultra-fast, AMP-compliant Jekyll theme based on Tufte CSS.

[]
[Tufte CSS](https://github.com/edwardtufte/tufte-css)

Immaculate currently includes tag support for some of the more commonly-used Tufte CSS layout options, including sidenotes, margin notes, full-width figures. Other features, such as `newthought`, can still be used by typing raw HTML in your Markdown files.

**Caveat (need hep!)**: AMP HTML does not allow form elements, including checkboxes, which are used in Tufte CSS to toggle the display of sidenotes and margin notes at smaller widths. As such, I've modified Immaculate to disable this functionality at smaller widths for the time being. It's a big deal, and I'm looking for help on emulating this functionality without using checkboxes.

## Helper Tags

Immaculate comes with a few helper tags.

```
{% image <src> <width> <height> <option?> %}
```

The `image` tag allows you to insert AMP-compliant images into the post.

`src` is the `src` attribute of the image tag.

`width` and `height` of the image must be specified, as per AMP specifications.

`option` - an optional argument which supports the following options:

- `fw` - makes the image full width
- `raw` - outputs the raw `amp-img` tag, can be used in conjunction with margin notes

##### Example usage

```
{% image https://image.com/image.jpg 1200 600 fw %}
```

```
{% youtube <id> <width> <height> <option?> %}
```

The `youtube` tag allows you to insert AMP-compliant embedded Youtube videos into the post.

`id` is the Youtube viddeo ID.

`width` and `height` of the video must be specified, as per AMP specifications.

`option` - an optional argument which supports the following options:

- `fw` - makes the video full width
- `raw` - outputs the raw `amp-youtube` tag, can be used in conjunction with margin notes

##### Example usage

```
{% youtube aj2h3h1sf 600 400 %}
```

```
{% sidenote <id> <body> %}
```

The `sidenote` tag allows you insert sidenotes into the post.

`id` is a unique identifier for the sidenote, and it can be anything - it will not show up visually.

`body` is the body of the sidenote. It can also accommodate `span`-level HTML elements (`<b>`, `<em>`, `<i>`, no block-level elements).

##### Example usage

```
This is a very long{% sidenote meh Yes, <i>very</i> long. %} sentence.
```

```
{% marginnote <id> %}
<body>
{% endmarginnote %}
```

The `marginnote` tag block allows you to insert margin notes into the post.

`id` is a unique identifier for the margin note, and it can be anything - it will not show up visually.

`body` is the body of the sidenote. It can also accommodate `span`-level HTML elements (`<b>`, `<em>`, `<i>`, no block-level elements).

You can also use margin notes in conjunction with `image` and `youtube` tags by specifying the `raw` option.

##### Example usage

```
{% marginnote yt %}
{% youtube aj2h3h1sf 350 200 raw %}
This is a <b>extremely</b> succinct example.
{% endmarginnote %}
```

## Syntax highlighting

Immaculate supports syntax highlighting, but the stylesheet is commented out by default to keep the page lean. Simply uncomment the following line in `_includes/styles.scss`:

```css
// @import 'syntax-highlighting';
```

## FAQ

*How can I use the sans-serif versin of Tufte CSS, which uses Gill Sans?*

You can override the CSS style in `_includes/styles.scss` with the font stack of your choice:

```
body {
  font-family: "Gill Sans"
}
```

## Credits

Credits to [Amplify]() for most of the AMP-related code.