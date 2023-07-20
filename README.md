# Escape Html

HTML Escape is a tool for HTML escaping process. When escaping, it replaces special HTML characters with their HTML equivalents (entities).

## For example

if you need to post a piece of HTML/JavaScript code in your article/blog post/any other HTML document, you need to escape it to make browsers don't treat it as HTML.

```html
<h1>I'm big BAD HTML</h1>
<script>
  alert("your hacked");
</script>
```

HTML Escape process replace all HTML reserved chacaters `(<, >, &, ")` to `(&lt;, &gt;, &amp;, &quot;)`.

And the result will be as follows.

```html
&lt;h1&gt;I'm big BAD HTML&lt;/h1&gt; &lt;script&gt;alert(&quot;your
hacked&quot;);&lt;/script&gt;
```

## Code info

HTML, JavaScript, Bootstrap Css

Readme.md created with [readme.so](https://readme.so/).

## Roadmap

[x] Add single quotes (') option with checkbox

[ ] Publish

[ ] Add Unescape (reverse) process.
