# Welcome to Sobriket's Github! 👋

Hey! I'm Maxime, a student developer at Creajeux Nîmes. I'm heading into my final year of studies. Here are some projects I've worked on, feel free to give them a try! 
## >> AI Tactics <<

This is my final year study project. The goal is to create an AutoChess/AutoBattler gameplay and incorporate an AI capable of playing against the player using machine learning, specifically <I>Unity MLAgents</I>.

### Project progress :

#### What is already done :

- The board : A 7x8 hexagonal grid with 2 rows of 9 square-shaped tiles.
  
   ![arena](https://github.com/user-attachments/assets/eaa62d73-2622-487e-86b1-acf66441d488)
- Units Stats : Units have various stats, such as attack speed, health points, damage, penetration, and armor.
- Units Pathfinding : Implemented using a simple breadth-first algorithm, which handles units with different ranges.
- Units Traits : Each unit has a trait and a race. The passives associated with these traits are not implemented yet, but units are built according to their traits, and their stats align with them.
  
   ![Units](https://github.com/user-attachments/assets/78952f46-d276-4f8f-839f-94e736e8b04c)
- The Shop : Inspired by <I>Team Fight Tactics</I>, the shop offers a choice of three units, each with a specific rarity and cost. Players can see their gold amount and experience points. They can buy experience and check how much is needed to level up. Each level allows players to place one more unit on the board.

   ![Shop](https://github.com/user-attachments/assets/a26760b2-5871-4a09-951a-749355440248)
- The Machine Learning : <I>Unity MLAgents</I> has been incorporated into the project, and I’ve learned a lot about configuring agents to train together using the self-play hyperparameters in the configuration file.
I successfully transformed my base project into a machine learning environment and am currently at the second checkpoint on my goals list :

   ![Golas](https://github.com/user-attachments/assets/3cfca883-5672-40f0-b203-562f01e3459e)






## >> Sand Simulation <<


> Try the game [here](https://sobriket.itch.io/sand-simulation)

This a minimalistic sand simulation made on Unity.

![Screenshot_3](https://github.com/user-attachments/assets/9cb4f8d4-5af4-433f-b2c3-cb019023fe16)

<blockquote>
<b>Engine used :</b>  Unity<br>
<b>Team size :</b> 1 <br>
<b>Project duration :</b> 2 hours
</blockquote>

## >> Hexasphere <<

> Try the game [here](https://sobriket.itch.io/hexasphere)

This is a planet generator based on an hexasphere shape made from an icosahedron.
You need to download the project if you want to test resolution 6 and 7.

First, I created the icosahedron shape.

Then, I divided each triangle into four smaller triangles, with each new point equidistant from the center. 

Finally, I generated hexagons from each point, resulting in a hexasphere.

Once I had the hexasphere, I used 3D Perlin noise to increase or decrease the distance from the center of each hexagon.

Then, I formed hexagonal-shaped cylinders. 

Finally, I created a shader that applies color to each hexagon based on its distance from the center.

![egazg](https://github.com/user-attachments/assets/437ed3f3-656b-457a-9762-650446b4835a)

<blockquote>
<b>Engine used :</b>  Unity<br>
<b>Team size :</b> 1 <br>
<b>Project duration :</b> 2 weeks
</blockquote>

## >> Deeper In My Mind <<

> Try the game [here](https://sobriket.itch.io/dimm)

This game has been made for the CreaJam 2024 on Unity. 
The theme was "Deeper and Deeper" with an optional constraint "Black & White".

It's an endless runner in first person view, you're playing in a bicolor environment where you have to dodge donuts, crystals, fans and brick walls. 
Your goal is to go the furthest possible.

In this game, I was responsible for map generation, including obstacles.

The map is divided into sections along the main slope, with each section featuring its own environment.

I quickly developed a system to manage each type of obstacle and attach them to the main slope.

I did a black and white post processing shader to match the game atmosphere.

![image_2024-10-15_114221792](https://github.com/user-attachments/assets/2be74d62-1db3-4712-871e-35ba4b0c1827)

<blockquote>
<b>Engine used :</b>  Unity<br>
<b>Team size :</b> 5 <br>
<b>Project duration :</b> 3 days<br>
<b>Tasks :</b> Map generation and shaders
</blockquote>

## >> The Rite <<

> Try the game [here](https://sobriket.itch.io/the-rite)

You are a young Skrokac and you're about to undergo your coming-of-age ritual.
You've been training for this for as long as you could remember,however, everything that could go wrong, will go wrong.

In this project, I took on the role of lead, primarily helping others and guiding the team.

I worked on the player character, focusing especially on the "Hypervision" power, which allows the player to see elements of his world through walls and provides hints to solve game puzzles.

I created several post-processing shaders to achieve this effect.

Additionally, I maintained a good flow of information within the team.

![Sans titre](https://github.com/user-attachments/assets/f46a7ccc-e81e-4568-97ab-bafeeecd35ea)

<blockquote>
<b>Engine used :</b>  Unity<br>
<b>Team size :</b> 11 <br>
<b>Project duration :</b> 5 months<br>
<b>Tasks :</b>Project management,shaders,multitask support
</blockquote>

## >> Dominion Corp <<

> Try the game [here](https://sobriket.itch.io/dominion)

It is a game where your goal is to mine asteroids with the help of your drones and gather as much resources as you can.

In this game, I worked on mining resource management and shaders. 

I developed tools to create new mining resources, planets, and solar systems. 

I also created a mining beam that changes color for each resource type, as well as the outlines of the asteroids and the starfield background. 

![Screenshot_1](https://github.com/user-attachments/assets/3b1d3975-def5-44b4-b6d2-53b802b7e402)

<blockquote>
<b>Engine used :</b>  Unity<br>
<b>Team size :</b> 2 <br>
<b>Project duration :</b> 6 months<br>
<b>Tasks :</b> Shaders, data gameplay programming 
</blockquote>

## >> Minion Invasion <<

> Try the game [here](https://sobriket.itch.io/minion-invasion)

A long time ago, in a fantasy medieval world, a magic portal was mysteriously opened, pouring hordes of monsters in these peaceful lands. 

The kingdom's army needs to mobilize to repel the invaders."

In this game, I had to create player spells:

- The first one creates a zone where meteors spawn to kill enemies.
- The second one creates a zone that empowers the player's turrets.

When I finished those tasks, I mainly helped others with their tasks, such as upgrading towers (I worked on the mage tower), improving enemy pathing, and building the map.

<b>![NRrkFq](https://github.com/user-attachments/assets/f8bd76b7-26ba-4cd5-adc5-efe55a85da0c)</b>
<!--
<b>![UQCsJh](https://github.com/user-attachments/assets/e8f5f05e-85fd-4adf-8fd8-f178ffa0fde9)</b>

<b>![ZSA1V5](https://github.com/user-attachments/assets/f28430fb-deaf-4191-a46b-85f715a79ac9)</b>

<b>![ezG9xH](https://github.com/user-attachments/assets/e7339b94-d7a5-4379-992c-c176f93b91e0)</b>

<b>![07HMpR](https://github.com/user-attachments/assets/e2e33284-ef18-43c0-a1d3-fb2047aeab4e)</b>
-->
<blockquote>
<b>Engine used :</b>  Unity<br>
<b>Team size :</b> 10 <br>
<b>Project duration :</b> 5 months<br>
<b>Tasks :</b> Player Spells,multitask Support
</blockquote>

## >> Rogue Like Project <<

> Try the game [here](https://sobriket.itch.io/rogue-like-test)

This is a rogue like test/prototype and the first project I did on Unity.

In this game, I was responsible for map generation. 
I started by creating the main path (from the start to the end) and then randomly placed rooms next to this path until I had no more rooms to add.
I designed every type of room. The goal was to include many enemy rooms (we stopped at one), a shop, a loot room, a secret room (accessible with a key), an empty room, and a room where players can spend gold to gain bonus stats for the level.

![Screenshot_2](https://github.com/user-attachments/assets/5dd38790-a963-46ba-a4a1-456ac09f7c66)

<blockquote>
<b>Engine used :</b>  Unity<br>
<b>Team size :</b> 2 <br>
<b>Project duration :</b> 6 months<br>
<b>Tasks :</b> Procedural map generation 
</blockquote>

## >> Rodent <<

> Try the game [here](https://sobriket.itch.io/rodent)

You lived your whole life as a rat lab. But now, this is over ! With the help of Volt, the small rodent, you will escape and have your revenge.
The little mouse will finally bite...

In this game, I implemented 2D physics, including basic OBB and AABB collisions and 2D raycasts. 
I also developed basic AI for the enemies, who roam between points, detect you if you’re in sight, and then chase the player. 
Finally, I designed the boss of the game, Gonk. 
He has two types of attacks:

- First, he can smash the ground to summon spikes. 
- Second, he tries to hit the player with a giant red beam.

 Gonk has a shield bar and a health bar. When you manage to reduce his shield to zero, he kneels down, allowing the player to hit him from behind.
 
![CA_7EF](https://github.com/user-attachments/assets/5e9db41a-44fe-4d61-b9d4-f01dc66e4f50)

<blockquote>

<b>Engine used :</b>  SFML<br>
<b>Team size :</b> 9 <br>
<b>Project duration :</b> 5 months<br>
<b>Tasks :</b> Game Physics,enemies and Boss AI
</blockquote>
<!--
**Sobriket/Sobriket** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
