# Single-Page Applications Study

Use your favorite search engine to research and answer the following questions
(no prior knowledge is expected). Strive for understanding the definitions
themselves, since you may be asked in an interview to define "single-page
applications" (SPAs) in your own words.

All your projects in this program will be SPAs, so you'll likely internalize
this defintion over time.

It might be a good idea to come back to this later and see if you'd still answer
in the same way! If you have a blog you're using to journal your experience
becoming a web developer, this might make a good article.

## Readings

-   [MSDN Single Page Applications](https://msdn.microsoft.com/en-us/magazine/dn463786.aspx) (Stop at 'Creating the Visual Studio Project')
-   [Modern Web applications overview](http://singlepageappbook.com/goal.html)
-   [Wikipedia](https://en.wikipedia.org/wiki/Single-page_application)

## Define "single-page application" (SPA)

In your own words, define what a SPA is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
A SPA is a web application that exists on one page i.e. the URL never changes.
The interactivity comes from changing the state of the one page, not from
switching to different pages.

Used knowledge I had from before.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
I think when users say "page" they probably mean a state of the page i.e. how
the page looks.

Before doing the readings I thought a page was one HTML file. I think there might
be ways to send multiple HTML files and display them all at once. I think the
key thing is that with a SPA we send all of the assets up front, and then
change the state of the page using those assets, rather than pinging the
back end server for new HTML whenever we want to render a change.

That said, I think sometimes people only load modules as needed in order to save
time while running SPAs, but the point is still that they are just downloading
modules to run on the client side in order to change the model there and update
the view. They aren't just getting the new HTML from the server.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
I think the "view" is the display i.e. the viewport, in the browser that users
are looking at. If the page hides or shows different HTML elements or different
data, the view-state is different, even though the page can be the same page.

I think front-end routers change what view-state a SPA page is in.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
SPAs have more latency when they are loaded for the first time in a session
because they have to download all of the assets. However, once they are loaded,
they have the major advantage that they don't have to reload the page every time
the state changes, so they can use things like AJAX to interact with APIs, which
could have high latency (depending on the application and on the network), without
having the useability hit from waiting for the AJAX calls to come back.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
-HTML and CSS for display.
-JavaScript for logic.
-jQuery for DOM manipulation.
-jQuery and AJAX for using APIs.
-There are also some front-end JavaScript frameworks that can save time for
developers e.g. AngularJS, Ember.js, and Meteor.js (Meteor also is back end)
```
