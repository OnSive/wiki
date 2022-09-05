---
sidebar: auto
---

# Rangering & Pointguide
Skrevet af Teknoz

*Stor tak til Flee for at rette grammatiske fejl og give nyttige oplysninger.*

:::warning Disclaimer Denne vejledning blev oprindeligt skrevet den 7. februar 2019. Den er blevet opdateret flere gange, men nogle oplysninger kan stadig være unøjagtige eller mangler. Hvis du bemærker unøjagtigheder/manglende oplysninger i denne guide, du kan indsende en pull-anmodning på [BSMG Wiki GitHub](https://github.com/bsmg/wiki#readme) eller sende mig en besked på Discord (TeknozFR#6900). :::

## Nøjagtighed og Scoring

### Scoremultiplikator
Din scoremultiplikator kan ses nedenfor, er omgivet af en ydre ring. Som sagt i navnet, har multiplikatoren en effekt på din score. Du starter sangen med en multiplikator på **1x**, og den ydre ring viser progressionen til den næste multiplikator. Når du rammer blokken, der bringer dig op til den næste multiplikator, er blokken selv påvirket af den nye multiplikator og ikke den gamle. De forskellige multiplikatorer er: **1x, 2x, 4x og 8x**. Hver gang du mister din combo, der indebærer at du misser en blok, skærer i den forkerte retning eller med den forkerte saber, rammer en bombe eller går gennem en forhindring, vil din multiplikator blive halveret.

![Scoremultiplikator](~@images/ranking-guide/score_multiplier.png "Scoremultiplikator")

### Scoring
At score godt i Beat Saber er ikke så simpelt som at holde en høj combo og ikke misse blokke, det er nemlig også bestemt af din score per blok. Den højest mulige score at opnå ved at skære en blok er **115** (uden at tælle scoremultiplikatoren). Når du skærer en blok, skal du opnå de korrekte svingvinkler, og du skal skære blokken i midten for at opnå den bedste score for dit snit.

Her er hvordan scoren beregnes for et snit:
| Komponent         | Scoringsværdi |
| ----------------- | ------------- |
| 100° Før Snittet  | 70 Point      |
| 60° Efter Snittet | 30 Point      |
| Rammer i midten   | 15 Point      |

This shows how important it is to do proper swings to get the right angles and the best score possible. Remember, it’s better to get a bad cut than a miss since a miss counts as **0 points** and breaks your combo.

### Hitbox
A common misconception in Beat Saber would be that most people think that the hitboxes for the notes are the blocks themselves. While that used to be the case, the hitboxes have changed quite a few times through the different versions of the game and a lot of the pictures out there are mistaken. Here is an image showing the current hitbox. As you can see, the hitbox is pretty big and extends a lot on the sides and the front. With this information, it is recommended to hit with the tip of the saber to maximize the angle and get the best cut possible.

![Hitboxes](~@images/ranking-guide/hitbox.png "Hitboxes")

### Nøjagtighed
Accuracy is shown on the left after enabling the **Advanced HUD** option in the Player Settings. Accuracy is shown by a percentage and a letter. While the best "possible" accuracy is **100%**, it is practically impossible since it would require no combo break and 115 cuts on every block. Even then, accuracy is still a great way to measure performance on a map and one’s ability to score properly and avoid missing notes. Accuracy is calculated using information such as the scores per hit, the score multiplier and the amount of miss.

Here is the connection between the letters and accuracy percentage:
| Letter Grade | Accuracy Percentage |
| ------------ | ------------------- |
| SS           | 90-99.99%           |
| S            | 80-89.99%           |
| A            | 65-79.99%           |
| B            | 50-64.99%           |
| C            | 35-49.99%           |
| D            | 20-34.99%           |
| E            | < 19.99%            |

## Rangeringsprocessen

### Rangeret / Urangeret
A lot of people (like I did) will spend dozens and dozens of hours without knowing the difference between ranked and unranked maps when they start. While a map being ranked doesn’t make it better for any reason, it’s great for new players to learn what the difference is, especially if they ever decide to try ranking up.

#### Ranked
A ranked map is assigned a certain difficulty level measured in stars (★) and is worth a certain amount of PP (performance points) for that difficulty. An amount of that PP can be earned by a player for completing the map. More PP will be rewarded for a player that got a higher accuracy. Ranked maps *mostly* respect criteria and are considered as "good maps". They are the only way to climb the [global leaderboard](https://scoresaber.com/global).

#### Unranked
An unranked map is any map that has been published on [BeatSaver](https://beatsaver.com/). It does not need to be actually possible to pass and maps can be made by anybody using the a mapping editor. Also, it is not possible to know the difficulty level of an unranked map except by looking at the difficulty name which is not always an accurate measure of the difficulty since the mapper chooses it.

### Kriterier og rangeringsprocessen
The ranking team ranks maps through a communal evaluation process. Those maps are then assigned PP based on an algorithm that determines the difficulty once they are ranked based on a variety of factors. PP, which stands for performance points, is given for completing ranked maps based on how high you scored in the level. Full details about the ranking process, criteria, and additional FAQs can be found in the [ScoreSaber Discord server](https://discord.com/invite/WpuDMwU).

## Rangeringssystemet Forklaret (PP Systemet)
The PP system is probably one of the most misunderstood things when it comes to ranking in the game. Personally, I find it that people misunderstand it so often that I ended up writing a message about it and pinned it on the Beat Saber Canadian Discord so I wouldn’t need to explain it anymore, so here is "all" you need to know about it.

### Hvordan kan jeg få PP, og hvordan fungerer den globale rangplacering?
You can find your global ranking on [ScoreSaber](https://scoresaber.com/global) by typing your username in the search bar. Your ScoreSaber profile is tied to your Steam/Oculus profile on which you play the game.

As said earlier, you can earn PP (performance points) by playing ranked maps. The amount of PP a map is worth is determined when the map is ran through the PP algorithm. The algorithm is kept secret to prevent mappers from trying to intentionally make songs to only be worth a lot of PP (to avoid breaking the system basically). The exact amount of PP gained by a player is determined by their accuracy on that map and the curve it represents compared to the max amount of PP that map is worth. You can find more information in the [ScoreSaber Discord server](https://discord.com/invite/WpuDMwU).

### Hvordan virker PP-systemet, og hvad er vægtet PP?
To prevent skilled players from grinding hundreds of easier maps worth less PP to rank up, a curve is applied to your plays. This curve is **0.965^(x-1)** where **x** is the position of that score on your ranked map list which can be found on your profile.

You might have noticed that in your list, there are 2 numbers which end with PP. One of these numbers is **blue** and represents the raw amount of PP you get from that play, before the curve is applied. The second number is gray and in parenthesis showing the actual weighted amount of PP you are getting from that play after the curve is applied.

![Raw and Weighted PP](~@images/ranking-guide/raw&weighted_pp.png "Raw & Weighted PP")

As said before, the amount of weighted PP you will receive is determined by the curve and the placement of that song in your list. As an example, if your top play is a **260 raw PP** play, you will be rewarded **260 weighted PP** which is a **100%** of the raw PP of that play. If your second top play is **247 raw PP**, you will be rewarded **238 weighted PP** which is the actual amount of PP you get after the curve is applied on it.

Here is an example of how the curve works:
| Raw PP | Weighted PP                  |
| ------ | ---------------------------- |
| 260pp  | **260pp** (100% of raw PP)   |
| 247pp  | **238pp** (96.5% of raw PP)  |
| 246pp  | **229pp** (93.1% of raw PP)  |
| 244pp  | **219pp**  (89.9% of raw PP) |

### Hvorfor stiger min samlede PP ikke lige så meget som den vægtede PP jeg fik på min nye score?
A common question people seem to have when they get a new score worth, for example, **100 weighted PP** is why they are not getting **+100 pp** on their total amount of performance points. As explained earlier, since the effect of the curve on your plays increases the further you go down your list, when you make a new play, it takes the place of an older play which makes all the plays that are under go down 1 place in the list. Even if you are getting **+100 pp** from this new play, all your lower plays are weighed down even more than before so you lose a certain amount of PP on them. This is why when getting a new play or making a better play on a map, you will never (one exception) get the same amount of PP on your total amount of performance points.

The only exception to this is if you get a better accuracy on your current top play. Since your top play is not affected by the curve, meaning that none of your songs will change places in your list, there will be no lost of PP on your other plays. An example would be if your top play is on Avalanche with **250 pp** and you manage to get a better accuracy and that play is now worth **260 pp**, you will then get **+10 pp** on your total amount of PP.

### Hvordan kan jeg forbedre og få flere PP?
To improve and get a better rank in the global ranking, there are quite a few tools you can use to find ranked songs that fit your skill level. First, it’s always good to go see your own [ScoreSaber](https://scoresaber.com/global) profile to see songs that you haven’t played in a while or that you could improve on and to know what your top scores look like. The [ScoreSaberEnhanced](https://github.com/Splamy/ScoreSaberEnhanced#readme) or [ScoreSaber Country Leaderboard](https://github.com/motzel/ScoreSaberCountryLeaderboard#readme) browser extension can extend the functionality of your profile. [BaliBilo's ScoreSaber site](https://scoresaber.balibalo.xyz/peepee) and [Beat Savior](https://www.beatsavior.io/) are external sites that can help you find maps to improve on and keep track of your performance.

For more precise tips and tricks, go refer to the [Useful Tips & Links](#useful-tips-links) chapter.

## Modifikatorer

### Modifikatorer & Rangerede sange
When it comes to ranked maps, all the **Negative Modifiers** such as No Fail apply on the score. This means **Negative Modifiers** can be used on any ranked map but they will obviously penalize your score and reward less PP. **Positive Modifiers** only take effect on two ranked maps as of now; [Overkill mapped by Nuketime](http://scoresaber.com/leaderboard/87194) and [Overkill mapped by Kry](http://scoresaber.com/leaderboard/86492). They are used to test the effects of **Positive Modifiers** on ranked maps and to find a way to integrate them on all the other ranked maps. You can obviously play any other map (including ranked ones) and the modifiers will all work but they will only increase your score and PP on the two versions of Overkill. The modifiers used on any score on the leaderboards can be seen to the right of the score.

With this said, here is a list of all the modifiers in the game, their effects on score and how they affect gameplay:

<!-- markdownlint-disable MD013 -->
| Modifier                    | Description                                                                                                                                                                       |
| --------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| No Fail (0.00/-0.50)        | Acts as a safety net letting you continue playing if you fail. As of version 1.13.2, this modifier applies the score penalty only if you lose all of your health during the song. |
| No Walls (-0.05)            | Removes all of the obstacles (walls) from the map.                                                                                                                                |
| No Bombs (-0.10)            | Removes all of the bombs from the map.                                                                                                                                            |
| No Arrows (-0.30)           | All notes become dot notes, meaning you can hit them in any direction!                                                                                                            |
| Slower Song (-0.30)         | Slows down the song to 85% of the original speed.                                                                                                                                 |
| 1 Life (0.00)               | Makes you fail on the first miss you make.                                                                                                                                        |
| 4 Lives (0.00)              | Stops the health bar from replenishing. This limits the total amount of misses and bad cuts you can have before failing.                                                          |
| Disappearing Arrows (+0.07) | Makes the arrows disappear from the note as they approach you. You still need to remember the direction as you need to cut in the correct direction as always.                    |
| Faster Song (+0.08)         | Speeds up the song to 120% of the original speed.                                                                                                                                 |
| Super Fast Song (+0.10)     | Speeds up the song to 150% of the original speed.                                                                                                                                 |
| Ghost Notes (+0.11)         | Notes are invisible and the arrows disappear shortly before you hit them, similarly to Disappearing Arrows.                                                                       |
| Pro Mode (0.0)              | Changes the hitboxes to match the notes precisely.                                                                                                                                |
| Strict Angles (0.0)         | Tolarace for a good cut angle is reduced                                                                                                                                          |
| Small Notes (0.0)           | Changes the notes to 50% normal size                                                                                                                                              |
| Zen Mode (-100)             | No notes, walls, or bombs. Just the music and the lights!                                                                                                                         |
<!-- markdownlint-enable MD013 -->

## Greb

### Hvorfor skal jeg bruge et greb?
An alternative grip can be an adjustment of the default saber angles, an alternative method of holding the controller, or a combination of both. There's no single grip that works for everyone, and using an alternative grip won't magically make you better at the game. It is not necessarily better than the default way the controller is meant to be held, or the default angles that Beat Saber uses. However, alternative grips can have many benefits, from being more comfortable for long periods of play to helping you optimize your swings. They can redistribute the weight of a poorly balanced Vive wand, or increase the range of wrist motion with a Touch controller. Below are some popular grips used in the competitive community. Don't be afraid to adjust or experiment to find what's right for you!

### List of Grips
Refer to the Grips section of [Grips And Tricks](./grips-and-tricks.md) for some examples of commonly used grips used in the community.

## Nyttige Tips & Links

### Tips & tricks
After all this time playing Beat Saber, I’ve hit many walls. Hitting a wall can be really annoying since it can take time to figure out what to do to keep improving. Here is a small list of tips to improve as a player.

#### Challenge yourself
While it sounds obvious, many players never try to improve and play harder maps and simply play the same maps over and over again. Extend your song list and push yourself to learn the things you are the worst at.

#### Play more
You don't get better at playing an instrument without a lot of experience. The same goes for Beat Saber - simply playing more will improve pattern recognition, condition your body, and build muscle memory.

#### Evaluate your own gameplay
Optagelser af dig selv er fantastisk til at se, hvad du kan forbedre, hvad end det kun er dit gameplay eller om det er med et webcam. Analyse af dit eget gameplay kan være virkelig nyttigt til at se dine mest almindelige fejl. You can also watch your own replays by clicking the info icon next to your score in the leaderboard, then the button in the top right corner of the info card.

Note: Quest currently requires an additional mod to record and watch replays.

#### Watch better players play and ask them tips
Hvis du har muligheden, så prøv at se bedre spillere og brug nogle af deres teknikker til at blive bedre. Copying everything about a pro player won’t make you one but can surely help you improve. Watch their replays and compare their movements to your own. Derudover, hvis du nogensinde får muligheden, så spørg altid efter gode råd (bare ikke vær irriterende eller respektløs).

#### Don’t overthink it
If you can’t finish a map or can’t achieve a higher score, don’t overthink it. I made the mistake of getting angry over this way too many times and it will create a mental wall. Simply play another song and come back to it another day.

#### Practice hard patterns
If you are struggling with a section of a map, slow it down with the Slower Song modifier or decrease the speed in practice mode.

#### BSRA
Check out Cube Community's [Beat Saber Replay Analysis playlist](https://www.youtube.com/watch?v=rxf68rH4S20&list=PLwx5EB8PdMNdElyEBfO7VktSWSNZukfqP). This series help viewers understand how top Beat Saber plays are made and how they can improve.

#### Have fun
At the end of the day, this is a game. The important part is that you have fun and enjoy playing it. If you hate playing this "one ranked map that sucks but is worth so much PP", then simply don’t play it. Don’t try to force yourself to play songs you dislike and play however you want. It’s when you have fun that you’ll see the time fly by and you’ll improve the most. If you don’t care about rank, it’s all good, just have fun 🙂

### Links

* [ScoreSaber](http://scoresaber.com/) Official website with the leaderboards for all the maps and the global ranking leaderboard
* [ScoreSaber Discord](https://discordapp.com/invite/WpuDMwU) Official ScoreSaber Discord to get informed about maps getting ranked, criteria, etc
* [BaliBilo's ScoreSaber Site](https://scoresaber.balibalo.xyz/peepee) Get play suggestions based on your scores to improve your global rank
* [Beat Savior](https://www.beatsavior.io/) Track your ranked stats and performance