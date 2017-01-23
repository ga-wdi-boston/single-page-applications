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
Single-page apps are web applications that use javascript and AJAX to dynamically alter a single HTML page without the need for constand refreshes.

All presentation logic happens on the client system.
- https://johnpapa.net/pageinspa/
- https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
Users may mean anytime something meaningful changes on the screen. When I though of a page before this study I though of the current state of the DOM- without reloading or moving to a new part of the app.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
Views refer to the different HTML fragments that get rendered as a user interacts with different parts the application. The view state, refers to the views that are currently being displayed to the user. Routers can create a "map" of how a user can navigate through an app. The routes in the router correspond with different template files which make up the views and can load dynamic data.

- https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
- http://singlepageappbook.com/goal.htmls
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
The biggest advantage of a SAP is that it provides a more fluid and native-like experience to the user by minimizing page loads.

- http://singlepageappbook.com/goal.html

Some disadvantages of SAPs are:
- Page load speed. SAP tend to have/need more code to run which increases initial load time.
- SEO. Because the app requires such reliance on Javascript to change it's state, traditional techniques to improve SEO cannot be relied on.

- https://en.wikipedia.org/wiki/Single-page_application#Challenges_with_the_SPA_model
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
Javascript, jQuery and many other various JS frameworks like Ember.js or React do the heavy lifting of creating a single page web app.

- https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
```
