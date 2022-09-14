## Overview

You don't need a SPA to have a great looking and functional webapp.

Whether you are a backend developer, a solo entrepreneur or just someone looking to
save time - there are more robust options for low/no js than ever before.



## What is low/no js?

Everyone is familiar with the Web 1.0 full page refresh model of development.
What's nice about it is that it's fast to develop in, leverages great mature
technologies like Django, Rails and Laravel. What's not so good is that the user
experience is not as smooth as that of a SPA.

The trouble with SPAs is that it adds a stack of equivalent complexity or
greater than your back end to your front end. You've just doubled your workload!

There is another way. First browsers have gotten much faster and so with small
payloads the user experience is almost instantaneous. Second, a new set of
frameworks has been developed that extend html to allow many SPA like
functionalities to be accomplished through markup. Third, frameworks such as
Phoenix LiveView popularized the use of persistent connections such as
websockets to stream updates to the browser.

## Common factors

1. The server is the engine of state
2. Html is extended with attributes that allow partial page updates
3. Html is passed over the wire instead of Json
