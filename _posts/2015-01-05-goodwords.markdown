---
layout: post
title:  "GoodWords"
date: 2015-01-15 13:02:10
modified: 2015-01-15 13:02:10
description: "Online repository for professional written references."
imagefeature: letter.jpg
comments: false
share: true
---

<a href="http://goodwords.herokuapp.com"><img class="post-image" src="/images/GoodWords.png"/></a>

GoodWords is a place for professionals to collect & display professional written references from colleagues, clients, etc. Users can sign up to create a profile where their basic info & references will be shown. This profile is then publically accessible, so that colleagues can leave references, and recruiters/prospective employers can view it.

GoodWords is a single-page Angular application, using ngRoute. It is styled by Bootstrap, Font Awesome, and plain CSS. All page data is loaded by AJAX.

GoodWords's back end is inspired by Service-Oriented Architecture, which prescribes simplistic back end controllers, with services that do all the heavy lifting. All back end controllers return JSON data.

Front end techs used:
- Normalize.css
- Font Awesome
- Bootstrap
- HTML5/CSS3
- jQuery
- AngularJS
- ngRoute
- ngSanitize
- AJAX
- Parsley.js
- Flow.js
- Alertify.js

Back end techs used:
- Node.js/ExpressJS
- bcrypt-node
- PassportJS
- Q
- moment
- request
- CORS
- MongoDB/Mongoose