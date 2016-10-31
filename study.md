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
A signle page application or SPA, is an application which, after initially being rendered in the browser, does not reload to update information on the page. The client requests information via ajax and the server responds with JSON formatted data.

source(s):
- https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
The visual representation of a website, currently being displayed in the browser, which can be naviagated by clicking links to go to different pages.

source(s): Me.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
A view-state, in developer terms is a functional section of the visible content, which is determined by a small amount of HTML. The view could be the entire content of what the user sees and would call a 'page'.

Front-end routers determine where to send a reqeust for information, whether its local, stored in a cache, or from the server.

source(s):
https://johnpapa.net/pageinspa/
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
The "page" is only rendered once, all other information, which creates the different views, is sent through intermediate communication between the server and the client. Views can change faster than having new pages rendered.

source(s):
- https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
- https://johnpapa.net/pageinspa/
- https://en.wikipedia.org/wiki/Single-page_application
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
Ember, Angular, Durandal, Meteor, React
source(s):
- https://johnpapa.net/pageinspa/
- https://en.wikipedia.org/wiki/Single-page_application
```
