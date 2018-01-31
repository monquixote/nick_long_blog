---
id: 18
title: 'Android Project - LibGDX'
date: 2011-02-15T23:55:00+00:00
author: admin
layout: post
guid: http://www.nick-long.com/android-project-libgdx/
permalink: /android-project-libgdx/
blogger_blog:
  - monquixote.blogspot.com
blogger_author:
  - Monquixote
blogger_permalink:
  - /2011/02/android-project-libgdx.html
categories:
  - Uncategorized
---
<div>
  <img src="http://apistudios.com/hosted/marzec/badlogic/wordpress/wp-content/uploads/2010/06/logo-full.png" /></p> 
  
  <div>
    After a bit of research on Android frameworks I've decided to go with LibGDX. It looks like an excellent framework and has the advantage that Android is just one back end to the framework. It can also build for JOGL to produce a desktop app. As well as the obvious advantage of having two platforms for the price of one it also means you can play with the desktop version while you are tweaking gameplay without having to continually go through the rigmarole of building for the emulator. 
  </div>
  
  <div>
    LibGDX is an OpenGL library and unlike some of the more beginner focussed libraries it doesn't sugar coat anything, it expects you to deal with it's eccentricities.
  </div></p> 
  
  <div>
    I noticed that many of the other Android libraries seem to be using the libraries from LibGDX so I thought I might as well go straight to the source. 
  </div></p> 
  
  <div>
    For those who are not au fait with such things OpenGL is a library that provides a standard way to talk to graphics accelerators. Before it existed people writing PC games had to write their own drivers for every single graphics card they wanted to support. OpenGL compliant hardware supports a standard set of features if you write code using an OpenGL library it will work any compliant hardware. 
  </div>
  
  <div>
    You might wonder why graphics hardware is important if you have a device with a speedy processor. CPUs are what's called a Turing machine which means they can do pretty much anything you can dream of while graphics accelerators can only perform a very limited set of instructions tuned for moving shapes around, but because they are so specialised and perform actions in parallel they can increase graphics performance, by a factor of tens or hundreds.  
  </div></p> 
  
  <div>
    Previous Java games I have written have used the Java2D library which allows you to draw graphical primitives on a canvas without graphics acceleration and while this might be fine for a simple game running on a desktop PC if I have any aspiration for writing more advanced game on heavily resource constrained devices I'm going to need to learn how to use hardware accelerated graphics (That said I developed my desktop game on an 800MHz PIII and will be developing my mobile game on a 1GHz Galaxy S)
  </div></p> 
  
  <div>
    I'm definitely going to use the Box2D library in the future, but I think in order to get on with writing a game without having to spend to much time learning stuff I'll make OpenGL the new thing for my first project and introduce Box2D on the follow up. 
  </div></p> 
  
  <div>
    I've been toying with the idea of updating <a href="http://nick-long.com/brickofdestiny.php">Brick of Destiny</a> to use OpenGL, but having reviewed the source I used the collision detection from Java2D quite extensively and the game also has a fixed frame rate which would mean tinkering with the rendering and simulation quite a bit so much so that it wouldn't speed things up that much. Last but not least I made a few school boy errors in the code as a gaming noob and so I would either have to waste time fixing them, be forever annoyed by bad decisions.
  </div></p> 
  
  <div>
    Next time hopefully I'll write up some concrete game design for my project. 
  </div>
</div>