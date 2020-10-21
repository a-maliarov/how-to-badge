# How to Badge?
This repository contains information and examples on how to insert badges/shields into different markup languages. For live explanation, check out this YouTube video!

---

## Dictionary
+ **source** | **src** | **source link** - the link to the badge image (*must have*)
+ **reference** | **href** | **target** - the link to the place where user should be redirected to after clicking on the badge (*optional*)
+ **alternative** | **alt** - text that should be shown if it was impossible to get the image using **source link** (*optional*)

## Insert a badge into:
+ **Markdown**

---

## Markdown
```
# Pattern
[![Alternative](https://source.link)](https://reference.link)

# Example
[![Build Status](https://travis-ci.com/a-maliarov/pyaction.svg?branch=main)](https://travis-ci.com/a-maliarov/pyaction)
```
