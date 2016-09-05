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
SPA stands for Single Page Application. SPA's are web apps that load a single
HTML5 page and use AJAX and JSON to create a highly responsive and fluid
app without the need for page reloads. After the first page is initially loaded,
all interaction with the server happens through AJAX calls, which are responded
to and returned to the client with data in JSON format.

Source: https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
To the layman, a "page" generally refers to what the user is actually seeing when
navigating a website. But to web developers using the SPA approach to building apps,
the "page" really refers to a single web page that the server sends back to the
browser and is then updated on the client side.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
"View-state" is a reference to an ASP.NET framework that preserves page and control
values when you refresh a page. In other words, view-state saves information that
is specific to a particular web page. On the other hand, "view"-ing is usually a
reference to so-called "session-state", meaning all information pertains to a
specific session with a server, not with a particular web-page. Front end routers
help manage view-state by not refreshing the page when the client receivers a response
from the server side, instead interpreting and updating the JSON it receives.

Sources: http://stackoverflow.com/questions/733482/what-is-the-difference-between-sessionstate-and-viewstate
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
The main advantages of SPA's over traditional applications are ease of use and
ease of updating. Using AJAX allows the page to be updated without reloading, resulting
in quicker and more fluid response times. If structured properly, developers can update
the HTML code without interferring or corrupting the logic and style format of the
site that is being worked on.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
Some important tools used to create SPA's are JavaScript, AJAX and JSON, as well as
the architectural templates of model-view-controller and the model-view-viewmodel.
```
