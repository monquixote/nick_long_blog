---
id: 15
title: 'Android Project - Train Game Design'
date: 2011-02-20T00:03:00+00:00
author: admin
layout: post
guid: http://www.nick-long.com/android-project-train-game-design/
permalink: /android-project-train-game-design/
blogger_blog:
  - monquixote.blogspot.com
blogger_author:
  - Monquixote
blogger_permalink:
  - /2011/02/android-project-train-game-design.html
categories:
  - Uncategorized
---
<div>
  <div>
    <img src="http://www.nick-long.com/wp-content/uploads/2011/02/229981914_dc05c5bc65.jpg" />
  </div></p> 
  
  <p>
    I've had a slight pause in my game project due to coming up against my first major design decision namely what is my game actually going to be about. 
  </p>
  
  <div>
    I've ruled out porting Brick of Destiny and on closer inspection I'm not convinced either of the ideas I mentioned in my initial post are going to work out.
  </div></p> 
  
  <div>
    I still stick by my initial assessment that there is absolutely no point in rewriting a classic unless I'm convinced I can do it better than Zynga, Glu or any of the hundreds of well funded casual game devs out there.
  </div></p> 
  
  <div>
    I've played and downloaded a lot of Android games and I've come to the conclusion that I don't really like tilt controls. or on screen joysticks for controlling action games which pretty much rules our classic shmups, platformers, or racing games. 
  </div>
  
  <div>
    I want something that's a natural fit for touch controls, but I still want something that has a proper game loop and gets the heart beating a bit faster.
  </div></p> 
  
  <div>
    <img src="http://www.nick-long.com/wp-content/uploads/2011/02/bGjb.jpg" />
  </div></p> 
  
  <div>
    There's an awful lot of games out there and it's easy to think that all the good games have been done. I've literally kept my self up at night trying to think of an original game idea. 
  </div>
  
  <div>
    I very nearly considered a remake of a PC game I was a huge fan of called <a href="http://en.wikipedia.org/wiki/Sheep_(video_game)">Sheep</a>, but a quick look at the Android market showed that several people have had the same idea. 
  </div></p> 
  
  <div>
    I had my eureka moment this morning. I've always loved the scene in Wallace & Gromit where Gromit has to lay the tracks out in front of the model train. I briefly thought about making a game where you have to lay tracks in front of a train but I realised this would be nothing more than a remake of <a href="http://en.wikipedia.org/wiki/Pipe_Mania">Pipe Mania</a> and there are dozens of those out there. I also briefly considered a remake of an old Amstrad game called <a href="http://www.youtube.com/watch?v=9A_n6l2csno">Locomotion</a> which is a similar concept with a sliding block puzzle twist.
  </div></p> 
  
  <div>
    My moment of revelation was thinking about the on rails sections of Mario games where you have to ride along on a moving platform hitting switches to change course and avoid obstacles. This reminded me of the mine cart mini game in the Indiana Jones arcade game (skip to 1:30). 
  </div></p> 
  
  <div>
  </div></p> 
  
  <div>
    I've had a bit of a rummage around on the Android store and I can't find any decent mine cart, or train based games. I also spent a bit of time searching for flash games (including a <a href="http://www.freetraingames.org/">site dedicated to train based flash games</a>!?!) and though there are a few games that have a train points mechanic they are usually focussed on managing a station rather than guiding a single train. 
  </div></p> 
  
  <div>
    So the concept I'm going for is keeping a train running on the tracks. 
  </div>
  
  <div>
    The screen will contain four parallel tracks the train can be switched from one track to the next by touching junctions on the track thus avoiding various obstacles. I'm a big fan of trying to keep something in a playable build at all times (especially due to my short attention span) so I'll probably knock something out as quickly as possible using horizontally blocks and lines and then add additional game play elements one by one getting rid of them if they don't work. Ideas so far are:
  </div></p> 
  
  <div>
    <ul>
      <li>
        A cutesy cartoon type look possibly with isometric pixel art (I might also try some fixed perspective 3D if I'm feeling brave) 
      </li>
      <li>
        Trains containing bad guys that you have to dispatch by forcing them to run into traps 
      </li>
      <li>
        Obstacles that can't be avoided but have to be fixed for the train to pass by using touch gestures.
      </li>
      <li>
        Depending on how I end up doing the graphics I may try my hand at a chip tune type sound track with some 8 bit synth action
      </li>
      <li>
        Rather than have instadeath and multiple lives I'm planning on having train passengers acting as lives who fall out when the train gets hit and can be picked up by driving past stations
      </li>
      <li>
        It would be really fun to be able to define rules for track layouts that provide a challenge, but are guaranteed completable so I could have the levels procedurally generated rather than defining them by hand
      </li>
      <li>
         The game should progressively speed up throughout the level possibly with some power ups which allow you to speed up or slow down the train. 
      </li>
    </ul>
  </div>
  
  <div>
    I'm glad I've finally got an idea I can start implementing. The next step is throwing some code together and seeing what works. 
  </div>
</div>