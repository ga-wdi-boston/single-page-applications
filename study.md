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
Single-Page Applications (SPAs) are Web apps that load a single HTML page and
dynamically update that page as the user interacts (or requests actions to the web
server) with the app.

References:
https://msdn.microsoft.com/en-us/magazine/dn463786.aspx

```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
Users are refering to the UI content for a specific URL on a client (web
browser) when they say "page".  I thought the same thing prior to reading
the SPA articles in this study.

References:
https://johnpapa.net/pageinspa/

```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
"Views" are the "other" pages in a SPA.  A SPA can have multiple "views" visible
on a single web page at any one given time (i.e. multiple tabs, sidebars, etc.).
"View-state" refers to the amount of views on a web page of which each view
contains multiple objects and variables.
Front-end "routers" help manage view-state by changing views within a SPA through
the use of client-based application menus and support for browser back and forward
buttons.  When a user clicks on a menu item, the SPA wlll translate to a different
view that will be displayed going out to the server for content only if that content
has not been displayed before (cached).

References:
http://singlepageappbook.com/goal.html
https://msdn.microsoft.com/en-us/magazine/dn463786.aspx

```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
Advantages of a single-page application (SPAs) are:
 - They are both fluid and responsive as SPA web pages don't have to continously
    reload when new data is to presented on the web page.
 - Since JSON (rather than HTML) is returned from the server in SPAs, separation of
    duty is achieved as the HTML is separated from the AJAX and JSON response
    application logic.  This separation makes it easier to design, code, debug,
    test, and refactor the application.
 - With SPAs, it is easier to separate the client from the server and replace one or
    both with a different methodology or upgrade their existing methodology at
    a later date assuming that the API does not change.

References:
https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
http://singlepageappbook.com/goal.html

```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
The folloing JavaScript framework tools can bu used to create single page
applications (SPAs):
  - Backbone
  - AngularJS
  - Ember
  - React
  - Knockout
  - Dojo
  - JavaScxriptMVC

References:
https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
https://en.wikipedia.org/wiki/Single-page_application

```
