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
A SPA is a single page application. Pages (individual HTML files) are not reloaded fuly, i.e., the client does not send a request to the server and receive an entire html page, when navigating or if page information changes. Rather, JavaScript is used for DOM manipulation to move the information into the current single page.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
When a user thinks about a page, I think they are picturing at single container (an HTML file served to their web browser by the server) that contains data that can be grouped together, e.g., profile information for a user would be in one page and then if you clicked "friends" of that same user a the browser would make a request to a server, receive a complete HTML file, and then render the file. I thought along the same lines, i.e., a page is basically a discrete HTML file.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
The view is the current representation of the model, basically, it is the user interface and the interpretation of the current content of the model; this is what the user interacts with and manipulates. A view-state is some sort of method/system implemented to preserve the state of a page or application since HTTP is a stateless system. A front-end router updates the browser's URL without refreshing the page as a user navigates through the app; you can also view it as something that tracs the user's location while navigating the SPA since URLs can no longer be used in the same fashion.

[GitHub Director Page](https://github.com/flatiron/director)
[Stack Overflow](http://stackoverflow.com/questions/10075507/what-does-javascript-routing-buy-you)

 [Single Page App Book](http://singlepageappbook.com/goal.html)
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
Advantage: Reduction in requests to the server; better performance with client-side rendering; feels more like a traditional application (one window, no page reloads, etc.) [Stack Overflow](http://stackoverflow.com/questions/21862054/single-page-application-advantages-and-disadvantages)
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
Ember, Angular, Kendo UI, Backbone, Meteor, jQuery, AJAX, JSON [Understanding the SPA](https://webcache.googleusercontent.com/search?q=cache:mswFIHcHRIMJ:https://masteringmean.com/lessons/636-Understanding-the-Singlepage-Application+&cd=1&hl=en&ct=clnk&gl=us)
```
