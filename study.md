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
A SPA is a web app that loads a single web page with out ever reloading or
re-rendering. That being said, the user will (usually) interact with said web
app and the page will dynamically react (https://msdn.microsoft.com/en-us/magazine/dn463786.aspx)
and what is viewed on the screen will change. The app does this using HTML, CSS
and JS that use an AJAX and JSON requests to function within the browser and a
solidly built API to draw from the back-end.
(https://en.wikipedia.org/wiki/Single-page_application)
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
From the users standpoint, a 'page' is the “totality of whatever occupies the four walls of the application UI”
(Ward Bell - http://www.johnpapa.net/pageinspa/). If anything changes on the 'page', most users will assume they are going to a new 'page,' which is why most users never realize they are using a SPA.
I was completely under this impression before I started to learn in depth about SPA's.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
When developers say 'view,' they mean the current 'thing' that users are looking at.
The 'view' is the interface with which the user will interact. As the user interacts, the
browser will compile a 'view-state' which stores the information and lets the browser
react accordingly for the current view to be interacted with and actions to be taken.
The 'view-state' is represented by a unique string. Front end 'routers' are set up in order to
take the information from the view state and make things happen with that information. 
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
<!-- your answer here -->
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
<!-- your answer here -->
```
