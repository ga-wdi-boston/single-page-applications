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

## Define "single-page application" (SPA)

In your own words, define what a SPA is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
A single page application is an app or site where the content of the page changes as
the user interacts with it, but does not have to reload.  All of the HTML loads initially
when the app/site is requested and then the page updates by using returned JSON from AJAX
calls without having to do full page requests.  The data being sent back and forth and the presentation to the user are separated.
A great example is Steve Mengin's portfolio, where a user only needs to scroll to load
new content.http://stevenmengin.com/
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
A page for users (and myself before this study) was basically equivalent to the page
in a book, a new set of information separate from the previous one.  For example, if
I'm shopping for some new jeans and am ready to checkout, clicking on my shopping cart
would take me to a new page.  I would input my address, then my credit car info, all on
separate pages that I could navigate through using the forward and back buttons.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
The view is what the client sees.  It is the only part that the client will interact with.
As far as view-state goes, I'm not really sure.  I couldn't find a resource that particularly
made it clear.  Hopefully we go over this on Monday.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
The user experience is more fluid in that a user doesn't have to wait for page reloads
in order to continue interacting with the content.  If a user has a slow computer, this could
mean the difference between visiting the site regularly or staying way entirely.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
Angular, Ember, and Meteor are use to create SPA's.
```
