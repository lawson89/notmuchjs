---
hide:

- navigation

---

# Htmx

## Introduction

[Htmx](https://htmx.org) is a relatively new project but was born out of
experience gained by founder Caron Gross with a previous project - intercooler.
Htmx is framework agnostic but has been enthusiastically embraced by the
Python (and particularly) the Django community. It has grown quickly in
popularity over the last year.

At it's core htmx allows access to ajax, css transitions, websockets and SSE via
html attributes. Htmx emphasizes:

1. Hypertext as the engine of state (server side state)
2. Progressive enhancement
3. [Locality of behaviour](https://htmx.org/essays/locality-of-behaviour/)

## At a glance

|||
|---|---|
|Project site| [htmx.org](https://htmx.org) |
| License | BSD 2-Clause "Simplified" License |
|Repository | [github.com/bigskysoftware/htmx](https://github.com/bigskysoftware/htmx) |
| Stars | ![](https://img.shields.io/github/stars/bigskysoftware/htmx?style=social) |

## Consider If

:octicons-checkbox-24: A backend agnostic framework is important

:octicons-checkbox-24: You can take advantage of pre-built integrations (Django,
Flask)

## Example code

The use of attributes to trigger an Ajaz action is seen below (taken from
htmx [introduction](https://htmx.org/docs/#introduction))

```html

<button hx-post="/clicked"
        hx-trigger="click"
        hx-target="#parent-div"
        hx-swap="outerHTML"
>
    Click Me!
</button>
```

When a user clicks on this button, issue an HTTP POST request to `/clicked` and
use the content from the response to replace the element with the
id `parent-div` in the DOM

## Integrations

Please help to add more!

| Framework         | Link  |  
|--------------|------------|
| Django | [django-htmx](https://django-htmx.readthedocs.io/en/latest/)      | 
| Flask  | [flask-htmx](https://pypi.org/project/flask-htmx/)

## Courses

| Course         | Link  |   Free/Pay |  
|--------------|------------|----------------|
| HTMX + Flask: Modern Python Web Apps, Hold the JavaScript Course | [Talk Python](https://training.talkpython.fm/courses/htmx-flask-modern-python-web-apps-hold-the-javascript)     | $ |

## Articles



