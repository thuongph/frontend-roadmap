# `<h1>` to `<h6>`: The HTML Section Heading

- Avoid using multiple `<h1>` elements on one page
- Prefer using only one `<h1>` per page and nest headings without skipping levels.

# `<title>`

- shown in a browser's title bar or a page's tab
- only contains text; HTML tags within the element, if any, are also treated as plain text.
- always used within a page's `<head>` block.
- for SEO purpose

# `<strong>` vs `<b>`

- `<strong>` --> semantic HTML tag, conveying importance and reserving, can play a role in SEO
- `<b>` --> purely visual

# `<pre>`

code:

```
<pre>
___________________________
  &lt; I'm an expert in my field. &gt;
      ---------------------------
          \   ^__^
           \  (oo)\_______
              (__)\       )\/\
                  ||----w |
                  ||     ||

<code>
body {
  color: red;
}
</code>
<code>
let i = 5;
if (i &lt; 10 &amp;&amp; i &gt; 0)
  return &quot;Single Digit Number&quot;
</code>
</pre>
```

==> UI:

<pre>
___________________________
  &lt; I'm an expert in my field. &gt;
      ---------------------------
          \   ^__^
           \  (oo)\_______
              (__)\       )\/\
                  ||----w |
                  ||     ||

<code>
body {
  color: red;
}
</code>
<code>
let i = 5;
if (i &lt; 10 &amp;&amp; i &gt; 0)
  return &quot;Single Digit Number&quot;
</code>
</pre>

# `<mark>`

code:

```
<mark>Pham Huyen Thuong</mark>
```

UI:
<mark>Pham Huyen Thuong</mark>

# `<sub>` & `<sup>`

- code: `C<sub>8</sub>H<sub>10</sub>N<sub>4</sub>O<sub>2` represent for:
  C<sub>8</sub>H<sub>10</sub>N<sub>4</sub>O<sub>2
- code: `<var>a<sup>2</sup></var> + <var>b<sup>2</sup></var> = <var>c<sup>2</sup></var>` represent for: <var>a<sup>2</sup></var> + <var>b<sup>2</sup></var> = <var>c<sup>2</sup></var>
