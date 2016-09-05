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
A SPA, or "Single-Page Application", is a web application that starts by loading
a single page from an HTML object provided by the server. Thereafter, all
updates to the user interface are made on the client side. Even if the entire
view changes in a way the user would colloquially refer to as a "new page", this
is actually done without requesting a new HTML document from the server;
instead, the client interprets the user's request within the context of its own
logic and updates the view accordingly. It may do this by requesting new
resources from the server, but the server provides the necessary data in the
form of a JSON string, rather than in markup that explicitly defines a new page.

Sources:
-John Papa, "SPA and the Single-Page Myth"
[https://johnpapa.net/pageinspa/]
-Mixu, "Modern web applications: an overview"
[http://singlepageappbook.com/goal.html]

```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
Before starting this study, I thought of a "page" as consisting of all the
information I could reach in my web browser without clicking a link, entering a
new URL, or otherwise "navigating away". Scrolling down meant I was still on the
same page, clicking a button that brought up new information could mean I was
still on the same page, but anything that made the whole window change meant
that I was now on a different page.

```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
"View", in developer language, comes close to what the lay user means when they
refer to a 'page'. A view is any distinct part of the page, whose content or
activity can be functionally distinguished from other parts of the page. A view
may occupy part or all of the browser window.

"View-state" refers to the set of values that define a view.

"Routers" interpet user-generated events (entering data in form fields, clicking
buttons, hitting 'play' on a video) and update the view-state accordingly. The
router may do this by initiating a server request for the necessary resource(s),
or by accessing relevant data from the cache.

Sources:
-John Papa, "SPA and the Single-Page Myth"
[https://johnpapa.net/pageinspa/]
-Abhijit Jana, "Beginner's Guide to View State"
[http://www.codeproject.com/Articles/31344/Beginner-s-Guide-To-View-State]

```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
SPAs make fewer round-trips to the server, resulting in increased performance

SPAs provide better separation of concerns by unlinking front-end functionality
from back-end architecture. In other words, you can swap out your whole back end
without changing the client at all, as long as the API used to phrase server
requests does not change.

Small view changes can be written more simply and sensibly in the client logic,
instead of being forced into non-intuitive URLs in order to fit the format of a
server request.

State is stored in an abstract model in memory instead of the DOM. I don't fully
understand this distinction, but it sounds as thought it makes state easier to
access and change.

-Sources:
-John Papa, "SPA and the Single-Page Myth"
[https://johnpapa.net/pageinspa/]
-Mixu, "Modern web applications: an overview"
[http://singlepageappbook.com/goal.html]
-Mike Wasson, "ASP.NET - Single-Page Applications: Build Modern, Responsive Web Apps with ASP.NET"
[https://msdn.microsoft.com/en-us/magazine/dn463786.aspx]

```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
AJAX is a key tool for getting resources from the server without loading a new
page.

There are several popular JavaScript frameworks used to handle the view-model
interaction in SPAs, including AngularJS, Ember.js, Knockout.js, and React.

data binding is a key feature of many of the frameworks, allowing the developer
to establish a relationship between HTML elements and properties of the model.
This way, updates to the model can be immediately translated into view changes
in the UI.

-Mike Wasson, "ASP.NET - Single-Page Applications: Build Modern, Responsive Web Apps with ASP.NET"
[https://msdn.microsoft.com/en-us/magazine/dn463786.aspx]
```
