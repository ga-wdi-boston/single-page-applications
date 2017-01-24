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
SPA use AJAX nad HTML5 to create web apps without loading page repeatadly. Separates UI - client side from backend - server side.
https://msdn.microsoft.com/en-us/magazine/dn463786.aspx

One my single page works without AJAX:
It runs from one file - usually index.html file. It can have a navigation with several bars as such as home about contact but when the user clicks it will not move to another html file rather stays on index.html. It will just start to read different <section> depends on how html is structured. It can be <div> tag instead. Usually into <a> tag goes under the href some id #some. <a href="#some"></a>


```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
Users usually mean by page the tab in the browser with some link rendered I think.

I have done some projects before with several or caled single page so I thought that the single page is one file with .html. Usually index.html, other pages can be called about.html contact.html etc. But ajax solution is much more pro.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
View are the "other pages" after the first page loads. Other pages are HTML fragments that offers a distinct set of functionality to the application.
https://johnpapa.net/pageinspa/

Views are components that are reusable and consist of a template and an object. View states are probably controllers responsible for a particular application state.
```
http://singlepageappbook.com/detail1.html

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
It's lightweighted - less files rendering, a faster load. Easer to update the application later because the development parts are logically separated.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
angular, durandal, ember

https://johnpapa.net/pageinspa/
```
