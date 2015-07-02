---
layout: post
title:  "Way to go"
date:   2014-07-02
categories: mediator feature
tags: featured
image: /assets/article_images/2014-11-30-mediator_features/night-track.JPG
---
Hi,

  This is a blog post I will mainting  as apart of my GSoC Project "Embed module API".
  I will start of by explainig what embed module is and why we need it and then
  briefly describe the progress I have made so far and what I am currently
  working on and I keep updating as the work progresses.

#Embed Module

  Embed module has its origin from the Entity Embed module which was also build
  as a part of GSoC Project in GSoC 2014. Entity Embed module allows Entity
  to be embeded.It has certain API level plugins that can be abstracted out
  to so that if the other modules wants to use them.
  Abstarcting  out the plugins lets the the module that wants to use the get
  only the code the need otherwise earlier they would have to get the whole
  EntityEmbed module as a depenendecy and it only requires a part of it.When the
  Project is complete it will provide a Embed Module Plugin which is not
  very functional by itself but it will provide a solid APIs to all other
  modules which aim to provide any kind of 'Embed' functionality


#Progress so far

  I started of working on Annotation Plugin. Well most the code for Annotation
  was already in there i had to add category to the annotation.



  Then the next step was working on Annotation Plugin  Manager.


  Then I was writing the test for Annotation Plugin and working. while reviwing
  the a Pull Request one of my mentors daveried who has started the drupal8 
  media intiative along with few members. Raised a question to




#Links
This is an [example link](http://example.com/ "With a Title").

