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

## Define "single-page application" (SPA)

In your own words, define what a SPA is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
A single page application is a web page that changes dynamically as changes are made, rather than only changing when refreshed. It also allows for a separation between the html display and the logic behind the scenes.

Resource:
https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
When users say "page" they generally mean something they had to cick a link or enter an address to go to, or the appearance visually differs from the initial "screenshot". For example, a login box might be perceived as a page even if it's just overlaid across the application.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
When developers say view, they mean the rendered display of the html elements.  When developers say view state, they mean the values of the page which are maintained during back and forth communication with the server. Routers help manage view state by tracking the users's location, since urls cannot be relied upon anymore for this. The routing library defines the paths through the SPA. 

Resources:
https://docs.cozy.io/en/hack/getting-started/learn-single-page-app-way.html
https://msdn.microsoft.com/en-us/library/ms178198(v=vs.85).aspx
http://appendto.com/2014/02/edisonjs-organized-routing-for-complex-single-page-applications/
```
