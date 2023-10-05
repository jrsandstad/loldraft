# loldraft

> Development page for a website for a drafting and comparison tool for the video game League of Legends (LoL). This is a hobby project for personal usage and is not related to LoL or Riot Games.

## The inspiration

The idea for this project stems from the website [drafting.gg/draft](http://drafting.gg/draft). The website is created by popular League of Legends streamer know as [LS](https://twitter.com/LSXYZ9). The tools intention is to simulate the drafting phase during of a ranked match in League of Legends.

## The problem

There is several things that could be improved upon on [drafting.gg/draft](http://drafting.gg/draft). One of the issues surrounds the user base the site was developed for, which is typically professional or highly ranked players. These players have been playing the game for a while and knows the champions, matchups, and the complex mechanics that is present in League of Legends.

The site therefore shows little info in addition to its primary function of simulating a drafting phase. This is not an issue for the intended users who know the game in and out, but it makes it basically useless for new or returning players. With typically 2 or 3 new champions being released a year and a game that is constantly chaning, it can be difficult to get a grasp on the strengths and weaknesses of champions as they are being released or reworked.

## The solution

This is my proposed solution in order to create a drafting tool that is helpful to new or returning League of Legends players.

### Drafting tool

- Create a drafting tool similar to the one found on [drafting.gg/draft](http://drafting.gg/draft)
- Compare strengths/weaknesses in team compositions between blue and red side
    - Ex.: Blue side has champions with a lot of CC which is good against the champions on red side. Red side can avoid this by picking these champions with more mobility
- Compare strengths/weaknesses in the champion bans
    - Ex.: Blue side has banned champions typically only played in the jungle. Perhaps diversify your banned champions with other roles.
    - Ex.: Red side has banned champions with low pick rate. Perhaps ban champions with a higher pick rate in order to counter your blue sides picks.

### Word list

- Create a list of the many words and terms of League of Legends
    - Ex.: What is crowd control (CC)? What is the difference between armour penetration and lethality? What are krugs? What are creep score (CS)?

### Sorting options

- Sort by using roles: top, jungle, mid, bot, and support
- Sort by using sub-roles such as: assassin, bruiser/fighter, tank, etc.
- Sort by damage type (AD/AP)
- Sort between ranged and melee champions
- Sort by using a difficulty scale
    - Easy, intermediate, challenging
    - Use Riots own difficulty ranking
- Sort by win rate, pick rate, and ban rate
    - No access to Riot’s API for this, so using static data gathered from [op.gg](http://op.gg) or [lolalytics.com](http://lolalytics.com/) might be an alternative. Perhaps randomly generate values.