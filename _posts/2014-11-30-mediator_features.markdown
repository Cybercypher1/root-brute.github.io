---
layout: post
title:  "Way to go"
date:   2014-07-02
categories: mediator feature
tags: featured
image: /assets/article_images/2014-11-30-mediator_features/night-track.JPG
---
Hi,

  This is a blog post I will mainting  as apart of my Google Summer of Code
  Project "Embed module API".
  I will start of by explainig what embed module is and why we need it and then
  briefly describe the progress I have made so far and what I am currently
  working on and I keep updating as the work progresses.

#Embed Module

  Embed module has its origin from the Entity Embed module which was also build
  as a part of GSoC Project in GSoC 2014. Entity Embed module allows Entity
  to be embeded. It has certain API level plugins that can be abstracted out
  to so that if the other modules also wants to use them .
  Abstarcting  out the plugins lets the the module that wants to use the get
  only the code the need otherwise earlier they would have to get the whole
  EntityEmbed module as a depenendecy and it only requires a part of it now.
  When the Project is complete it will provide a Embed Module Plugin which is not
  very functional by itself but it will provide a solid APIs to all other
  modules which aim to provide any kind of 'Embed' functionality


#Progress so far

  I started of working on Annotation Plugin. Well most the code for Annotation
  was already in there I had to add category to the annotation. Then the next
  step was working on Annotation Plugin  Manager.

  Then I was writing the test for Annotation Plugin and working.For which we created 
  three test plugins to test if the getDefintionsForCategory() works properly. The
  test had dependency on all of the build test modules as well as annoation plugin
  If the test were to be succesfull all the modules had to be correct. Mean while 
  while reviwing a Pull Request one of my mentors daveried who happens to be
  one of the core member media team. Raised a question 'Do we actually need the
  Category feild'. So the discussion has been going about it look. I am keenly following
  it and trying to find out what we can do about it now.

  So as of now I am working Abstract out Editor Button config entity from the
  Entity Embed module so that other modules can declare one easily. It involves
  going through the Entity Embeds code.


