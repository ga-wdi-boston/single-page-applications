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
A Single Page Application (SPA) is a web application that loads into a client
browswer with a single initial page load. From that point forward, any updates
to the user experience are a result of AJAX requests to the server that
communicate any changes to the program data. The application on the client
side handles any user interface changes required as a result of data updates
without making explict calls to the server to refresh the "page".
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
When users refer to a "page", they are traditionally referring to a view into
a web application. For traditional web sites, this means a full html page with
navigation, content, and interactivity. For sites that include private data,
such as a customer service portal or corporate intranet, the web-based
experience can feel more like a desktop application with more updates being
handled in-page instead of requiring page loads. I've been exposed to both
types of sites before, so the concept is familiar.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
A "view" is an fragment of HTML used in SPAs that renders what would be
considered a page in a traditional website. Since views in SPAs are often
composed of multiple, smaller HTML components that can be modified
independently, these smaller components are known as "view-states". A front
end "router" maps combinations of view states to given paths so that users
can navigate to a given view through URLs or in-application navigation.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
SPAs can be more dynamic and responsive to the user than traditional page-
based applications without requiring multple page reloads as the user interacts
with the application. SPAs also enable effective separation of the presentation
layer and the back end thorugh the use of JSON to transfer data.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
AngularJS, Ember.js, and Meteor.js are three JavaScript frameworks that are
designed specifically to build SPAs. These use AJAX to send and receive JSON between the client and server. 
```
