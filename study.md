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
Single-Page Applications (SPAs) are web apps with a single web page that the server sends to the browser when the application starts. Single page apps are able redraw any part of the UI without requiring a server roundtrip to retrieve HTML, and it is this lack of server-based UI logic that distinguishes SPAs. Any changes that occur after this preliminary loading are the result of AJAX reacting to the client, and thus do not rely on a request for new HTML each time.

https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
https://johnpapa.net/pageinspa/

```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
They think that a "page" is the content that loads into the view of their web browser. I also thought that was the case.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md

Views are “other pages”, or the HTML fragments that make up what users commonly call screens or pages. In a SPA everything the users sees is a “view”. When a view occupies the entire screen we call that a page to reflect the fact that it visually commands the user’s full attention. Technically, it’s just a another view composed by the client.

The view-state seems to be a built-in structure for automatically storing values between multiple requests for the same page, which means that it represents a storage center for the data that results from users interacting with different "views".

The router’s job is to allow the user to go from View A to View B within the browser by clicking some menu item. In a SPA, it will allow a user to go to a specific place (view) in the app given a url (a term known as deep linking) without posting to the server. If the view has not been seen before, the application may make an HTTP request to retrieve the HTML template for the view. Then it will compose the view, fill in the template, and display the view in the appropriate location within the shell. If the view has already been viewed once, the browser may have cached it and the router will be smart enough not to make the request.

https://johnpapa.net/pageinspa/

```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
The immediate benefits of a single-page website is the content is presented in simple, easy and workable fashion for the user. Single page sites immerse the user in a simple linear experience, and navigation is much more straightforward. All of this means that performance is improved by limiting communication with the server.

https://www.uxpin.com/studio/blog/single-page-vs-multi-page-ui-design-pros-cons/
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
HTML, CSS, and JS are the fundamental tools used to craft SPAs, while AJAX is used to communicate with the server. Other frameworks such as Angular can also be used to simplify the creation process.

```
