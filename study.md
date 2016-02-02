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

## Define "single-page application" (SPA)

In your own words, define what a SPA is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
Single page application refers to web app or website that loads its content in a single page, like Twitter and GMail. Users are able to navigate the page on end and interact with the page as subsequent content is loaded dynamically.
https://www.quora.com/What-are-some-examples-of-single-page-applications
http://stackoverflow.com/questions/19501553/what-is-the-meaning-of-single-page-apps-in-context-with-round-trip-apps
https://developers.google.com/analytics/devguides/collection/analyticsjs/single-page-applications

```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
Users, like me, typically think of page as a webpage made of html, css and javascript and other frameworks, from which a bundle of them make up a website.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
Developers refers the rendered display of HTML fragments as view.

View-state is the default method that ASP.NET page framework uses to preserve page and control values between round trips  of the server and the client. In ASP.NET, submitting in a form on a page, the action is done within the page as opposed to from one page to another. Field values don’t disappear after submitting the form.
JS routers provides view state method that tracks user locations, loads resources without page reload, which is helpful when developing SPA’s.

https://msdn.microsoft.com/en-us/library/bb386448.aspx
https://www.youtube.com/watch?v=L3p6Uw6SSXs
http://appendto.com/2014/02/edisonjs-organized-routing-for-complex-single-page-applications/

```
