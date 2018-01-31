---
id: 21
title: 'Android Project - Game Engines'
date: 2011-02-10T22:27:00+00:00
author: admin
layout: post
guid: http://www.nick-long.com/android-project-game-engines/
permalink: /android-project-game-engines/
blogger_blog:
  - monquixote.blogspot.com
blogger_author:
  - Monquixote
blogger_permalink:
  - /2011/02/android-project-game-engines.html
categories:
  - Uncategorized
---
<div>
  <div>
    <a href="http://www.google.co.uk/imgres?imgurl=http://www.nick-long.com/wp-content/uploads/2011/02/TRC3649.jpg&#038;imgrefurl=http://autotenz.com/audi-with-more-powerful-engines/&#038;usg=__GOkXFePAi-myo-cpeNrhGFsNQUE=&#038;h=333&#038;w=500&#038;sz=65&#038;hl=en&#038;start=13&#038;zoom=1&#038;tbnid=8EtXIfbpwsuSSM:&#038;tbnh=87&#038;tbnw=130&#038;ei=plhUTePVA5CyhAfJmcHvCA&#038;prev=/images%3Fq%3Dv8%2Bengine%26start%3D9%26um%3D1%26hl%3Den%26safe%3Doff%26biw%3D385%26bih%3D402%26addh%3D36%26output%3Dimages_json%26tbs%3Disch:1&#038;um=1&#038;itbs=1"></a>
  </div>
  
  <div>
    <img src="http://www.nick-long.com/wp-content/uploads/2011/02/TRC3649.jpg" />
  </div></p> 
  
  <p>
    In the comments to <a href="http://nicklong.posterous.com/planning-an-android-game-project">my previous post</a> iPhone developer <a href="http://www.easyeartraining.com/Apps/">extraordinaire</a> Chris suggested using a third party physics engine for my game. I don't know why I hadn't thought of this in the first place. For web development I wouldn't dream of starting a project without using a framework. After all the longer you spend writing loads of boilerplate code the less time you have to spend on the good stuff.
  </p>
  
  <div>
    <div>
      Chris suggested using the <a href="http://www.box2d.org/">Box2D library</a> which looks very good. As Android is a Java platform a Java library would be ideal and luckily some helpful chaps have ported the library and called it <a href="http://www.jbox2d.org/">JBox2D</a>. There are some very nice looking demos on the website and a helpful <a href="http://www.anddev.org/how-to_2d_physics_with_box2d-t5099.html">tutorial </a>about getting it up and running on Android. I was slightly concerted when playing with the applets that there were a few freezes and stutters (My laptop is only a year old) and a quick search on the internets revealed that most  people were having problems with the Java garbage collector causing problems. 
    </div>
    
    <div>
      Luckily all is not lost. Android is not a Java only environment thanks to something called the NDK (Which as far as I can gather is just Android's version of <a href="http://en.wikipedia.org/wiki/Java_Native_Interface">JNI</a>) which allows you do drop meaty chunks of speedy C++ into your Java stew. This requires you to do a bit of work to wrap any C++ classes you want to use with a bit of Java.
    </div>
    
    <div>
      <img title="AndEngine Logo" src="http://www.nick-long.com/wp-content/uploads/2011/02/logo.png" alt="AndEngine Logo" />
    </div></p> 
    
    <div>
      Luckily a bit more Googling revealed the <a href="http://www.andengine.org/">AndEngine</a> and <a href="http://code.google.com/p/libgdx/">libgdx</a> a pair of free Android game frameworks. Both use OpenGL for graphics and rather conveniently integrate the Box2D library saving me the job of getting my hands dirty with NDK. Opinion seems to be that libgdx is faster and better documented while AndEngine is higher level and easier to get to grips with. I quite like the fact that libgdx offers the ability to compile into JOGL for desktop apps rather than having to continually build apks and test on the emulator. 
    </div></p>
  </div></p> 
  
  <div>
    I'm still undecided between the number puzzle and the jumping frog game but either way I'm going to give a framework a go and see what it offers. 
  </div>
</div>