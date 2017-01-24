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

SPA’a are single page applications. All UI interaction occurs on the client side through Javascript and CSS. Client only needs to know what HTTP requests to send. Could change entire back end or entire client app - service layer doesn’t need to be changed.

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

When users say “page” they mean different layouts on a webpage that offer unique functionality. A page can consist of a continuation of an article, a log-in page, or any  distinct and contained information displayed by the browser. In addition, pages can be re-visited using the “back” and “forward” buttons. Pages in terms of SPAs are more accurately described as views where all of the information contained within the UI is loaded when the page is first visited and all other alterations of the page are done on the client side. If one were to hit a back button on a SPA all information and potential progress one accrued on a SPA would be lost.

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

A view can be though of pseudo-pages. They’re the different states or apparent pages that are constructed during a SPA experience. Views are HTML fragments that make up the different states or “pages” while the user is traversing a SPA. Views are in essence HTML fragments that offer distinct functionality to the SPA. Routers allow the user to go to different pages or views by clicking on a menu item. Routers allow for the user to access different parts of the SPA without posting to the server.

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

Several advantaged to SPAs over traditional applications are that SPAs are more fluid and responsive and do not have to reload to display new information. SPAs also offer better UX as everything needed on the client side is loaded when the page is first visited. A SPA approach is also a fast UX due to the server only sending the client information as JSON, which are small compared to HTML and other documents.

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

Libraries such as Knockout.js or Ember.js or Meteor.js. AJAX, Javascript, HTML, CSS, Angular, Durandal
