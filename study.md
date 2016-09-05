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
A single-page application, or SPA, is a web app that only loads _one_ HTML page,
and then dynamically updates that page with new information from the server based
on the user's interactions, without ever refreshing that main HTML page.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
Most users would define "page" as the HTML they see when they load a website. If
that HTML changes (eg if we type a different word in the search bar on Google),
the user would be inclined to say the _page_ changed, even if it only dynamically
updated and never refreshed. This is about how I would have defined it before we
started learning about this anyway!
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
'Views' are another word for bits of HTML that make up what the user usually
calls 'pages'. These HTML bits typically have their own distinct set of functionality,
and mutliple 'views' can be visible on a single page at time (a nav bar 'view',
a content 'view', a sidebar 'view'...)

The view-state, then, is any particular assembly or combination of views, that can
be represented in the URL path (sometimes, though they can be too long for a URL).
I think. This is the best definition I could come up with, even with Google at my side.

The front end 'routers' take the URL from a button click and translate it
into a 'view' to be displayed.

Resource: http://www.c-sharpcorner.com/UploadFile/225740/what-is-view-state-and-how-it-works-in-Asp-Net53/

```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
One huge advantage is that SPAs don't have any page refreshes, meaning they offer
a much smoother experience for the user, as well as cutting down on any server-side issues.
They also let developers seperate the design of the site from the logic, meaning
we can rewrite the design without worrying the functionality will be too adversely affected.
Finally, as part of this seperation, both the front end or the back end can be entirey
rewritten and redesigned, but as long as the API stays the same, the functionality will
not be affected.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
Ember.js, Angular.js, ASP.NET, Node.js
```
