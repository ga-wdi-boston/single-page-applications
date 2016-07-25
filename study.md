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
SPA stands for single page applications that allows user to receive information without refreshing the page. It uses AJAX for the communication with the back end. AJAX returns data in JSON format. Then the app uses JSON data to update the page dynamically.

SPA makes only round trip to the srver to get initial HTML page.

Once that is done, the client takes over. The client decides what to do on the page if anything.

https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
https://johnpapa.net/pageinspa/
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
Web page is consisted of all the elements that are visible for the user when page loads. Buttons or menus aren't included because they change the visual representation of the page.

https://johnpapa.net/pageinspa/
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
"Views" are acutally HTML fragments. Since SPAs make only one round trip to the server, all "pages" that are seen after first page loads are actually "views" rather than pages that we get when we refresh our browser.

Routing is what actually make "views" or HTML fragments requested by the client.

https://johnpapa.net/pageinspa/
```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
Page doesn't need to reload, so the user have seamless experience because data was accessed and delivered using AJAX.

https://msdn.microsoft.com/en-us/magazine/dn463786.as
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
AJAX and jQuery for accessing the elements and retrieving the resource back to the user.

JSON is one of the format that is used when retreiving data from API using AJAX.

JavaScript frameworks like Angular.js, Ember.js etc.

https://en.wikipedia.org/wiki/Single-page_application
```
