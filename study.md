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
An SPA is a web app which relies on a skeleton html code which it loads once and then dynamically alter based on user actions.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
In layperson's terms, a "page" is essentially just any sufficiently different set of things on the web broswer, generally considered to change when things are clicked.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
A "view" as used by developers is in many ways what non-developers mean by "page": the distinct set of things being rendered by the browser window. A view-state is a way to differentiate between various different render states that are similar enough to fall under the same view but have minor differences (perhaps a menu is open or closed). Routers, as I understand them, direct certain url paths to handle certain actions, so that view-states can be easily accessed directly from a URL, and the necessary resources can be served to the client as needed.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
A single page application is faster to load and doesn't require long and complicated URLs to be able to bookmark and get back to virtually the same place ou were when you left.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
Ember, Angular, Ajax and websockets, among others (ajax and ember are two of a number of libraries that serve the same function).
```
