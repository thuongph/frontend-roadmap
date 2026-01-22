# Tag

In HTML, a tag is used for creating an element\
`<p>` --> start tag, `</p>` --> end tag

# Attribute

An attribute extends an HTML/XML element, change its behavior or providing metadata\
Example:\
`<a href="https://github.com/thuongph/frontend-roadmap">This is a link</a>`\
href --> attribute name and the url is the attribute value

### Attribute Reflection

#### Attribute getter/setter

The default mechanism for getting and setting an attribute is the `getAttribute()` and `setAttribute()` methods of Element interface.\
Example:

```
<input placeholder="placeholder" />
const input = document.querySelector("input");

// get and set attribute placeholder of input
const attributeValue = input.getAttribute("placeholder");
input.setAttribute("placeholder", "another placeholder");
```

#### Reflected attributes

Many attributes are relfected in corresponding DOM interface\
Example:

```
<input placeholder="placeholder" />
const input = document.querySelector("input");

// get and set the placeholder attribute of input element
const attr = input.placeholder;
input.placeholder = "Modified placeholder";
```

# Case insensitivity

uppercase, lowercase and mix of both\
`<html>` = `<HTML>` = `<Html>`

# HTML entities

`&lt;` --> `<` in HTML content

# HTML comments

```
<!-- HTML comments -->

<!--
this
will
not
be
rendered
-->
```

# Whitespaces

...updating
