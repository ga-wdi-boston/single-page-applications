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
A single page application is one where the HTML "page" is loaded once by the server, and any changes made to it thereafter are done using Javascript that dynamically reacts to the client, sometimes using asynchronous calls to the server for resources such as additional HTML snippets or CSS styles.  Though SPA's communicate with the server, this is not the same as a web app that refreshes the page with a request for a new HTML document for each content page, more clearly called a "view," because it is what the user sees and interacts with.
References:
ASP.NET's resource on SPAs https://msdn.microsoft.com/en-us/magazine/dn463786.aspx.
Wikipedia - Single Page Application
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
Users generally refer to a "page" as a section of content that fills their screen, like a page on a book that they would have to "turn" or change by clicking to go somewhere else.  I have referred to a web page both as an individual view or 'content page', but also as a generic term for a web site which could include many views of content. 
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
What a view is somewhat depends within which framework you are describing it.  Within the MVC context, it is generally that which the user sees.  The user then interacts with the controller which makes changes to the model, which then ultimately updates the view to complete the circular control loop.  
However, within a Model View View-model framework, the view is still what handles the display layer of what the user sees, but it instead interacts back and forth with the view-model, which talks back and forth with the model (a representation of our data)
References:
Wikipedia: model-view-controller, model-view-view model
https://msdn.microsoft.com/en-us/library/hh848246.aspx
```

## Define the advantages of an SPA over a traditional application

What are the disadvantages of a single page application over a traditional appliction?

```md
Advantages: Making a web app Single Page allows for a more seamless experience since most of the logic is handled on the client-side, so this eliminates the need to constantly be requesting to the server for entire new HTML documents to load.  Using SPAs also allows greater deployment flexibility because you do not need to worry as much about how particular browsers will handle your web app's javascript (this more closely follows the philosophy of separation of concerns and allows us to write more robust tests for our apps as well).  It might also make it easier to wrap an application originally written as a web app as a standalone (offline) desktop app, since none of the logic is handled on the server side.  

Disadvantages: It can be tricky to accurately coordinate the asynchronous callbacks in a web app to happen at the right timing with respect to each other.  There is a bit more complexity and work up-front.  A traditional application might have an advantage if one of its pages fail, it might not have a catastrophic effect on the other pages of the website, whereas with an SPA, the interconnectedness of the whole web app could cause failures to propagate throughout the whole application.  
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
Technologies: HTML5, which implements push states; asynchronous server calls (AJAX); MVC or MVVM frameworks; HTTP
Tools: Backbone, Ember, React, Angular, Meteor, etc.
```
