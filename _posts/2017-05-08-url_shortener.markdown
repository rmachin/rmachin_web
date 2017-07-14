---
layout: post
title:  "Url Shortener with Heroku"
date:   2017-05-05 13:08:10 -0500
img: img/portfolio/url_shortener.png
modalID: modalUrlShortener
category: Web Development
---

The URL Shortener is a web application build with ruby that takes long URLs and squeezes them into fewer characters to make a link that is easier to share, tweet, or email to friends.


As a user YOU CAN pass a url as a parameter in a form and receive a shortened url as a random string.


After the user submit the URL the link is send to a method named create in the controller, the controller call a method in the Model to generate a short URL using a loop and a combination of numbers and characters. Next, the short code is send back to the controller, save in the database, and the page name show is render with the short url. For more information visit the project in github.


# Users can create these short links through the web interface [here.](https://pure-river-29837.herokuapp.com/)



#### Technologies Used:

##### * Ruby version 2.4.1

##### * Rails version 5.1.1

##### * Html5, CSS3 and JS.


# [Open GitHub Project](https://github.com/rmachin/Url-Shortener-Heroku)
