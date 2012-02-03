--- 
layout: post
title: "HTML5 Has Failed Us"
published: true
categories: []

---

Unless you've been living under a rock, you've probably heard the fanfare about HTML5 and all it eye-catching splendor. What you don't know is that HTML5 completely dropped the ball on ensuring that the web will stay free and open.


##"Shut up, you stupid hippy"
That's the first thing I think whenever I hear someone preach about the "free and open Internet." Such rants are heard too often from neckbeards who incessantly rally against sites like Facebook or Twitter (probably because no one wants to friend them).

<img src="http://i1.kym-cdn.com/entries/icons/original/000/003/445/untitled.jpeg" />

I am not one of those people. Instead, my story starts when I was selecting blogging engines. This blog is implemented in Jekyll but it was almost a Tumblr blog. My greatest regret with rolling my own site is I miss out on the wonderful community that comes with a site like Tumblr. No comments, no one to repost my blog posts on their own pages. This is the price I pay to keep my data open.

##One little icon that will kill the web

<img src="http://4.bp.blogspot.com/-HzztD74ib-w/TrQ0957-IdI/AAAAAAAAAvk/d00Uk1SLd5M/s320/retweet-icon.jpg" />

That little sharing icon has become the very future of the World Wide Web. Sharing has become the *primary* way to consume content on the Internet. Knowledge no longer propagates through hyperlinks; it comes by way of Tumblr reblogs, Twitter retweets, and Pinterest repins. Re, re, re.

The truth is that HTML does not support any way to share content in this manner. True, images can be remotely referenced by way of hot linking. But what about snippets of text (such as a Tumblr post you want to reblog)? How about a Github commit/issue you want to display inline?

There simply is not way to tell a browser or -- more importantly-- a web crawler, that the thing you are seeing here is really just a "view" of some resource somewhere else.

To anyone who have programmed in Rails or iOS, the concept of separating a view and the underlying model is part of your toolkit. This is sadly impossible with even the latest HTML spec.

##I like freedom. I like convenience better.
I'm turning the tables on Ben Franklin this time. We've demanded social Web standards for over half a decade. What did we get? An incomprehensible alphabet soup like RDF, OWL and SPARQL.

The HTML standards committee missed the boat on provided an easy and standardized way to relate the shareable snippets that our modern Web is composed of. Instead of being encoded in Hypertext, the underlying relational graph of the web is contained within the databases of private Internet giants.

I'm not going to stop using the Web because of this. Life is far too short to be an ideologue. But I can't help but lament what could have been.