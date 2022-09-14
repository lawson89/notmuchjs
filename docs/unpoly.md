---
hide:

- navigation

---

# Unpoly

## Introduction

[Upoly](https://unpoly.com/) was started by a Rails consultancy (makandra) who
was looking for a way to reduce their stack complexity and reduce the
maintenance burden for the sites they maintain -
see [presentation here](http://triskweline.de/unpoly-rugb/#/). Similar to htmx
they focused on extending html with attributes which allow ajax without writing
javascript. Unpoly is a very capable toolkit with a *lot* of pre-built
functionality which is probably not surprising given its roots in a working
agency.

## At a glance

|||
|---|---|
|Project site| [unpoly.com](https://unpoly.com/) |
| License | MIT License |
|Repository | [github.com/unpoly/unpoly](https://github.com/unpoly/unpoly) |
| Stars | ![](https://img.shields.io/github/stars/unpoly/unpoly?style=social) |

## Consider If

:octicons-checkbox-24: You can make use of the pre-built functionality, especially layers

:octicons-checkbox-24: A backend agnostic framework is important


## Example code

The use of attributes to trigger an Ajax action is seen below (taken from the
[unpoly tutorial] (https://unpoly.com/tutorial))

```html

<a href="front.html" class="one" up-target=".one">
    Flip
</a>
```

When a user clicks on this link, issue an HTTP GET request to `front.html` and
use the content from the response that has a class of "one" to replace the
current element with class of "one"

## Integrations

Please help to add more!

## Courses

## Articles

