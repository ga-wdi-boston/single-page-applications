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
SPA's are websites that offload most of their information/processing to the client.
Rather than loading each page in a separate window they can reload the current view
to have new content, and even store the content in memory to reduce traffic back to
server.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
Users think of a page as a singular block of content viewable at one time, found
behind a single url, which is how I thought of them before this.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
Views in SPA's are basically what most people would think of as a "page".  I found
a definition of view state here(https://www.codeproject.com/Articles/31344/Beginner-s-Guide-To-View-State),
which looks to be a little outdated, but according to that it's the concept of
storing user variables on the client.  Front end routers allow the content of
the viewed area to change when navigated by menus while keeping other parts of the
user interface intact.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
SPA's feel more responsive, since they don't require the same load times from the
server.  Additionally, it's easier to write them in smaller pieces, which can be
tested individually.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
The sources for this study in particular suggested angular.js and node.js as being
the best/post prevalent.
```
