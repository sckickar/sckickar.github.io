---
title: Warheadz Devlog
date: 2022-09-22 16:08:00 Z
categories:
- dev
---

**THIS PROJECT IS ABANDONED**

**Day 0**
I didn't know brainstorming original ideas would be hard. It took me 4 hours to come up with a good and marketable idea. Thanks to the theme being a bit free and lax, I can experiment with previous ideas implemented by other games.

I have decided to copy the core idea of Sneak Ops but with a twist: you cannot stay idle for a very specific amount of time. This will make the game inline with the theme of "Keep Moving". The movement for the game will be a one-thumb experience, including moving, shooting, and interacting.

The real challenge here is that I will be in the office next week. I will need to discipline myself this time if I want to win that $10,000 cash prize, or win in general.

See you in the next update!

**Day 1**
Movement and collisions are done, thanks to my older game prototypes that already had those in place. It was a breeze to implement and relatively quick.

![image.png](/uploads/image.png)

So far, so good. I will now add a simple enemy AI, a shooting mechanic, and the core gameplay on Day 2 (procrastination is a bitch). The planned core gameplay is that there will be a timer somewhere in the game that keeps track of the player when they're not moving. It will alert all the enemies in a certain radius to go to the player.

Adieu, see you in the next update!

\
**Day 2**

\
Finally got the AI to work correctly, but the code is a mess. I might need to refactor this once I get the other parts done. I also got the shooting mechanics and the core gameplay set. Now it's just a matter of implementing the theme of the game, which is the "Keep Moving" motif.

The AI was time-consuming to implement. Thankfully, there are a couple of implementations from previous source codes that I have gathered through all the years of my learning in Game Maker Studio.

![GIF 06-10-2022 9-23-24 pm.gif](/uploads/GIF%2006-10-2022%209-23-24%20pm.gif)

From this fucking jank to this

![GIF 06-10-2022 10-29-50 pm (1).gif](/uploads/GIF%2006-10-2022%2010-29-50%20pm%20(1).gif)

Now the AI feels a lot more natural.\
I have also implemented some shooting mechanics as well

![GIF 06-10-2022 11-38-23 pm.gif](/uploads/GIF%2006-10-2022%2011-38-23%20pm.gif)

\
I must say, the placeholder looks gorgeous, even for placeholder standards.

So far, so good. It feels very satisfying to see the progress from Day 0 to Day 2. Maybe, just maybe, I'll look at this in the future and feel proud of myself for this endeavor. Whether I win or not, the experience this has given me is unlike anything I have ever experienced before.

I might have to set up VCS for the project this Friday. Now the next problem will be level design and the art for the game, both of which are way beyond my skill set. I guess I'll have to bite the bullet this time and crack my fingers again. Or maybe I can borrow some sprites from other games—we'll see.

Thank you for reading, self. Now, on to the next update. See you tomorrow!

\
**Day 3 and 4**

Not much happened during the third day, but there was a huge revamp in how the AI works on Day 4. Unfortunately, the internet died (thanks a lot, PLDT, you bitch!). Updates will resume on Day 5. This will include the graphics, some levels to make way for the story, new enemy types for added variety, and a user interface.

The fucking ISP bitched out, so I have to move the levels and graphics updates to the 5th day. Thanks a lot, PLDT!

See you tomorrow with some real updates.

\
**Day 5**\
So, something came up while I was having a smoke break—an epiphany, in a sense.

I figured making this a story-oriented game with stealth mechanics looks, feels, and sounds a bit boring. The gameplay is now changed from a stealth game to a roguelike room jumper. The added mechanic this time will be that the current section you're in is timed, encouraging you to keep moving.

Since the game already has functional chase AI, I figured I might as well turn them into melee-type enemies. Thankfully, I'm still not that far off progress-wise.

![GIF 10-10-2022 11-06-32 pm.gif](/uploads/GIF%2010-10-2022%2011-06-32%20pm.gif)

\
Well, it's a good thing I thought of this now.

*So, what's the new mechanic like?*

The game would throw you into a section of the room, and the game will start counting down to a specific timer. Once the timer is reached, it will throw you into a new section of the room, discarding your current items and giving you a new set of weapons.

All right, let's get to it then. The to-do list is now updated to remove the old mechanic. Quite surprised it removes the skill overhead needed to finish the game.

See you in a bit!

**Day 6**

\
The office is starting to tire me physically. I might just crunch the rest of the features on Friday, but if I can find the time and energy to do them before then, I'll take that chance!

![GIF 11-10-2022 9-33-54 pm.gif](/uploads/GIF%2011-10-2022%209-33-54%20pm.gif)

Added some sprites because the game is now renamed to Warheads (it's a crappy joke). Progress is good at the moment, with some minor slowdowns due to work, but I'll do everything in my power to finish this before the deadline.

Not much to show today aside from the added graphics.

I also tried exporting the game on GX, and I'm surprised by the performance. However, I have to remove the window scaler since the GX exporter has some problems with the rendering.

I might have to reverse Wasteland Kings or use RGBA to map for the level generation. I'll probably split both if I have the time: Wasteland Kings generator for endless mode and RGBA for the main game.

Until then, ciao!

**Day 7 and 8**

![GIF 14-10-2022 10-47-47 pm.gif](/uploads/GIF%2014-10-2022%2010-47-47%20pm.gif)

Well, it looks promising now. Random map generation took me about three days to finish, on top of my work schedule.

But I'm happy with the result. I just copied the code from Nuclear Throne.

A few problems with the Nuclear Throne source code are that it's messy and hard to read, and mp_grids don’t work with randomly placed objects.

It took me two days to figure out that mp_grid cells aren’t 1:1 with the room, and I had to convert it to cell coordinates for it to work. Luckily, there is an existing implementation lying around.

So far, so good with where things are going. Now I just have to figure out how to properly satisfy the jam theme. I’ll probably figure it out tomorrow.

That’s probably all for now. See you in a bit!