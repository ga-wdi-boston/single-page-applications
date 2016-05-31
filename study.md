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
A single page application is a web application that has just one page that
updates as the user interacts with it, so it has a single HTML file and updates
on the client side as opposed to having the server send it a new HTML file for
the page. (used required readings)
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
Users probably think that every time a page changes, its a new page, when in fact
I would consider each unique page to have a seperate HTML file.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
A view displays the information sent to it by the server, and the view state refers
to how the page looks at a given time, since it can always be changing depending on
how the user interacts with it.  Front end routers manage the view state using jquery,
reducing the burden of communication with the server.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
It enables a faster and smoother user experience since it does not have to communicate
with the server every time the view state changes.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
jQuery, JavaScript, HTML
```
