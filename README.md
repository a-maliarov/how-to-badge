# How to Badge?
This repository contains information and examples on how to insert badges/shields into different markup languages. For live explanation, check out this YouTube video!

---

## Dictionary
+ **source** | **src** | **source link** - the link to the badge image (*must have*)
+ **reference** | **href** | **target** - the link to the place where user should be redirected to after clicking on the badge (*optional*)
+ **alternative** | **alt** - text that should be shown if it was impossible to get the image using **source link** (*optional*)

## Insert a badge into:
+ [**Markdown**](https://github.com/a-maliarov/how-to-badge/tree/main#markdown)
+ [**HTML**](https://github.com/a-maliarov/how-to-badge/tree/main#html)
+ [**RST**](https://github.com/a-maliarov/how-to-badge/tree/main#rst--restructuredtext)
+ [**Textile**](https://github.com/a-maliarov/how-to-badge/tree/main#textile)
+ [**Rdoc**](https://github.com/a-maliarov/how-to-badge/tree/main#rdoc)
+ [**AsciiDoc**](https://github.com/a-maliarov/how-to-badge/tree/main#asciidoc)
+ [**Pod**](https://github.com/a-maliarov/how-to-badge/tree/main#pod)

---

## Markdown
```
# Pattern
[![Alternative](https://source.link)](https://reference.link)

# Example
[![Build Status](https://travis-ci.com/a-maliarov/pyaction.svg?branch=main)](https://travis-ci.com/a-maliarov/pyaction)
```

## HTML
```html
# Pattern
<a href="https://reference.link">
  <img
   src="https://source.link"
   alt="Alternative"
  >
</a>

# Example
<a href="https://travis-ci.com/a-maliarov/pyaction">
  <img
   src="https://travis-ci.com/a-maliarov/pyaction.svg?branch=main"
   alt="Build Status"
  >
</a>
```

## RST / reStructuredText
```
# Pattern
.. image:: https://source.link
  :target: https://reference.link

# Example
.. image:: https://travis-ci.com/a-maliarov/pyaction.svg?branch=main
  :target: https://travis-ci.com/a-maliarov/pyaction
```

## Textile
```
# Pattern
!https://source.link!:https://reference.link

# Example
!https://travis-ci.com/a-maliarov/pyaction.svg?branch=main!:https://travis-ci.com/a-maliarov/pyaction
```

## Rdoc
```
# Pattern
{<img src="https://source.link" alt="Alternative" />}[https://reference.link]

# Example
{<img src="https://travis-ci.com/a-maliarov/pyaction.svg?branch=main" alt="Build Status" />}[https://travis-ci.com/a-maliarov/pyaction]
```

## AsciiDoc
```
# Pattern
image:https://source.link["Alternative", link="https://reference.link"]

# Example
image:https://travis-ci.com/a-maliarov/pyaction.svg?branch=main["Build Status", link="https://travis-ci.com/a-maliarov/pyaction"]
```

## Pod
```
# Pattern
=for html <a href="https://reference.link"><img src="https://source.link"></a>

# Example
=for html <a href="https://travis-ci.com/a-maliarov/pyaction"><img src="https://travis-ci.com/a-maliarov/pyaction.svg?branch=main"></a>
```

