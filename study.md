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

A single-page application is a web application that lets users do everything
they need/want/can do within the app without reloading the page. SPAs use AJAX
to send/retrieve data to and from the server and update the page dynamically.

Citations: MSDN SPA

```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md

What loads within the browser window when you visit a specific URL; a single
"view.

Citation: SPA and the Single Page Myth

```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md

A "view" is what non-developers think of as a "page" or a "screen." Views are
blocks of HTML that offer the display elements necessary for a specific piece
of functionality—like signing in, or navigating the app, or reviewing a list
of movies the app has returned based on a user's search specifications.

"View-state is (I think?) a collection of data that represents/describes the
"current state of your view within the browser. It might also be the term used
"to refer to the current state of the view. State encompasses client-side
"settings that affect the view. For example, you might make an AJAX request
"for all of the movies in a database, and then have filtering functionality on
"the client side that lets the user choose which genre of films they want to
"browse. Their choice of genre would be part of the current state.

Front-end "routers" match a URL with sending/receiving of any necessary data
and the display of the correct view(s). These routers can connect different
URLs with different view states (building on the previous example:
movies/comedy and movies/drama) and show the appropriate data/view to the
user.

Citations:
- SPA and the Single Page Myth
- ["Temporary UI State" tutorial in Meteor](https://www.meteor.com/tutorials/blaze/temporary-ui-state)
- a bunch of not-so-helpful ASP.NET articles
- [Route Configuration with React](https://github.com/reactjs/react-router/blob/master/docs/guides/RouteConfiguration.md)
- [AngularJS State Management with ui-router](http://txt.fliglio.com/2013/05/angularjs-state-management-with-ui-router/)


```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md

SPAs let us avoid reloading pages, which makes the user experience more fluid
and can improve performance by minimizing communication with the server. They
also neatly separate the display from the logic.

Citations: MSDN SPA, SPA and the Single Page Myth
- 

```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md

At their core, SPAs are built in HTML, CSS, and JavaScript. JavaScript
frameworks (like Meteor, Angular, or Ember) make the process easier. AJAX is
used to communicate with the server and send/retrieve data.

```
