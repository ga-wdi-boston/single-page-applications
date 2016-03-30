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

Single page applicatoin is either a web app or website that uses a single web page and can be dynamically updated.  All necessary components, html, css, js files are retrieved as a single page load as first.  The page can subsquentially be updated as needed, which mean that it is not necessary to completely reloading the html everytime.

source: wikipedia, msdn
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
Pages here usually mean a web documents that can be retrived from the web to your computer thru you webbrowser.  The web documents are usually written in html or other languages.  It contain all the informations, such as contents, style, scripts, that is necessary to represent a webpage.

source: wikipedia
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
<!-- your answer here -->
The view is the output representation of information, in this case, think of it as user interface generated from the html markup.  The viewstate store the parts of framework/data that is necessary to preserve the pages, but not necessary to be send back and forth to the API server.  So in SPA, view state will be the parts that is not being dynamically updated, but they are important to store as they are needed for the markup.  If we think of the router is facilitating "route" or communcation between the view on your computer and the url, it need to determine what information need or not needed to be send back and forth, so it basically determine and set the view state (?).

```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
<!-- your answer here -->
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
<!-- your answer here -->
```
