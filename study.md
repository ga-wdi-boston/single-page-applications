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
A SPA is a web application that loads a single HTML page from the server and
dynamically changes its user facing view depending on the user's activity on
the page.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
When Non-developers/users say "page, they mean a distinct looking page on the web.
I saw pages like this too. Users use that word in a conceptual way. Developers
are very literal. A meaning word like "page" tends to be understood in its
literal, technical context-- for instance, any file that has the extension .html
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
The user's understanding of a "page" translates directly to the developer's
concept of a view. With single page apps, the user's "pages" are just
different "views" supported in the single HTML.

I think view-state is a snapshot of what the view looks like with all the
applicable data. Users expect their applications to automatically work with
their browser's back button and forward button (front-end "routers").
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
SPAs are more responsive. In older apps where each view was an HTML file
on a server, rendering those pages required a roundtrip call to the server.
Single page apps don't need to do that since the initial page is all it needs.

```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
html5, css, javascript, ajax
```
