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
<!--
SPAs are web applications that load a single HTML page that uses dynamic updates to update the page based on the user’s interactions with the application. Essentially, real-time application updates in JSON via AJAX as opposed to data markups.
-->
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
<!--
"Page" in regards to SPA refers to a full-screen view of the single web page that the server sends to the browser when the application starts. After the HTML is rendered, ajax requests can be made to the server to which the server responds with JSON in order to dynamically change the page.

Prior to reading about SPAs, I had thought that page was a simple, generic word thats used to refer to the website that is holding the user’s focus.

Sources:
https://en.wikipedia.org/wiki/Ajax_(programming)
https://en.wikipedia.org/wiki/XMLHttpRequest
-->


```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
<!--

"View": Views are the other versions (sometimes called 'pages') of the website that are associated with SPAs and are generally considered everything the user sees. Full-page views are called a page. Multiple views can be on screen at a time. Each view is a different 'fragment' of the whole that is the SPA.

"View-state": A client-side state management tool. It stores the page value at the time your information was sent annd received by the server.

"Front-end routers & servers": Front end routers help manage view-state because all of the operations associated with the page's changes are all being done by the front-end (client. They only have to load the proper files once.

https://calvinx.com/2014/05/16/interactive-web-clients-frontend-routing-or-backend-routing/


https://www.toptal.com/react/managing-view-state-with-react

http://www.codeproject.com/Articles/31344/Beginner-s-Guide-To-View-State

 -->
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
<!-- 1. Dynamic responses: Single-page applications are dynamically responsive, making the application as a whole more fluid because the user doesn’t have to reload the page and the browser doesn’t have to re-render the whole page to incorporate the changes made by the user.
2. Application Architecture: By using this method, developers will have an easier time tracking the sources of errors because it creates a ‘separation' between the presentation (HTML markup) and application logic (ajax requests plus JSON responses). This separation makes the development of an application easier and more organized because the separation allows us to develop other parts of the application without having to worry about the code that implements the app’s logic.
3. Asset Packaging: Asset packaging divides things into modules and makes sure that their run-time state is acceptable. -->
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
<!--
1. HTML
2. JavaScript
3. JSON
4. DOM
5. Asset packaging
 -->
```
