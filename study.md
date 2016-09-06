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
(NOTE: I primarily used wikipedia and the John Papa blog post, which I found
to be very helpful, for all answers. I also skimmed the following article for
a bit more context:
http://adamsilver.io/articles/the-disadvantages-of-single-page-applications/)
An SPA, or Single Page Application, is a fairly recent (and somewhat trendy)
way of designing web applications. It basically means that when a
user loads an SPA in their browser, all the funcitonality of the SPA is
immediately loaded from the server onto the client. So after this initial
page-load, all of the presentation--in other words, the user's experience of
interacting with multiple "pages"--is done on the client-side. Thus, the user
experiences different parts of the SPA via something that web developers call
"views" (but which appears to the user as different "pages" in the traditional
sense).
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
When non-developers say "page," they generally think of that page as existing as
its own branch on a tree, separate from any page that was clicked on previously,
or any page that can be navigated to subsequently. Likewise, most people think
of pages as easily navigable using the back and forward buttons on their browser.
SPAs can sometimes present a problem with this expectation, as pressing the "back" button
on the broswer can load the last page the user navigated to before opening the SPA,
rather than reverting one step in the user's previous screen state within the SPA.
(However, in my research I learned that this navigation issue can be solved.)
Before conducting my research, my understanding of the word "page" was somewhat
fuzzy, as I had experienced the previous usability issue with SPAs but not
fully understood why. This assignment really helped me to distinguish between
pages and views. (I generally like when our HW is about terminology, as I've
found it really helps with my overall understanding of web development.)
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
When developers say "view," they mean what the user would refer to as different
"pages" or "screens." However, in the context of an SPA, it is more accurate to
call these various parts of the SPA that the user interacts with "views," since
they are all part of the single page that loaded from the server to the client.
Having separate terminology for pages and views helps us make important
distinctions when we are discussing design for SPAs versus other types of websites.

The "view-state" simply refers to whatever view the browser is currently rendering
for the client. This could be any number of views that are available once the
initial HTML loads from the server. In this way, "page-navigation" and "state-
navigation" are analogous ways of thinking about navigating traditional websites
and SPAs, respectively.

Front-end routers help manage view-states because in an SPA, the routing is
handled by the client-side application using Javascript, as opposed to the server
(with a traditional multi-page website). As I previously mentioned, this means
that all possible views are already "pre-loaded" in the browser once the initial
load of an SPA occurs; the user is merely unaware that they are already loaded,
because an SPA provides the experience of loading the separate "pages" that most
end-users are accustomed to.


```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
The primary advantage of writing SPAs is that they allow a more "native-app"-like
experience to the user than traditional web apps. Another advantage is that SPAs
are good for very responsive sites. This is because the client doesn't have to
make an additional "round-trip" to re-render any part of the UI; all of the data
has already loaded, and the user just needs to navigate to different view-states
to experience different presentations of that data.
```

## List some technologies used to make SPAs

What are some of the tools used to create single page applications?

```md
Some of the tools used to create SPAs are:
1. Javascript frameworks like AngularJS, Ember.js, Meteor.js, ExtJS, and React.
2. Ajax (which , according to wikipedia, is the most prominent technology being
used to create SPAs)
3. JQuery is a popular library that is commonly used to normalize Ajax behavior
across different browsers
```
