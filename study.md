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
SPA stands for Single Page Application, and describes a web application or
website that exists on a single web page. The application will load the
necessray code like HTML/CSS/Javascript once, and will retreive further
information from the server without having to reload the page.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
When users say "page", they mean any website accessed over the internet. For
example, on Gmail.com, a user may consider the page to write an email one page,
the page to view sent emails another page, and the inbox another page.
Before reading up on SPA, I thought it was a website that loads once and does
not have to reload again.

```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
In SPAs, there are multiple views, which are different versions of the single
page that, in users' perspective, each consist of different visual features on
the page. Each view consists of smaller components, called view-states.
Front-end routers allow users to click through different views
while remaining on the same page within the browrser. When a user visits a new
view, the router sends an HTTP request to retreiev new resources (HTML, etc.)
to upload the new view. Once it receives the resources, it will upload a new
view. Once a user visits a new view, the router can store a local cache of the
resources used to load the view when the user revisits. 
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
SPAs allows for a more fluid experience for users. For example, Gmail is a SPA
that allows you to click through different emails, write and send new email, and
receive new email, but the page will never reload.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
- Javascript frameworks like Ember.js and Angular JS
- Data transport tools: JSON, Ajax, etc.
```
