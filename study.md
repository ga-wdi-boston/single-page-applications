<!-- # Single-Page Applications Study -->

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
SPAs page do not need to reload when interacted with nor does control transfer to another page. They use "views" that are essentially pre-loaded (with a one time request from the server) to emulate new pages, or just fragments of HTML that must be utilized.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
To a non developer, every time the view is occupies the enitre page, you have now entered a new page. The “Go to the order entry screen” example is a perfect analogy. It is a view they are looking at not a new page.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
views really mean that an HTML fragment that offers new functionality to the application has come onto the "page." This may be something that does not encompass the whole broswer view but certainly can. SPA supports the concept of routing (using the appropriately named "router" to do so). The router allows a user to go from one "view point" to another within the browser by clicking a certain element.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
Users can have richer interactions with the application due to the mailiable nature of SPAs. They are fluid and do not need regualr page loads to run with their full functionality.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
AJAX and HTML5 (they usually return data in JSON format)
```
