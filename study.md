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
-   [SPA and the Single Page Myth](https://johnpapa.net/pageinspa/)

## Define "single-page application" (SPA)

In your own words, define what a SPA is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
Single page application: It is a web app that is only on a single page. The UI is
able to be updated without refresh and without sending a request to the server
to update the HTML. After the page initially loads, the client takes over.
Most of the changes that happen after the initial page load are client side.

http://singlepageappbook.com/goal.html
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before you started
your search to define SPAs?

```md
When users say "page", they often mean the total of what they see on the screen,
on the app's UI. This is what I thought it had meant until I read the article.

https://johnpapa.net/pageinspa/

```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
Views are are everything the user sees, often erroneously referred to as "pages".
It is only correct to refer to a "page" when a view occupies the entire screen.

View state refers to the part of the app that changes visually (such as clicking
on a drop-down menu)

Routing means that you can interact with a specific view in the app (such as a
drop-down menu), without the app needing to communicate with the server.

https://johnpapa.net/pageinspa/



```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
They are good for responsive sites. The URLs are resolved on the server on the
first request and load by ajax on any further requests.

Rendering HTML takes up a lot of resources. The rendering happens much more quickly when
executed on client side instead of server side.

When pressing the button, you can access your previous view through AJAX "promises"
instead of having to wait a bit longer for the page to relaoad.

They are easy to debug with Chrome, as you can examine page elements and associated data.

It can run on any platform or device.


http://stackoverflow.com/questions/21862054/single-page-application-advantages-and-disadvantages
https://www.quora.com/What-are-the-advantages-of-SPA-single-page-application-over-a-normal-web-application
https://johnpapa.net/pageinspa/
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
AngularJS, Ember.js, Meteor.js, Ajax

https://en.wikipedia.org/wiki/Single-page_application#Technical_approaches
```
