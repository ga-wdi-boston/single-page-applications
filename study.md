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
A SPA is a web app that exists on one page, and one that does not require page
reloads to update the user interface. The way developers are able to build SPAs
is by utilizing AJAX and HTML5 (per first required reading). There is a model
layer (handles data) and a view layer (interprets from the model) which allow
for the UI to be updated without browser page refreshes.

Citations: All three required readings

```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
A page in a non-development environment is one single page view or landing page
with text/images/other data. I thought it meant a website with only one page,
which would be the page the user sees and interacts with. That is wrong!
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
Views are the subsequent pages outside of the initial page render from the
server in an SPA. Any time new HTML is introduced that adds new functionality
this would constitute as a new view. I'm not seeing specifics regarding
"view-state"... I think it is a way to describe whether the changes a user makes
are updated in the current view or if there are discrepancies between the
server side and what the current user view is. It could also be a way of
indicating what the current view is that a user is on?

Routers help manage the view-state and allow users to switch between views by
utilizing buttons, scrolling, etc.

Outside citations:
https://reinteractive.net/posts/186-lessons-learnt-by-building-single-page-applications

```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
Advantages: Better UI (no page refreshes). It also makes the app more adaptable
from a development standpoint because of the separation between the HTML and
the logic. Can still have multiple views. Also, server-side rendering is hard
to implement. Also easier to adapt to different devices a user may use.

Outside citations:
http://stackoverflow.com/questions/21862054/single-page-application-advantages-and-disadvantages
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
Ember.js, Angular.js, Knockout, Durandal, Meteor.js, Ajax, MVC, JavaScript,
HTML, CSS
```
