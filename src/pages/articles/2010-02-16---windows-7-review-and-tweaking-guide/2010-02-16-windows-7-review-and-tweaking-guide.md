---
id: 37
title: Windows 7 Review and Tweaking Guide
date: 2010-02-16T02:03:00+00:00
author: admin
layout: post
guid: http://www.nick-long.com/windows-7-review-and-tweaking-guide/
permalink: /windows-7-review-and-tweaking-guide/
blogger_blog:
  - monquixote.blogspot.com
blogger_author:
  - Monquixote
blogger_permalink:
  - /2010/02/windows-7-review-and-tweaking-guide.html
categories:
  - geeky
  - windows 7
---
This is the third and final part in my blog series on my experiences of moving to Windows 7 from my previous set up of XP and Ubuntu Linux.

In my old set up I used my Ubuntu as my everyday machine and kept XP around to use when inconsiderate manufacturers don't provide drivers for Linux (I'm looking at you HTC and Tom Tom) when both of my machines died in quick succession I bought my laptop with an expectation that I would probably dual boot Win 7 and Linux, and once again avoid Windows except when necessary.

Once I saw the very positive reviews of Win7 I thought it would be an interesting experiment to see if an Ubuntu devote such as my self could use Win7 without being driven insane. In my previous post I explained some of the long list of tweaks I have to apply to XP to make it usable so I'll be covering some of those issues here along with a few other things that came up along the way.

I guess I should start with the headline news that after a month I'm still using Win 7 and I have to hand it to Microsoft it's pretty good. That's not to say it's all been sunshine and roses. I'll try and use the same headings as my XP article but first the setup process:

## Set Up & Crapware

I've always believed that at least 25% of the reason people love Macs and tolerate PCs is the dreadful state that Windows machines are in when they get to a punter. PC manufacturers make on average an extra £50 on every PC they sell due to shipping a machine full of hard to remove trials, toolbars and useless expensive services. On my PC I had: An app launcher, a game download service, online storage, a dell support program, a music download service, MS works and the expected overpriced antivirus. Unsurprisingly crapware vendors don't like to make their applications easy to remove and the standard Add Remove Programmes dialogue isn't really up to it. I quickly found a couple of tools which made life a lot easier. [Revo Uninstaller Pro](http://www.revouninstaller.com/ "Revo Uninstaller Pro") is a superb tool which makes removing unwanted crap a breeze and also cleans up any leftover files and registry entries as well as featuring a number of other useful tools beyond the scope of this article. For this less technically inclined [PC Decrapifier](http://www.pcdecrapifier.com/ "PC Decrapifier") is a simple one click solution that finds crapware and removes it.

Set up was in all other respects a breeze. There are any number of nice little touches down to the comprehensive selection of well thought out system sounds and wallpapers which can be selected using a simple personalisation menu.

## Browser

I'm going to have to start with a bad one I'm afraid; Internet Explorer is still a joke. Microsoft are going to have to find some way to keep all those crappy IE 6 apps while embracing open standards or Firefox and Chrome are going to eat them for breakfast. I lasted about 10 minutes with IE 8 before downloading Firefox, but to be fair I would probably do the same on a Mac as I'm no fan of Safari.

## Media Playback

I use Spotify for my music needs so I can't really comment on Windows Media Player or Media Center for managing your media library, but as a minimalist media player it's very usable and has a very much improved set of codecs compared to XP. In fact I didn't really feel the need to download any other media player software for a month and then only because I needed to work on AMR format audio which is fairly obscure.

Under this heading I will also mention that the photo viewer application is also really rather good even when viewing photos on a remote server.

## Taskbar

This is one of the obvious big changes from XP/Vista. The taskbar is a huge improvement. Quicklaunch and the main application area are merged and applications with multiple windows are neatly handled with Aero Peak which shows a thumbnail of all that apps open windows when you hover over the icon. The system tray also looks a lot cleaner and has a really nice interface for hiding icons or restricting popups. Hopefully the days of the irritating popup frenzy system tray are over. 

Overall I still think the OSX doc is tidier but I didn't really feel any urge to install Rocket Dock

## The Start Menu



The start menu is also a big improvement over XP (Though perhaps not Vista). The main plus is that its fully searchable so when you hit the Windows key you simply start typing the name of the app and it instantly takes a guess at the app or folder you are after as you type. It doesn't offer all the functionality of a dedicated tool such as Launchy, but again it's good enough that I don't feel I need anything else.





## File Management

Explorer has a few nice tweaks like breadcrumbs and better support for zip files. 

A couple of gripes would be that Explorer lacks tabs and support for ISO disk images is very limited.



## Window and Desktop Management

Ok here is my first serious beef. No virtual desktops. I my opinion this is totally unacceptable. Even XP had a powertoy which gave you 4 desktops. It also makes very little sense because I have been very impressed with Win 7s ability to handle multiple screens and surely it can't be a big jump from one to the other. The only reason I can think of is that the feature was vetoed by the Office team as Office 2007 works both appallingly and inconsistently with virtual desktops. 

The worst thing was I couldn't find a tool which worked well with the Win7 toolbar. This was the first issue that nearly caused me to reach for the Ubuntu disc but luckily someone pointed me in the direction of the new beta version of [Virtuawin](http://virtuawin.sourceforge.net/ "Virtuawin") which works seamlessly. It's still a big black mark though.

In general window management is very good. The new Aero Snap features which let you maximise and split screen windows with a gesture are excellent and I find myself trying to use them on other operating systems. The window switcher is also improved with life snapshots and an optional groovy 3D window fly though feature.

## Software Updating 

As I mentioned in my XP article the ability to seamlessly update all of the software on my machine with one simple automatic interface is something that is only available in Ubuntu. the same is true of the Ubuntu software store which provides a great source of trustworthy free software.

Windows updates seem less obtrusive but no great improvement from XP.

## Security

My biggest tip to anyone using Windows is DON'T PAY FOR VIRUS PROTECTION!!!!

Microsoft have a free antivirus product called [Security Essentials](http://www.microsoft.com/Security_Essentials/ "Security Essentials") which integrates seamlessly and outperforms all of the commercial applications. It's a terrible shame that people are being screwed by charlatans like Symantec when MS would probably include it in the OS if they didn't fear a lawsuit from the EU.

I get the impression that Win 7 seems pretty secure and as a Linux user I don't mind having to give permission to allow an administrative action. My wife has been freaked out by malicious popups on websites claiming virus infection. Of course the computer was in no danger, but it's easier to laugh it off if you are using a Mac or Linux.

## Media Sharing 

OK here is my other big bitch. Out of the box my laptop could not access the shared folders on the Linux server on my home network. The problem is due to Windows requiring authentication which most versions of Linux don't support. Fixing this required a lot of messing about with registry settings and lots of rebooting. This would be galling enough, but moves to the realms of infuriating when you realise that if I had Win7 business I could use a built in app called Secpol to fix the issue with a single click. Mac and Linux users don't have to make do with crippled operating system versions and I don't see why I should have to either.

Now you might say I'm a geek and this is a geeks issue which I knew how to fix, but lots of people buy network drives to backup photos and these nearly all run on Linux. For these users their photo back up drive becomes a brick.

On a positive tack my Laptop automatically appears in the menu on my Playstation 3 and seamlessly streams HD video to it without a glitch. Very impressive.

## Other Thoughts

Overall Win7 seems very customisable and user friendly. I've been impressed by the audio stack which allows you to change between the internal soundcard and a USB soundcard while Windows Media Player is playing and have it seamlessly switch playout without a glitch (XP would require an app restart). Lots of people think the Aero Glass window theme looks tacky but I think it looks very clean and adds some candy without getting in the way.

One omission is that seemed a little bizarre is that Win7 supports customisable log in screens but requires a reg hack to make it work. 

The start up and shutdown speeds are acceptable but not amazing and of course with Windows you are limited to a DOS Window rather than the power and elegance of a Bash shell.

## Conclusion 

Overall I think Windows 7 is a huge improvement over XP and Vista. I think I still appreciate the power and flexibility of Ubuntu and if I didn't need Windows 7 for drivers and such it would be a hard decision which I would use as my main OS. With today's announcement of Windows 7 phone it seems like after a few years of getting an whipping in the technical stakes from Apple, Google and the open source community. Microsoft might finally be getting their act together.