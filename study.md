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
<!--
It's an application that loads onto a single page. As opposed to needing to reload every time it opens a new page, as in multiple page applications, it instead loads the one and alters view templates on the page to change the information there through the model you've built.


https://webcache.googleusercontent.com/search?q=cache:mswFIHcHRIMJ:https://masteringmean.com/lessons/636-Understanding-the-Singlepage-Application+&cd=1&hl=en&ct=clnk&gl=us
 -->
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
<!-- they mean the page they're seeing in the web browser, with all of the front and back ended
content merged into the single 'page' they see, like google.com or a wikipedia entry. -->
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
<!-- the view is which template of the page is being displayed and there can be many view states. 

I still have only some semblance of what view-state is. view state is a magical place where
all of these manipulations to the front and back end interections of the page/what the user sees
can be changed without reloading the page? So it's all happening client-side without making continues requests to the server? -->
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
<!-- You can load the information from the server intitially, and then the other code you've written
can manipulate that one html document to change the view state? a traditional application is instead making
constant server requests and receiving responses in order to present new information to the user, whereas
a SPA basically allows the user to manipualte the DOM through your code and layer different information and states into a single page? -->
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
<!--

jquery, ajax, html, javascript, MVC , MVVM

 -->
```
