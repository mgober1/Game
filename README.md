# Game
Introduction: The game is a platformer game that challenges the player's adaptability and reflexes. The game consists of various levels where the player has to jump, run, and avoid obstacles and enemies. However, every 30 seconds, the game randomly changes the controls, such as swapping the buttons, inverting the directions, or adding new actions. The purpose of the game is to provide a fun and engaging experience that tests the player's skills and creativity. The target audience is anyone who enjoys platformer games and likes a good challenge.


Value/Use: A platformer game where the controls change every 30 seconds provides a unique and challenging experience for the players. It tests their adaptability, reflexes, and problem-solving skills as they navigate through different levels and obstacles. The game also offers a variety of gameplay modes, such as single-player, co-op, and competitive, to suit different preferences and moods. The game is designed to be fun, engaging, and rewarding for both casual and hardcore gamers who enjoy a dynamic and unpredictable gaming environment.

User Interaction and Experience:
1. User Interface (UI)

- Platforms: These are the surfaces that the player can stand on, jump from, or land on. They can be fixed, moving, or disappearing, and they can have different shapes and sizes.
- Enemies: These are the characters or objects that try to harm or stop the player. They can be stationary, moving, or flying, and they can have different abilities and behaviors.
- Hazards: These are the environmental features that can damage or kill the player. They can be spikes, pits, fire, water, electricity, or anything else that poses a threat.
- Items: These are the collectibles that the player can find or obtain in the game. They can be coins, gems, stars, keys, hearts, or anything else that provides a reward or a benefit.
- Power-ups: These are the special items that grant the player a temporary or permanent boost or ability. They can be mushrooms, flowers, feathers, capes, suits, or anything else that enhances the player's performance.
- Character: A kangaroo that the player controls.
- Score Display: Displays the player’s current score.
- Lives Display: Shows how many lives the player has left.

-- I want to add an educational aspect to this. We can have like a food chain system where the player 'eats' items that are below them on the food chain, and the enemies are things above them on the food chain. So, for example, if the player plays as a kangaroo, the 'items' can be grass/alfafa/canned meat which all give different score increments. Once score is hits a certain threshold, the kangaroo goes to the next level. Some predators/enemies can be dingoes on the ground and eagles in the sky. There also may be hunting traps that the kangaroo must avoid

-- perhaps there can also be an 'energy' element to it, since the kangaroo is jumping on platforms, and that requires energy. We can get a certain amount of energy from consuming 'items' (so 'items' give you both score and 'energy'). If you don't have enough energy, you cannot jump. However, there should be a lot of items around, and there should be a reservoir of energy (like an 'energy' bar to display energy levels) so the player is mostly fine.

-- we should probably display a countdown of five seconds before the controls switch, as well as a couple of 'control groups' instead of having the controls be randomized. One example of this would be like WASD keys, arrow keys, or numbers. So it would say something like: Controls switching to Arrow Keys Mode in 5...

-- for power-ups...what boosts a kangaroo in nature? Flowers? Special grass? These can maybe make all 'items' give double the energy for a certain time limit, make the kangaroo jump higher for a certain time limit, or increment the number of lives the kangaroo has left

2. Gameplay Mechanics

- Movement: The character's movement is dictatated by the player
- Collecting Items: the player earns points by collecting items and finishing the level.
- Ground Enemies: They move and stay on the ground. They can be defeated by jumping on  them if possible, or dodging them.
- Flying enemies: These are enemies that fly or hover in the air,  They can be defeated by jumping on them if possible, or dodging them.
- Lives and Death: the character loses a life if any part of the enemies other than the top of them touch the character. The game ends when all lives are lost.
- Levels: Completing a level advances you to the next level, with new controls.

3. Aesthetics

- Color Scheme: Bright and colorful.

-- how does the player collect items? I guess the controls are switching every 30 seconds, so that might be hard to define. Perhaps we should change the switch time to 10 seconds. 30 feels a little too long for a game, after all. 

-- ground enemies are the dingoes, flying enemies are the eagles. can kangaroos jump on eagles? perhaps instead of jumping on them, the kangaroo could 'kick' them-- this would require to add sprite animations, though. Maybe each enemy could have a small hp bar. When the player defeats an enemy, they gain the equivalent of the amount of hp the enemy had in their score. 1 hp = 1 kick with no power-ups. Should 'kicks' require 'energy'? I feel like that might be too hard. Oh, perhaps some enemies could be traps or gates that block 'items', and you need to kick them a certain amount of time to break them down so you can reach the 'item'. Reminder that 'items' are food like alfafa that give you score and energy. This isn't meant to be a puzzle game, though...

-- how would levels work? More on this later?

-- i would like something like a savannah or whatever the kangaroo's natural habitat is as the scenery. Although the game isn't totally realistic, there is that educational aspect I want to keep. I feel like the color scheme shouldn't be too bright, since it could hurt people with sensitive eyes. Everything should have clear edges so that they are easily distinguishable from other objects in the game. It would be cool to have sound effects like whooshing noises when the kangaroo kicks an enemy, or chomping noises when the kangaroo consumes a grass 'item'. There can also be a change in the background music when the kangaroo is actively using a power-up, and the kangaroo can glow a little, so that they player knows clearly when the power-up's duration is over. The font should be simple and readable, something a mix of Times New Roman and a straight handwriting font. I think that would match the aesthetic of this game.


Competitive Element: This game can facilitate competition among students by challenging their adaptability and creativity. The game requires the players to quickly learn and master the new controls, while also navigating the obstacles and enemies in the game world. The game includes a leaderboard with players in order of who has the most points.

-- i wonder if we could choose to start at a certain level, or if we have to work ground to up. I feel like if there's a storyline, we should make sure that you have to start from the first level, but then if you have passed a bunch of levels and then you die, you can retry from the latest level you died at, or any other level before that level. To track users, then, we would need some kind of authentication page, since this would be different from everyone. We should track individual's high score throughout the different times they play the game, as well as a mass scoreboard for the public.

Engagement and Addictiveness Strategies: The game can foster a sense of achievement and fun, as the players can compare their scores and strategies with their peers. Providing feedback and rewards for the players' performance reinforces the players' sense of progress and accomplishment, as well as encouraging them to replay the game and improve their scores. The game can also varying the level design and difficulty can help increase engagement and lead to more players wanting to see how the game changes as they continue to play. Lastly, incorporating a story or a theme that connects the gameplay elements and gives them a purpose. This adds an emotional and narrative dimension to the game, as well as making the players curious about what will happen next.

-- i am very in pro of a storyline. I like having a storyline in a game, since it makes it more engaging and makes me want to find out what happens next. But for a kangaroo educational game....maybe it can be about a kangaroo who has to go on a journey to find his long lost mother or something who was taken away by hunters (?). The kangaroo has to go through a lot of hardship (enemies, traps) and unexpected situations (controls switch) but ultimately grows and adapts to the terrain. Maybe at the end of each level, the kangaroo can find a clue or puzzle piece telling it where its mother is. At the very last level, the kangaroo pieces the pieces (haha) together, and finds its mother. Yay! This is pretty emotional, right? In that case, the kangaroo's scenery might not only be limited to the savannah. If the kangaroo is moving around searching for its mother, it might encounter different terrain such as rainforests and underwater (put a diving suit on the kangaroo, this level could have some properties like higher jumps because water bouyancy and different enemies like sharks). This would indeed be quite interesting. That would mean the kangaroo needs a lot of different skins, though, for each level. Or, well, I guess you don't need a special skin in the rainforest. But maybe every level has some kind of pre-built-in power-up, like with underwater you jump higher, and with rainforest, 'items' give you 2x energy since its super nutritious or something.

Scalability and Expansion: A platformer game where the controls change every 30 seconds is a novel and challenging design that can attract and retain players who seek variety and unpredictability. The game can also appeal to casual gamers who want to have fun without mastering complex controls. The design allows for future growth and adoption by enabling the developers to create diverse levels, modes, and scenarios that test the players' adaptability and creativity. The game can also leverage user-generated content and social features to foster a loyal and engaged community.

Accessibility and Inclusivity: By changing the controls every 30 seconds, no player has an unfair advantage or disadvantage based on their physical or mental abilities, preferences, or backgrounds. The game also provides options for players to customize the controls to suit their needs and comfort levels. (listed below)
- Allowing players to choose the frequency and type of control changes, such as switching between keyboard, mouse, gamepad, or touch inputs.
- Providing clear and consistent visual, and auditory feedback that indicate the current control scheme and the upcoming changes.
- Offering different difficulty modes that adjust the speed, complexity, and number of obstacles in the game.
- Using simple and intuitive user interface elements that are easy to read and navigate.