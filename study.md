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
SPAs are Web apps that load a single HTML page and dynamically update that page as the user interacts with the app.  Instead of rendering a new HTLM page each time that the web app calls the server, resulting a browser refresh, all interaction in SPAs happens through AJAX calls.  Those calls retrun data, usually in the form of JSON, and the web app uses that data to dynamically update the page.

Sources:
-Required readings
-https://www.quora.com/What-are-the-advantages-of-SPA-single-page-application-over-a-normal-web-application
-https://www.quora.com/What-are-the-best-frameworks-and-tools-to-use-for-building-single-page-jQuery-applications
-https://www.codeproject.com/Articles/31344/Beginner-s-Guide-To-View-State


```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
I think that most non-developer users would think of a "page" as the current screen that they are viewing on a website.  Prior to reading about SPAs, my thought of a page was similar to that.

Sources:
-Required readings
-https://www.quora.com/What-are-the-advantages-of-SPA-single-page-application-over-a-normal-web-application
-https://www.quora.com/What-are-the-best-frameworks-and-tools-to-use-for-building-single-page-jQuery-applications
-https://www.codeproject.com/Articles/31344/Beginner-s-Guide-To-View-State

```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md

With the MVC model, "view" displays the view model and sends user input to the view model.  In the JS MVVM framework, view is markup.  This helps to separate the data from the presentation of the data, with "view" being the layer that reads data from the models.  "View state" is a repository in an ASP.NET page that can store values that need to be retained during postback

```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md

Somde advantages are as follows:

-SPAs are fast since a browser refresh does not need to occur each time that the server is called.

-Easier to create mobile versions of desktop web apps as the back end code can be reused.

-Flexibility in UI design as the front end can be rewritten without impacting the back end.

Sources:
-Required readings
-https://www.quora.com/What-are-the-advantages-of-SPA-single-page-application-over-a-normal-web-application
-https://www.quora.com/What-are-the-best-frameworks-and-tools-to-use-for-building-single-page-jQuery-applications
-https://www.codeproject.com/Articles/31344/Beginner-s-Guide-To-View-State
-https://msdn.microsoft.com/en-us/library/ms227551(v=vs.85).aspx

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?


```md
-HTML
-CSS
-JavaScript
-jQuery
-Ajax

Some JavaScript frameworks include the following:
-AngularJS
-Ember.js
-Meteor.js

Sources:
-Required readings
-https://www.quora.com/What-are-the-advantages-of-SPA-single-page-application-over-a-normal-web-application
-https://www.quora.com/What-are-the-best-frameworks-and-tools-to-use-for-building-single-page-jQuery-applications

```
