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
It is a website that always keep you on the same page. On most websites, when you click a link,
it reloads to a new page. In a single page application, clicking a link keeps you on the same page,
but replaces part of it with new content. It makes for a more fluid experience for users.

This quote helped: "The “page” in SPA is the single web page that the server sends to the browser when the application starts. It’s the server rendered HTML that gets everything started. No more, no less. After that initial page load, all of the presentation logic is on the client."
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
Users usually mean the link that they are currently on and the entire content that is displayed.
My understanding was essentially the same before the readings.
This quote helped: "The “page” in SPA is the single web page that the server sends to the browser when the application starts. It’s the server rendered HTML that gets everything started. No more, no less. After that initial page load, all of the presentation logic is on the client."
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
I am using language from the reading because I think it as simple as I can break it down and understand it.
Everything the user sees is a "view".
Views are HTML fragments that make up what the users commonly call screens or pages.
The view-state is what the user is currently seeing on their screen.
The router’s job is to allow the user to go from View A to View B within the browser by clicking some menu item.
The user goes to a specific part of the view. 
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
Single page applications can improve loading time, using AJAX and are generally easier to navigate.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
The MEAN framework stack is something I cam across frequently in my own research. I have heard of
some of these frameworks before, but don't know much about them.
Websockets are frequently used as well as browser plug-ins.
```
