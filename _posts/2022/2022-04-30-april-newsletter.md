---
layout: newsletterPost
title:  APRIL 2022 - GhostTyrant
date:   2022-04-30

postTitle: APRIL NEWSLETTER 2022
monthYear: APRIL 2022
readTime: 8min
headerPath: /assets/headers/april_2022_hollowKnight.png

tags: april
---

<span style="color:white">IT’S WARM (APRIL)</span>
---

APRIL is here…! It’s warm and sunny! My life force is returning! This newsletter covers MARCH and APRIL and you may read about: COSMO! ART! and my first attempt at playing BLOODBORNE!

<br>
<div class="postBreak" style="border-width:1px;border-color:#ababab"> </div>
<br>

<span style="color:white">’WRITE A COMBAT SYSTEM’ I SAID, ‘IT’LL BE FUN’ I SAID</span>
---

It’s COSMO update time…! I said in the [previous newsletter](/2022/02/28/feb-newsletter.html) that I was working on a few things: a miniboss of sorts, debugging the combat system and porting to a new engine. I have managed to work on all of these things successfully! [sound of cheering] so here’s a little progress update.

{:refdef: style="text-align: center;"}
![scream](/assets/2022_misc/feb_2022_cosmoSlide.gif) \\
*hey remember this guy*
{: refdef}

<br>

At the beginning of MARCH, the mini-boss was basically just a door that screamed at you. At the end of APRIL...it’s still just a door that screams at you, but now it’s a little fancier and my combat system is a little more robust. You could say I got distracted when it came to developing the boss a bit more, instead spending time on some underlying systems. It’s fine. It was necessary work.

I already have an enemy which is small and fast – great for testing parrying and recoil, but this miniboss gave me a great opportunity to test blocking due to the scream attack having an extended duration. So I dedicated some time to sprucing up and debugging that mechanic to get it to a point where it felt useful and cool to use. I also added super armour(?) or knockback resistance for some reason...I think to prevent the player from flying off into the sunset during certain animations. My intentions may be a mystery but it’s a very handy flag to have.

{:refdef: style="text-align: center;"}
![blocking](/assets/2022_misc/april_2022_cosmoBlock.gif)
{: refdef}

<br>

Combat detour completed, I reworked and expanded on some enemy systems to enable both a stationary enemy and an enemy that took damage via external objects – the idea of this miniboss is to destroy the locks keeping it shut, so I made “satellite” objects that tell their parent whether they’re being attacked. Works great! From there I added a rudimentary boss health bar and then descended into my cutscene system again to add some extra functionality for the little intro sequence...and, ta-da! Here’s how it’s all looking:

{:refdef: style="text-align: center;"}
![intro](/assets/2022_misc/april_2022_cosmoIntro.gif)
{: refdef}

<br>

So what’s next? I have no idea! I’ll keep working on this miniboss and get some more attacks in there, and then...who knows? Maybe another enemy? Or some level design? :^)

Finally, I mentioned in the previous newsletter that I intended to port COSMO over to a new engine, LUTRA, which is made and maintained by my good friend [Emmy](https://twitter.com/leafcodes). I’ve made a start on the whole process and Emmy has been working to fill in some gaps in functionality that COSMO relies on, so progress is slow but moving forward. I think it could be some time before this is done but I’m excited regardless! And until then, I’ll continue working on the gameplay.

<br>
<div class="postBreak" style="border-width:1px;border-color:#ababab"> </div>
<br>

<span style="color:white">ART ZONE</span>
---

It’s Art Time! April marked the debut of the newest BLACK ROCK SHOOTER anime: DAWN FALL, and I’ve gotta say, I’m not really into it! I’m a huge BLACK ROCK SHOOTER fan but for some reason this newest anime feels strange and it’s not sitting with me too well. I’ll continue watching it before forming my final opinion but thankfully the original OVA/anime will always exist so I don’t feel too bad about disliking it so far. Anyway, all these thoughts on the brain meant I spent a bit of time doodling some characters – here’s a DEAD MASTER warmup that I spent some extra time on:

{:refdef: style="text-align: center;"}
[![dead master](/assets/2022_misc/april_2022_deadMaster.png)](https://ghosttyrant.co.uk/2022/04/08/dead-master.html)
{: refdef}

<br>

Hey remember that Dante I sketched back in [January 2021](/2021/01/31/jan-newsletter.html)? Well I’m not sure what happened but during April I suddenly became determined to finish rendering it. Perhaps replaying DMC3 a month or so ago put Dante on the brain. Anyway, here he is, all shiny and cleaned up, enjoy!

{:refdef: style="text-align: center;"}
[![dante](/assets/2022_misc/april_2022_danteBP.png)](https://ghosttyrant.co.uk/2022/04/18/danteBP.html)
{: refdef}

<br>
<div class="postBreak" style="border-width:1px;border-color:#ababab"> </div>
<br>

<span style="color:white">GAME ZONE</span>
---

Late February saw the release of ELDEN RING…! I didn’t play it. Instead I figured it was a good opportunity to finally get started on BLOODBORNE – which so far is the only soulsborne that interests me at all. I spent a good few hours learning the ropes, strengthening my guy and facing off against the first couple of bosses...and then I went and played HOLLOW KNIGHT instead. Oops! Oops!

{:refdef: style="text-align: center;"}
![bloodborne](/assets/2022_misc/april_2022_bloodborne.png) \\
*critically acclaimed!*
{: refdef}

<br>

HOLLOW KNIGHT is one of my favourite games ever and I’ve been trying to redirect my pent-up excitement for the upcoming sequel by playing games that are similar. BLOODBORNE is apparently similar, what with it being a sort of boss-focused metroidvania style adventure, but it’s just not quite what I’m looking for.

Why avoid playing the original HOLLOW KNIGHT then? Well I’ve already played it a lot and I didn’t want to burn out on its world and gameplay before SILKSONG was released, but it’s become apparent that the sequel is still some time away (which is fine! I’d rather they took their time!!) so I’ve given in – I am replaying HOLLOW KNIGHT once more. Then, once the titular Hollow Knight has found peace – I will perhaps return to Yharnam...

{:refdef: style="text-align: center;"}
![hollow knight](/assets/2022_misc/april_2022_hollowKnight.png)
{: refdef}

<br>

<span style="color:white">**RESIDENT EVIL 7**</span> - Back in MARCH I finally began my journey into the Baker Household. I’d already seen it through the eyes of various Let’s Players and twitch streamers over the years so I thought there was no way it could scare me too badly but lo and behold – it got me good. Several times. Sometimes a game’s sound design is so good that you become too scared to move from the tiny cupboard you’ve entrusted with your life.

The most embarrassing moment came when I crawled into a small side-room and opened the map so that I could explain in-detail the plot of Telltale’s MINECRAFT STORY MODE to my brother, only to suddenly realise that the game was not paused when Jack Baker kicked the door down and hit me with a shovel. RIP.

Anyway, we had fun. There were some problems (e.g. neither of us find evil little children very scary) but RESIDENT EVIL 7 has successfully restored my brother’s faith in the series, and so I will be progressing on to RESIDENT EVIL VILLAGE in the near future…

{:refdef: style="text-align: center;"}
![resident evil 7](/assets/2022_misc/april_2022_reCat.png) \\
*this is the only screenshot I took throughout the whole game*
{: refdef}

<br>
<div class="postBreak" style="border-width:1px;border-color:#ababab"> </div>
<br>

That’s all! Thanks for reading! As I’m finishing up this newsletter I see that VRChat’s AVATAR DYNAMICS update has gone live for everyone, so I might spend May finishing up my GHOST avatar! Perhaps look forward to that? Otherwise, there’s always work to be done on COSMO or doodles to draw...until next time…!
<br>

<span style="color:lime">Caspar 👻</span>