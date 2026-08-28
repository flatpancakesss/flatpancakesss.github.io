+++
date = '2026-08-01T13:18:15Z'
draft = false
title = 'Summer 2026 Devlog'
thumbnail = 'images/art/26-08-05.png'
+++

Hello again! I can't believe its been another 3 months already, where does the time go??

I've spent the large majority of my free time this summer working on bringing the game to a "playable" state, most specifically the combat system. It's a little rough around the edges, but its finally in a state where the basic combat mechanics are almost entirely functional.

On top of that, a lot of the core design ideas have been fleshed out alongside progress on the character designs too. 

## Programming

{{< youtube CMyOVSqmJvc >}}

> All assets here are temporary placeholders or leftovers from the Pocket Mirror fangame.
> These assets will be replaced with original assets eventually.

##### YouTube has been fucking with embeds recently, if the video doesnt load in the embed, click [here](https://www.youtube.com/watch?v=CMyOVSqmJvc).

I suppose now is the right time to explain how the battle system works.

The screen itself is divided into two sides of 6 tiles each, the player side at the bottom and the enemy side at the top. Combat is turn-based, and you win once you've defeated all enemies.

Instead of following a traditional turn-based formula, the game functions around an 'actions' system. During your turn, you have a set number of Action Points (AP) that can be spent to command your allies, with each time you command a unit costing 1 action. Once you have no actions remaining, your turn concludes and it's now the enemy's turn to fight back.

However, as long as you still have actions remaining there's actually no limit to how many times you can command the same unit during a turn. Lets say you have 4 party members and therefore 4 AP. Rather than having each character act once, you have 4 individual actions that you can spend however you want. Instead of each ally acting once, maybe you want someone to act twice? Maybe you want to spend all 4 actions on one character? Its entirely up to you.

Additionally, during your turn you can freely reposition your allies on your side of the grid, provided you have enough AP remaining. Positioning is important because if one unit is positioned behind another, the unit in front will take damage first, effectively covering the unit behind them. You can use this to your advantage to protect vulnerable allies from incoming damage!

There's still a few missing features of course, but those will be continued to be worked on in due time. 

## Art

This time around, my general focus has been almost entirely on improving the colour rendering of my drawings, and working on finalising the character designs for the game.

Starting with character design, progress is coming along really nicely!

The game has 5 main girls, with 2 outfits each, making 10 outfits in total to design. Each girl will have a “base” outfit that they wear for the first two thirds of the story, followed by an updated design for the final chapters. As of right now, I’ve completed rough designs for everyone’s casual outfits.

![OC](images/summer2026devlog/OCcharacterdesignsketch.png)

Aren't they super cute? To be honest, it's kind of surreal. A few months ago I could barely draw at all, and now I'm designing and illustrating my own cast of characters. Smaller details are still subject to change of course, but these general "vibe" of everyone is what's laid out right here and that's not going to change.

I also need to spend some time making full illustrations of each character, as I only have rough sketches right now. I'll also formally introduce everyone at a later date, so that I have some more time to work on their designs and character traits.

As I said previously, basic cel shading is not what I want to aim for with my art and that I'm much more inspired by the levels of detail usually seen in gothic horror games. A lot of that detail lies in the colouring and lighting techniques, which is why it has become such a strong focus for me recently.

Since the last devlog, I've been paying close attention to learning such colouring detail, and have made a nice improvement. From here, it’s simply a matter of continuing to practice until I understand it more and more.

![alt text](images/art/26-08-24.png)

##### The most recent example of my rendering process.

## Writing (and how it affects the gameplay)

The current writing hurdle has been connecting both the narrative and gameplay together. I've had a general outline for what happens in the game for quite a while now, but making sure it connects to the game itself in a way that feels logical has been more of a challenge. As plans for the gameplay shifted, I had to adjust the story accordingly. As plans for the story changed, gameplay design had to be changed too. 

At a time before most of the story had been considered, the main concept was to have an open-ended map with the player able to explore and complete the storyline at their own pace. Kinda like GBC Pokemon or Dark Souls 1. However, once work on the narrative progressed, the open-ended map idea began to make less sense. With the girls having a clearly defined goal in the story, wandering around aimlessly just doesn't really make sense anymore, and so I've opted for a more linear "point A to point B" approach.

But on that same note, I don't want to completely take away the aspect of exploration from the player. The game takes place in a fantasy world after all, it would be regrettable to not let them experience that.

The approach I've decided on is that each chapter is "separate" from the others, but each one is still its own individual, explorable environment. Once you progress to the next chapter, you can't go back to the map from the previous one, but you have free reign to explore the current chapter's map. So, instead of one large interconnected world, it's made up of multiple smaller-scale explorable maps, one or two for each chapter.

This structure is similar to how games like Pocket Mirror or The Last of Us work, and I think it's a perfect solution.

To use Pocket Mirror as an example, you can explore Egliette's Ballroom as much as you like, but once you progress into Fleta's Garden, the story moves forward and you can't return to the Ballroom. You can explore Fleta's Garden as much as you like, but once you progress into the Dollhouse, you're once again locked out of the previous area. I think this structure is perfect because it keeps the narrative on a linear track while still allowing the player to explore freely within each area.

I know that's not a lot about the actual "writing", but these decisions are still important as they have a direct impact on the gameplay itself. In terms of actual writing, I've been fleshing out each of the characters, but I'll save what I've written for when I formally introduce them in the near future. 

## Goals for Autumn

Now that the prototype combat system is nearly functional, gameplay programming will take more of a backseat while I spend some time working on the narrative. I can't actually start building levels without having concepted the locations themselves anyway, so working on story and design is just a logical next step. I've already made a large headstart on the story, as I've already created many concepts and a general outline of what happens across the game, so I'm not working from nothing here.

This isn't to say that gameplay programming will be halted entirely, there's still a lot of work that can be done in terms of general polish, and features outside of the main story mode. I'll probably be working on the main progression mechanics of the Abyss mode as it's a mode based more on the gameplay than the story, so there's still a lot I can do there.

Music production is also likely to begin soon, so that the game's world can be fleshed out with an original soundtrack. Production of the music isn't handled by me directly, its commissioned work that I'm paying for out of my own pocket. The composer is super talented and I can't wait to work with them to enhance the game!

If I cant think of a name by the time of the next devlog, I'll come up with a simple temporary working title for the game. Just saying "my game", "my OC game" over and over is getting really tedious, and I'd love to have an actual NAME to refer to the game by... Oh well, I'll come up with something for next time.

Development progress on the game is going at an incredible rate! This game didnt even exist earlier this year and now its really beginning to take shape, I can't wait to share the story and gameplay with you all. Within the coming weeks I will be distributing a prototype to my friends for playtesting purposes. 

It is by no means a finished version of the game, just something similar to the video shown at the beginning of the devlog so that I can recieve some feedback on the main mechanics and gameplay balance which I will then use to improve the game itself. I just need to finish up with the prototype before I can start sending out playtest copies, as right now there's a lot of things that don't work properly yet. Healthbars and damage numbers are in the wrong places, only Ines has functional moves implemented at the moment, etc etc.

And lastly, I'd love to present a lovely illustration of one of the characters, drawn by my friend [4rdilla](https://x.com/4rdilla_/status/2090437631133839781)! It's absolutely incredible to see that someone had liked one of my characters enough to draw her, I am so grateful for your drawing.

![bea](images/summer2026devlog/4rdilla_beako_fanart.png)

Anyways, it's time for me to lock in on finishing up the prototype and writing more of the storyline. I'll see you next time for the Autumn devlog. :)