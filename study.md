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
SPA is a single page application that is a strategy in which a web app or website has a more fluid and responsive UI, similar to a desktop app, where the page does not constantly refresh each time an event occurs. With a SPA, all of the code is generated in a single page load. The server and the client work independently and the client is in charge of firing off events as the user makes them on the page.

I used the following required readings:
https://johnpapa.net/pageinspa/
https://en.wikipedia.org/wiki/Single-page_application

```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
For a non-developer, a page would be defined as the current screen the user is on or would like to navigate to on a website. (i.e. "Go to the view my cart page to see everything I want to purchase.")
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
A common misconception with SPAs is that they are a single page, however SPAs can support many other pages. These 'other pages' are called views. Additionally everything a user sees is considered a view. When a view takes up the entire screen that is considered a page since it grabbing the user's full attention.

View state is the client-side mechanism for managing the stored data between roundtrips to the server. The router helps get the user from view A to view B via menu items in the browser. If the view is not stored in memory or ever been seen before the app will make a request to retrieve the resources for that view.
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
SPAs allow for a more fluid and responsive UI experience since it doesn't always need to refresh the page when events occur. Another advantage is the architecture of the app. Since the client and server work independently, this allows for more flexibility in terms of building out different layers of the app. In an ideal situation, you can edit the HTML without touching the code that implements the logic.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
Angular, Ember and React
```
