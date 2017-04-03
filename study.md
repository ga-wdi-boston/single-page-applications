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
Instead of pages refreshing, SPAs are built so that a user interacts with that page
without it needing to refresh.  Updates to the page are dynamic.  It's a better
experience for the user, with all user interactions handled on the client side.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
"Pages" mean individual web pages to end users (and myself before learning about
SPAs).  When navigating a site, you might go to the "about page" to learn more about
a company, or the FAQ page to see popular Questions and answers.  Pages are
something that users can bookmark and have unique URLs.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
The view is everything the user sees.  The best definition I've seen for
view-state is that it "can store the page value at the time of post back (Sending and Receiving information from Server) of your page."  You shouldn't use view state when
handing sensitive or large content. (https://www.codeproject.com/Articles/31344/Beginner-s-Guide-To-View-State)  Routers allow the user to navigate/interact with what they see on the screen.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
Resources on the page (html, javascript, css) are only loaded once, which makes
it faster than pages that need to load/reload.  Less server load, since ineractions
are done client-side.  Changes to the front-end won't impact the back-end (and vice versa).
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
Javascript, Ajax, Websockets, Server-sent events, browser plugins, XML, JSON.
```
