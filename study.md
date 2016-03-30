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
SPA stands for Single Page Application, which is a web app that only consists
of one HTML page. SPAs are built using HTML, CSS, JavaScript, JSON, and AJAX
allowing the single page to dynamically interact with the user without needing
to re-render the entire page. Page refreshes are very noticeable, thus
repeatedly refreshing the entire page would be very annoying for the user. SPAs
solve this issue by only re-rendering the relevant area.  The "single page"
part of SPA does not necessarily mean that a SPA only does one thing, it just
means that the server rendered an HTML page once when the app initialized, and
the rest of the work is done on the client-side.  User interaction does not
involve the server, everything is done by the client instead.

Sources: https://msdn.microsoft.com/en-us/magazine/dn463786.aspx
http://www.johnpapa.net/pageinspa/
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
When refering to a "page," non-developers are likely to think of a single
section or part of a a webpage (ex. the "about me" in a blog is a page, and
the "archives" would be another page). A website would encompass multiple
pages.  Before I started my search to define SPAs, I used page and website
interchangeably.

Sources: http://www.johnpapa.net/pageinspa/
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
Views are the "pages" that non-developers typically think of, the content that
is not part of the initial HTML render. They are fragments of HTML that add
different set of functionality. By "view-state," developers mean the data
that is kept during a user's session, so that information will not be lost
between communication with the server or client. Web apps are stateless by
default, so maintaining view-state has become an important part of development.
Front-end "routers" manage view states by tracking user state and loading
resources as needed with changing the url or refreshing.

Sources:  http://www.johnpapa.net/pageinspa/
https://msdn.microsoft.com/en-us/library/ms178198(v=vs.85).aspx
http://appendto.com/2014/02/edisonjs-organized-routing-for-complex-single-page-applications/
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
