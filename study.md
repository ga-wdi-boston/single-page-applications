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
An SPA is an app that only requests and loads a single HTML page when the user first opens the page. Instead of needing to refresh the page every time an event occurs, the single page dynamically updates its appearance and functionality as the user interacts with it. An SPA makes interface/content changes as a well as data requests from servers in real time.

I mostly used the MSDN link and the Single Page Myth link from above in order to answer this question.
```

## Define "page" as used by non-developers

What do users mean when they say "page"? What did you mean before your started
your search to define SPAs?

```md
I imagine most people think of a "page" as something static--- something that loads that they can scroll through and look at before they interact with it. Although most younger people nowadays are pretty internet/computer savvy, I imagine that some people think that once something changes on the page that it counts as a new page. I was lucky enough growing up to be familiar with technology, so when web pages started becoming more interactive, I think I was able to mostly infer when something was still the same page or whether it was refreshing. Before I was a developer, I didn't necessarily know that it was *specifically* about the server rendered HTML that is first sent to the page before the client-side operates on it at all.

I used my personal experience and the "Single Page Myth" site for this answer.
```

## Define "view" and "view-state" within the context of SPAs

What do developers mean when they say "view"? Since view can have many meanings,
what do developers mean when they say "view-state"? How do front-end "routers"
help manage view-state?

```md
I'm still a bit unclear on the exact details. From what I gather, view-state has to do with managing multiple states/versions of a single web page. This is necessary because every time the page is requested from the server it returns a brand new copy, wiping any information or controls that were on the page before it refreshes. View-state is a state management feature in the ASP.NET page framework used to "preserve page and control values between round trips to the Web server".

I used the page "ASP.NET View State Overview" for this answer.
https://msdn.microsoft.com/en-us/library/bb386448.aspx


```

## Define the advantages of an SPA over a traditional application

What are the advantages of a single page application over a traditional appliction?

```md
There are many advantages. For one, it's very good for responsive websites. Since you don't need to make a brand new html request to the server any time you want to change something, things are much snappier. Also, any time something new/complex needs to be rendered, it is done on the client side, which lowers the burdern on your servers and eliminates most latency (reduces resources needed). A good example that someone mentioned on Stackoverflow illustrates the concept pretty well I think. They said "want an extreme example? Try making a calculator in a non-SPA website". I can imagine that initiating a calculation in the client, sending the data to a server, having that server unpack the data, do the calculation server-side, and then send the result back, would make for a pretty crappy/laggy calculator experience. Whereas with an SPA you could load in some sort of calculator scripts and do calculations in the browser, etc..

I mostly parsed through opinions on stackoverflow for this answer.
```

## List some technologies used to make SPA's

What are some of the tools used to create single page applications?

```md
It looks like the answer to this depends on the complexity of your site, but many of the answers are things I've seen/heard of before. It seems like most tools are some iteration of something called an MV Framework.
Here's a list I compiled from a bunch of responses I found from developers online:

   - http://backbonejs.org/
   - http://angularjs.org/
   - http://emberjs.com/
   - http://www.meteor.com/main
   - https://facebook.github.io/react/
   - http://spinejs.com/
   - http://sammyjs.org/
   - http://knockoutjs.com/
   - http://batmanjs.org/
   - http://canjs.us/

Backbone, Angular, and Ember are all things I've heard about frequently from developers, including the consultants at GA. I'm assuming we eventually learn one or all of those three at some point in this course.

I searched google for "best tools for making single page apps" and "best tools for MV frameworks" and these are the links I saw most often^^
```
