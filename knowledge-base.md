---
layout: default
title: Knowledge Base
---


# Knowledge Base

Nowadays it's very easy to learn anything online. You just have to google the topic you want and there you go. You have access to thousands of resources. For example there are great courses on [codecademy](https://www.codecademy.com/) or similar websites. Use those resources, they are awesome!

There are two pages which you will visit a lot (and you probably know them very well already):

 - [w3schools](https://www.w3schools.com/)
 - [MDN web docs](https://developer.mozilla.org/en-US/)

The relevant parts of these websites will be included at the end of every subsections.


In this page we try to collect some resources which are not the ones mentioned above and can help you to get into various topics. These can be tutorials, youtube chanels or any other websites.


## The Basics of HTML & CSS

First of all, you have to learn the fundamentals of HTML & CSS. The most important thing to understand is how you can create complex layouts. You have to have a good understanding of the basics, otherwise you will waste a lot of time when you debug some CSS magic...
To learn this, check out the following blog posts:

 - [The Basics of HTML and CSS - Part I.](http://blog.edmdesigner.com/the-basics-of-html-and-css-part-one/)
 - [The Basics of HTML and CSS - Part II.](http://blog.edmdesigner.com/the-basics-of-html-and-css-part-two/)

By finishing this part, you should be able to answer at least the following questions:

 - How can you put divs next to each other? (Think about two different solutions.)
 - How can you create a 3 row layout, where there are 3 columns in the middle row?
 - What is a clear class?
 - How can you create a top menubar which will hover in from the top when you scroll down?

Other links:

 - [MDN - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
 - [MDN - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
 - [w3schools - HTML](https://www.w3schools.com/html/default.asp)
 - [w3schools - CSS](https://www.w3schools.com/css/default.asp)


## JS Basics

The first and most important thing to learn when you learn a programming language is the basic concepts. It's especially true when it comes to javascript. There are many developers who are confused about some of the basic concepts in the language. If you learn the basic principles, you will be much better js coder than those who know many frameworks but use javascript as it was a different language.

In this part let's focus on ES5, so you will gain a solid knowledge before you investigate the great (and not so great) things in ES6.

I started a [blog about JS](http://www.jsmage.com/) a few years ago. Unfortunately I stopped publishing posts on it, but I think these articles will be very useful for you:

 - [Variables and types](http://www.jsmage.com/2013/08/the-very-basics-variables-types-and.html)
 - [Objects](http://www.jsmage.com/2013/08/the-very-basics-objects-in-javascript.html)
 - [Arrays](http://www.jsmage.com/2013/08/the-very-basics-arrays-in-javascript.html)
 - [Functions](http://www.jsmage.com/2013/08/the-very-basics-functions-in-javascript.html)
 - [Function Scoping](http://www.jsmage.com/2013/09/the-very-basics-common-mistake-around.html)
 - [Function Combination](http://www.jsmage.com/2013/08/function-composition.html)
 - [The Module Pattern](http://www.jsmage.com/2014/01/the-module-pattern-in-javascript.html)

By finishing this part, you should be able to answer the following questions:

 - What types are there in Javascript?
 - How can you determine the dynamic type of a variable?
 - What is variable and function hoisting?
 - What is a closure?
 - What is a factory method?

Other links:

 - [MDN - JS](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
 - [w3schools - JS](https://www.w3schools.com/js/default.asp)

## Javascript & the DOM - the Basics

If you know learn how the following functions work, then you will gain a good understanding of the basics of the DOM:

 - createElement [MDN](https://developer.mozilla.org/en-US/docs/Web/API/Document/createElement) [w3schools](https://www.w3schools.com/jsref/met_document_createelement.asp)
 - createTextNode [MDN](https://developer.mozilla.org/en-US/docs/Web/API/Document/createTextNode) [w3schools](https://www.w3schools.com/jsref/met_document_createtextnode.asp)
 - appendChild [MDN](https://developer.mozilla.org/en-US/docs/Web/API/Node/appendChild) [w3schools](https://www.w3schools.com/Jsref/met_node_appendchild.asp)
 - addEventListener [MDN](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener) [w3schools](https://www.w3schools.com/js/js_htmldom_eventlistener.asp)

When people apply to us for a job, I usually ask them to create a ToDo List app in vanilla.js in ES5. It shows how well they understand the basics of Javascript. I suggest you to do the same. The HTML you start with has to be the following:

```html
<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>
<script>
//Write your todo list here, don't touch the markup!
</script>
</body>
</html>
```

The only rule is that you must not touch the markup! By using the four functions mentioned earlier you have to be able to solve this task. It has to work on IE8 as well, so you must use ES5. (To be honest it's not because of IE8... I usually ask people to use ES5, because then I can see if they know what function scoping and closures are. (var vs. let)) 


## Prototypes, Inheritance and the Misterious 'this' Keyword

There are NO classes in Javascript. One of the biggest common mistakes is that coders coming from other languages try to use JS as a classical object oriented language. This is a prototype based object oriented language, not a classical one.

Actually I came to the conclusion that you don't even need to use the *this* and the *new* keyword in Javascript. It's a decision that I don't use some of the features in this language, BUT you need to know the fundamentals! If you know them you can decide wether you use something or not. If you understand the following figure, then you probably understand prototypes in Javascript.

![Prototypes in Javascript](./assets/prototypes-in-javascript.png)

I think this is the best figure about JS prototypes ever. If you are not familiar with prototypes please read [their article](http://mollypages.org/tutorials/js.mp) which highlights the most important parts. You can also read about [the prototype chain](http://mollypages.org/tutorials/jsscope.mp) and the misterious [this](http://mollypages.org/tutorials/jsthis.mp) pointer. (They compare it with Java's this in the article. - I think it's extremely useful.) 


After you are familiar with the *this* keyword, you definitely should play around with the following functions:

 - [apply](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/apply)
 - [call](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/call)
 - [bind](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/bind)

You can modify *this* with these functions. They will refer to another object!


## Git

Git is a widely used versioning system. I wrote a blogpost about a branching model previously that contains lots of useful links to learning resources.

 - [Git Branching Workflows in SaaS Development and the Reivew ASAP Policy](http://blog.edmdesigner.com/git-branching-workflows-in-saas-development-and-the-review-asap-policy/)

If you follow the links in the article, you will be able to learn a lot about Git. After doing it, you should know:

 - the basic git commands: pull, commit, push, checkout, branch, etc...
 - the basic branching models / workflows


## Linux

If you don't want to suffer as a developer, you definitely should use Linux. One of the biggest reasons is that it has a great package manager and a good default terminal, so you can easily run scrips which will help your day-to-day life. It is not very easy to find a good linux tutorial, but this seems to be okay: [http://ryanstutorials.net/linuxtutorial/](http://ryanstutorials.net/linuxtutorial/)

Our DevOps supermage told me that I have to include this [book](http://linuxcommand.org/tlcl.php). It contains the important basics.

Although you don't have to be a linux superstar, it can save you a lot of time. Go for it!


## Node.js

If you use node.js you can use javascript on the server side. It's great, because you can use the very same language that you use on the frontend which also means that you can use some of your code on the frontend and on the backend as well. 

The ultimate source for learning node is [nodeschool.io](https://nodeschool.io/). Besides node, there are other tutorials to explore.

The probably most importand web application framework for node.js is [expressjs](https://expressjs.com/). You can write APIs and also whole websites.

When you write a webserver in node, you usually use [MongoDB](https://www.mongodb.com/) as your database. [Mongoosejs](http://mongoosejs.com/) is an [ODM](https://en.wikipedia.org/wiki/Object-relational_mapping) for MongoDB on Node.


By finishing this part, you should be able to create a simple website with Mongoose and ExpressJS. After you created your website, you should check out what a [REST REST](http://www.restapitutorial.com/) is.

If you want to create RESTful APIs, you definitely should check out [superserverjs](https://github.com/EDMdesigner/superserverjs).


## Templating Languages & Blogs

Using templating languages is a great way to inject dynamic data to your HTML templates. You can do it on the server side and on the client side as well. If you have ckecked out some Node.js + express.js tutorials, you are probably familiar with some of the following templating languages:

 - [EJS](http://www.embeddedjs.com/)
 - [Handlebars](http://handlebarsjs.com/)
 - [Liquid](https://shopify.github.io/liquid/)

If you are not familiar with Node.js and Express.js, you can still benefit from the use of templating languages. Many blog engines and static site generators use them.

For example the liquid templating language is used by [Jekyll](https://jekyllrb.com/), which is a blog aware static site generator. The coolest thing in it is that you can host your jekyll base website for free on [Github pages](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/).

Handlebars is the default templating language of the new, hip, Node.js base blog engine: [Ghost](https://ghost.org/).

We use both jekyll and Ghost, and we use EJS with Express.js & Node.js. We also use it in our build processes. (For example we need to use different resources [eg. css files] in our development, staging and production environments.)


## HTML5 & CSS3

If you are already familiar with the basics, you should check out a [tutorial](http://www.hongkiat.com/blog/building-html5-css-webpages/) which focuses on the modern but stable things.


## Tooling & Task Automation

 - grunt, gulp, etc

 - [HTML Email Development Tools](http://blog.edmdesigner.com/tag/html-email-development-tools/)



## HTML Frameworks & CSS Precompilers

The second step is to get familiar with a framework. The most famous one - which you probably know - is Bootstrap (LINK) by Twitter. You can use it together with Font Awesome (LINK) to create decent UIs. It's best if you want to create admin UIs. For product end-user facing interfaces, you will need to use pure CSS knowledge.

 - TODO: find a good tutorial - eg. build an administrative ui...

	- Sass, Less


## Knockout.js

## Unit Testing

## Email HTML

If you are interested in how email HTML differs from traditional web-based HTML, check out our [Modern Email HTML Tutorial](http://blog.edmdesigner.com/tag/modern-html-email-tutorial/).

## Other Javascript

	- JSON

	
	funfunfunctions
	https://www.youtube.com/channel/UCO1cgjhGzsSYb1rsB4bFe4Q

	Douglas Crockford
	https://www.youtube.com/results?search_query=douglas+crockford


## Hosting

	- apache, nginx
	- forever
	- AWS
	- DNS, Nameservers
	- docker

## Continuous Integration

	- Basic concepts
		- TODO links
