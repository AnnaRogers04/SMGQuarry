# Client Brief - The Quarry

Gameplay design and programming

Anna Rogers

2315276

## Brief Question

 2. Will video games inevitably mature into a new narrative art form driven by their storytelling ambitions? Consider different narrative structures deployed by game designers and the player’s role in experiencing and constructing game stories. 
 
 (Asking if video games in themselves will be considered their own art form driven by their choices in design story telling narrative)


## Project Outline
The game I've chosen to base this project off of is The Quarry, a cinematic third person game experience that relies on ambiance and scenes to provide the player with an immersive experience. I wanted to create a playable scene that felt like The Quarry by implementing a similar interaction system the original game and a similar UI system to try learn something new and push my boundaries outside my comfort zone. I will do this by researching and learning blueprints for interaction systems and adjusting them to suit the style of gameplay wanted.

## Research:

### Methodology  

The sources I've provided have influenced how I approach the narrative of my game. With it being based off of a cinematic game the narrative is mainly shown in audio and interaction with the level. Each bit of interaction provides a further detail to the game, unravelling a story that's intended to be seen.

### Game and Academic sources 
#### Little Hope 
Little Hope is a cinematic horror game by supermassive games. The theme of a more visual gameplay is very similar to the quarry as it very much focuses on the visual and storytelling aspect of the game. The game is heavily influenced by the Salem witch trials and the Andover witch trials of the 17th century. In particular the events of the 1692 witch trials in colonial America. This game reminds me of the following quote:

- "From the opening cut-scene, gameplay is invested with a strong, even overwhelming, sense of narrative. Reduced to their basic formal or ludological bones, these tests in maze navigation, puzzle solution, evasion and target practice, are devoid of either horror or any notable sense of survival. It is through aspects of narrative, representation, and characterization that gameplay acquires the "edge, meaning and motivation."

This quote presents the idea that narrative is crucial and is well thought upon, without it the game is just a series of challenges. It shows us that the story provides emotional weight and helps us to understand if the game is a survival or horror etc. This relates to my current project because narrative is a huge part of the game we are making. Without the right narrative and world creation the game we make could be misunderstood.
#### The Quarry 
The Quarry is also a cinematic game by Supermassive games. Its also very visual and audio based like Little Hope. This game is more supernatural, having the setting based on the night of a full moon where werewolves hunt down a group of summer camp assistants. The goal is to lift the curse by killing the white werewolf and keeping all members alive. This game reminds me of the following quotes:

- " Alone in the Dark involves a range of visual and audio iconography self-consciously drawn from horror narrative culture. Survival entails a narrative situation including existence in the form of a central protagonist("character"), adversaries("horrific monsters"), location("enclosed places"); and events, the process of "solving puzzles" and "destroying"- which more problematically implies successful player interaction."
- "Game play takes place within a representational universe, filled with depictions of objects, interactions, and ideas out of which the player makes meaning. It is up to the player to piece these together as they try to interpret the varying levels of complexity embedded within the game."

The first quote suggests the idea of a protagonist, adversaries, location and puzzles being the core elements in which a survival horror game can be made. Using traditional horror signs and sounds can create further the image of a survival game, making it more immersive to the player.
The second quote further explains that the world you are playing in isn't random and is in fact very thought through and made to show/represent something. This design encourages the player to explore. They have the choice to learn more and piece the game and the story together or leave the game up to their interpretation entirely. In my game the world itself has been made to encourage exploration, as exploration progresses the story and the level your playing, while using the narrative of a character, danger and confined space I have tried to recreate an isolated ambient experience.


### Documentation Sources  
#### Quick time
<iframe width="560" height="315" src="https://www.youtube.com/embed/H58y1Fp77_w?si=6oQG_i1nNOX5JJVa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

I used this video to make my quick-time event system more immersive and interactive. Since *The Quarry* is a cinematic game with minimal interactions, adding a visual quick-time event enhanced the experience.  
Quick-time events were new to me, and this source was very good in expanding my knowledge of nodes. However, I found it challenging to follow since it only provided notes and no audio. To overcome this, I looked to the designers in my group for help, which greatly improved my understanding and allowed me to implement the system successfully and efficiently. Additionally, my peers assisted me in troubleshooting and fixing issues when I encountered difficulties.
#### Credits
<iframe width="560" height="315" src="https://www.youtube.com/embed/LmLjLQbyq-4?si=gLKk3EvA0ewXEjlg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

I used the video provided above to make my credits scene. This tutorial was really easy to follow and explained what I needed to do really well and in depth. After making the end credits from this video I further added the background to fade to black from the game and a main menu button to appear once the credits finished running. This was a nice final touch to add and I really enjoyed being able to share all the names of people I worked with. It polished the game off well and overall I'm really happy with this.

## Implementation

### Process

For this game I knew I wanted to create a similar game system to 'The Quarry'. I looked into Quick time events and interaction systems. While there are loads of videos based on quick time events, the one I had used felt like it was the best at the time. However, in hindsight there were probably better videos out there. The video I used for my interaction system was one a designer in my group showed me based off of a dialogue system that Tutor, Liam Lacey showed how to make. This system had to be adapted to work with hot key popups. The process of making everything has been an interesting but challenging learning curve as unreal was new to me.

### Quick time event system
<iframe src="https://blueprintue.com/render/mey5o30d/" scrolling="no" allowfullscreen></iframe>
<iframe src="https://blueprintue.com/render/wqfjnmuz/" scrolling="no" allowfullscreen></iframe>
<iframe src="https://blueprintue.com/render/cipdk-x5/" scrolling="no" allowfullscreen></iframe>
<iframe src="https://blueprintue.com/render/wtamd7af/" scrolling="no" allowfullscreen></iframe> 

I found the quick time event blueprints challenging. The video that shows how to put this system together did not explain what everything was for, with some logical thinking I managed to figure out what meant what. For this chunk of blueprints I used new nodes like:
- Timelines
- Play animations
- Create widget
- The majority of the nodes on the Progress bar Blueprint

Learning how to use these nodes and how they would bring the quick time event system together was definitely a learning curve for me however, completing this event was such a relief that it helped provide further motivation to add things like the credits and provide one big push to get everything done.


![Failed_QTE](https://github.com/user-attachments/assets/965ef796-3c0c-4ce3-b4b0-1752fc6c9313)
![Passed_QTE](https://github.com/user-attachments/assets/319d86de-96d4-4eb5-b28d-8ca93f5c437f)


 Figure 1 and 2 show both the passed and failed system working, The positioning was later changed for the final product as I feel that it was too big and too central. This to me effected the flow of the game. I'm pleased I changed it.

### Interaction system


<iframe src="https://blueprintue.com/render/5iiwqmyw/" scrolling="no" allowfullscreen></iframe>

For my interaction system I followed a video by Liam Lacey on adding running dialogue into a game, while i didn't use running dialogue I was able to adapt this system to have an image of a mouse appear when an intractable is within reach. This was one of the first blueprints I created for this project, it was a great introduction to unreal. 

As shown below there was originally a raycast system that was used to interact however I decided that this would be too conflicting with everything else we needed to add so we changed it to the system with the functioning UI. This system in my opinion fits the gameplay style I wanted to create really well and was happy with the change.
![photo-collage png](https://github.com/user-attachments/assets/071ac8e0-4da0-47ca-89c4-5048079e8b74)


Figure 3 Shows the UI I created for the interaction system in tester mode and as the final product. This fits well with the game and im really happy with this.


![Raycast](https://github.com/user-attachments/assets/0c58e7f1-fda6-47fb-8683-58f531a09f2d)


Figure 4 Shows the raycast system working when we were testing blueprints, this was originally going to be the interact system until we decided that trigger boxes would work better with the camera system.
### End credits 
<iframe src="https://blueprintue.com/render/q44mhqou/" scrolling="no" allowfullscreen></iframe>
<iframe src="https://blueprintue.com/render/1di8-483/" scrolling="no" allowfullscreen></iframe>

The end credits was a very simple yet effective blueprint to add. After the quick time event I was more confident using animations and I nderstood how they worked. For instance the play animation node runs the whole animation when trigger the whole way through, this is where adding delays come in useful becau
![End credits](https://github.com/user-attachments/assets/82b5226a-10bc-4783-8261-0e7907d32dfe)

### Visuals 

![Cage progress](https://github.com/user-attachments/assets/1766238e-23f0-49a5-b36f-e449b7d99499)


Figure 5 shows the progression of the cage before textures were added, during this process assets were starting to be added to the game and the final product was starting to come to life.

![office progress 1](https://github.com/user-attachments/assets/2c2b6206-8e13-48fe-bd31-304045ba3367)
![office progress 2](https://github.com/user-attachments/assets/daeedeb9-f5c8-4767-b51d-51265685ae12)


Figure 6 and 7 shows the office when the untextured assets were added, the shape of the room is now taking place.


![FotoJet](https://github.com/user-attachments/assets/ab04b54a-16b0-41da-a8e9-fa680078aaee)


Figure 8 shows another area of the office up close. Final assets and details were added before this like the artists textures and it really pulled this section together.


![FotoJet (1)](https://github.com/user-attachments/assets/b3fa6e5c-5b44-49fc-8915-570be79f2c7c)


Figure 9 shows area of the office finished with lighting and textures, these images are final images from the gameplay itself.


![Cage fin](https://github.com/user-attachments/assets/e5838225-911f-4db4-ae78-960ef4ad5d3f)


Figure 10 shows a final image of the cell with textures, I added the assets and textures for all of the cell area and polished that off myself.

### New Approaches  
For this game I thought raycasting would be the best for the interaction. However after testing the raycasting alongside begin overlap I decided a trigger box was better for this scenario. It was interesting to learn as implementing a trigger box is a lot more visual then in unity.

### Testing
When testing the game I came to the conclusion that the UI system, walk keys and puzzle elements (more complex) need to be more interactive. Some screens were timed and you couldn't exit until the timer had finished. For people that picked up on what they needed to do quickly this took away from the experience. Making puzzle hints and a bigger game area. this feedback was very informative for me to perfect this game and has pushed me outside my comfort zone to overcome this I used a variety of sources from teacher  peer support to videos to inform and improve my work. responding to this feedback I discussed to my group the changes that needed to be make and delegated roles to each member to allow everyone to have a direction and upon doing this we've been able to correct and further improve the game to make the experience more immersive and allow the player a greater experience 

### Technical Difficulties
During the game progress there were several technical issues the mains ones being the Password system and the QTE (quick time event) system. While the password was functional before the game test you could put in any code as long as you used all 4 numbers and it would work, this was a major flaw as well as not being able to back out of the screen. These were fixed and I have provided documentation sources which I looked at while trying to get this to work.
The QTE system had an issue when transferring to main which glitched some variables, I had to go through and recheck the variables and replace the broken ones to fix this issue.

## Outcomes (remaining word count) 

- [itchlink](https://lunarlynx-games.itch.io/thequarrystudentinspired/) 
- [gitlink](https://github.com/AnnaRogers04/SMGQuarry/)
- [youtubelink](https://youtu.be/C_sLJNYTjBE?si=i-Zj6I86VqMRw1nP/)


## Reflection (Suggested Word Count 800) 

### Research Effectiveness  
- Assess the usefulness of the research conducted during the project.  
- Highlight which sources (games, academic, documentation) had the most significant impact on your work and explain why.  
- Identify any research gaps or areas where additional information could have improved your project outcomes.

### Positive Analysis 


### Negative Analysis  
- Identify the areas of the project that did not go as planned or could have been improved.  
- Discuss challenges you faced, whether technical, creative, or time-related, and evaluate their impact on the final product.  
- Reflect on any mistakes or missteps and what you learned from them.

### Next Time
- Outline what you would do differently if you were to undertake a similar project again.  
- Suggest improvements to your workflow, research methods, or implementation process based on your reflections.  
- Consider any new tools, techniques, or approaches you would explore in future projects to achieve better results.

## Bibliography  
Research
- Kirkland, E. (s.d.) 'Storytelling in Survival Horror Video Games' In: Horror Video Games: Essays on the Fusion of Fear and Play. (s.l.): (s.n.). pp.62–78.
- Sheldon, L. (s.d.) 'Character development and storytelling for games' (s.l.): (s.n.). pp.153–154.
- Hoedt, M. (s.d.) 'Narrative Design and Authorship in Bloodborne' In: An Analysis of the Horror Videogame. (s.l.): (s.n.). pp.140–142.

Game sources
- How do I press the buttons in the correct order using a variable? - Programming & Scripting / -    Blueprint - Epic Developer Community Forums (s.d.) At: (https://forums.unrealengine.com/t/)
- how-do-i-press-the-buttons-in-the-correct-order-using-a-variable/488873 (Accessed  01/04/2025).-
- Basic QTE System | Part 1 - Unreal Engine 4 Tutorial (2021) At: (https://www.youtube.com/watch?v=teoJUExYjVI/) (Accessed  01/04/2025).
- Tap Key System (QTE) in Unreal Engine 5 (Tutorial) (2022) At: (https://www.youtube.com/watch?v=H58y1Fp77_w/) (Accessed  01/04/2025).
- How to Make a Credits Menu in Unreal Engine 5 (2023) At: (https://www.youtube.com/watch?v=LmLjLQbyq-4/) (Accessed  09/04/2025).

## Declared Assets

Audio - Sourced and imported by Daniel Mcpherson
- 8mm Film Camera | Royalty-free Music (s.d.) At: (https://pixabay.com/sound-effects/)8mm-film-camera-6446/ (Accessed  09/04/2025).
- Cinematic Tension - Suspenseful Thriller Music Loop | Royalty-free Music (s.d.) At: (https://pixabay.com/music/main-title-cinematic-tension-suspenseful-thriller-music-loop-297627/) (Accessed  09/04/2025).
- Deep Pass By | Royalty-free Music (s.d.) At: (https://pixabay.com/sound-effects/deep-pass-by-106962/) (Accessed  09/04/2025).
- Fire Alarm Loop by simonjeffery13 (s.d.) At: (https://freesound.org/people/simonjeffery13/sounds/792642/) (Accessed  09/04/2025).
- Geiger counter (dry) by Sanderboah (s.d.) At: (https://freesound.org/people/Sanderboah/sounds/674113/) (Accessed  09/04/2025).
- Whip | Afro Dancehall Music | Royalty-free Music (s.d.) At: (https://pixabay.com/music/beats-whip-afro-dancehall-music-110235/) (Accessed  09/04/2025).

Assets - Sourced and added by Daniel Mcpherson
- Coat Rack - Download Free 3D model by Whostea (2021) At: (https://sketchfab.com/models/72e821fc75d9473183a63d548959693b/embed?autostart=1) (Accessed  10/04/2025).
- Wire Fence and Door Set - Download Free 3D model by GameDevMoot (2024) At: (https://sketchfab.com/models/eca6ce077d1e43c9a177f278284d3735/embed?autostart=1) (Accessed  10/04/2025).
- Rusty Filing Cabinet - Download Free 3D model by Amiel Goco (@pamikoe) (2018) At: (https://sketchfab.com/models/619484b78fbe449ea5c0cdb68e8f2bd6/embed?autostart=1) (Accessed  10/04/2025).
- Desk lamp - Download Free 3D model by sergeilihandristov (2023) At: (https://sketchfab.com/models/ac5135b505694287a64b4370ea2cda8d/embed?autostart=1) (Accessed  10/04/2025).

Characters - Made by Ana Brichis, imported by Anna Rogers
- MetaHuman Creator (s.d.) At: (https://metahuman.unrealengine.com/) (Accessed  09/04/2025).
