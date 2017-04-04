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
SPA stands for Single Page Application. In short, a SPA is a web page that is updated based on user interaction without the user refreshing the page to see the updates that correspond to their actions. The first page/"load" will be rendered from the server then the client takes over to do the rest,
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
To non-developers page means the website that they are choosing to access and interact with. A non dev would consider different areas of the website separate pages- account history page, messages page, etc.

Before I started to define SPAs, I did not consider that a SPA would not requiring refreshing to reflect changes that I, as a user, had made on the page itself.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

Developers consider views to be what makes up the entire screen and commands a user's full attention.

In SPAs, the data itself is separated from the presenation of data by a model layer. The model later handles the data and the view layer reads from that model.

The "view" is content is determine by the model layer. When the content in the model layer changes, the "view-state" is programmed to reflect or not to refrlect that chagne.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
Web pages and app can be more fluid and responsive to the user.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
AngularJS
EmberJS
ReactJS
```
