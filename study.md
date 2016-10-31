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
SPA - Single page applications update the web page without refreshing it.
It used Ajax and HTML. The changes are dynamically loaded to the page as
necessary.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
To me a page before I read the article meant everything on a website I saw on
my screen.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
Views are the HTML pages of your application that the end user interacts with.
View State is the method to preserve the Value of the Page and Controls between
round trips.
A Frontend-Controller collaborates with a Router to decide based on the (HTTP)
request against the application which concrete Action has to be executed and
then dispatches it.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
1. In SPA, the HTML page is static where all dynamic changes occur in the
   browser. Hence, the server processes less load.
2. SPA is fast, as resources are only loaded once during the beginning of the
   application. Only data is transmitted back and forth.
3. It works more like an app than a web page.
4. SPA is very good for highly responsive sites.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?
```md
A few technologies used to implement SPAs are
AJAX
JQuery
Angular
Ember
```
