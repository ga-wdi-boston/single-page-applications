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
Single Page Application. It is a way for users to interact with a page, without
having to actually reload the page and alter the actual HTML. For instance the user
does not have to touch the back end server, but rather interacts with the page using AJAX,
inputs that way and the server returns back a JSON string as form data.
https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
<!-- your answer here -->
the user likely means the HTML document or single web page that they are currently looking at within a website.
When I said page before researching I meant referencing the exact URL of a website.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
the view is what a web user sees in their eyes.
Developers mean stateless as a view state once the server request has been made
and page has already been displayed.
Once a request is made to a router, that view state changes until the request
has a response and the response has been given back to the client. Once the client
receives their response, the "router" becomes "stateless" again.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
The user does not have to render the HTML of the page over again in a SPA, so it will
have a less back and forth sort of UX and be more fluid.
Also, you can replace the back-end server during a users input with the SPA, because
it won't need to be reached at the time, as it is handled with AJAX & JQuery.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?
JQuery, AJAX, HTTP requests from a server, HTML
```md
<!-- your answer here -->
```
