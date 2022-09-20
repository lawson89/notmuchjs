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

The use of attributes to trigger an Ajax action is seen below (taken from
intercooler [introduction](https://htmx.org/docs/#introduction))

```html
  <!-- This anchor tag posts to '/click' when it is clicked -->
  <a ic-post-to="/click">
    Click Me!
  </a>
```

When a user clicks on this button, issue an HTTP POST request to `/clicked` and
use the content from the response to replace the element with the
id `parent-div` in the DOM

## Integrations

Please help to add more!

| Framework         | Link  |  
|--------------|------------|
| Django | [django-htmx](https://django-htmx.readthedocs.io/en/latest/)      | 
| Django | [django-htmx-patterns] (https://github.com/spookylukey/django-htmx-patterns) |
| Flask  | [flask-htmx](https://pypi.org/project/flask-htmx/) |

*The resources below are not meant to be exhaustive but to give you a sense of the framework*

## Articles
- [https://www.mattlayman.com/blog/2021/how-to-htmx-django/](https://www.mattlayman.com/blog/2021/how-to-htmx-django/)

## Podcasts
Podcasts on [Htmx Talk](https://htmx.org/talk/) - scroll to bottom


## Courses

| Course         | Link  |   Free/Pay |  
|--------------|------------|----------------|
| HTMX + Flask: Modern Python Web Apps, Hold the JavaScript Course | [Talk Python](https://training.talkpython.fm/courses/htmx-flask-modern-python-web-apps-hold-the-javascript)     | $ |





