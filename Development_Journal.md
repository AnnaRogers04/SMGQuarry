# Client Brief - The Quarry

Gameplay design and programming

Anna Rogers

2315276

## Brief

2. Will video games inevitably mature into a new narrative artform driven by their storytelling ambitions? Consider different narrative structures deployed by game designers and the player’s role in experiencing and constructing game stories. (asking if video games in themselves will be considered their own art form driven by their choices in design story telling narrative)


## Project Outline
The game I've chosen to base this project off of is The Quarry, a cinematic third person game experience that relies on ambiance and scenes to proivide the player with an immserive experience. I wanted to create a playable scene that felt like The Quarry by impletemting a similar interaction system the orignal game and a similar UI system to try learn something new and push my bounderies outside my comfort zone. I will do this by researching and learning blueprints for interaction systems and adjusting them to suit the style of gameplay wanted.

## Research

### Methodology  

The sources I've provided have influenced how I approach the narrative of my game. With it being based off of a cinematic game the narrative is mainly shown in audio and interaction with the level. Each bit of interaction provides a further detail to the game, unraveling a story thats intended to be seen.

### Game and Academic sources 
#### Little Hope 
Little Hope is a cinematic horror game by supermassive games. The theme of a more visual gameplay is very similar to the quarry as it very much focuses on the visual and storytelling aspect of the game. The game is heavily influenced by the Salem witch trials and the Andover witch trials of the 17th century. In particular the events of the 1692 witch trials in colonial America. This game reminds me of the following quote:

- "From the opening cut-scene, gameplay is invested with a strong, even overwhelming, sense of narrative. Reduced to their basic formal or ludological bones, these tests in maze navigation, puzzle solution, evasion and target practise, are devoid of either horror or any notable sense of survival. It is through aspects of narrative, representation, and characterization that gameplay acquires the "edge, meaning and motivation."

This quote presents the idea that narrative is crucial and is well thought upon, without it the game is just a series of challenges. It shows us that the story provides emotional weight and helps us to understand if the game is a survival or horror etc. This relates to my current project because narrative is a huge part of the game we are making. Without the right narrative and world creation the game we make could be misunderstood.
#### The Quarry 
The Quarry is also a cinematic game by Supermassive games. Its also very visual and audio based like Little Hope. This game is more supernatural, having the setting based on the night of a full moon where werewolves hunt down a group of summer camp assistants. The goal is to lift the curse by killing the white werewofl and keeping all members alive. This game reminds me of the following quotes:

- " Alone in the Dark involves a range of visual and audio iconography self-consciously drawn from horror narrative culture. Survival entails a narrative situation including existance in the form of a central protagonist("character"), adversaries("horrific monsters"), location("enclosed places"); and events, the process of "solving puzzles" and "destroying"- which more problematically implies sucessful player interaction."
- "Game play takes place within a representational universe, filled with depictions of objects, interactions, and ideas out of which the player makes meaning. It is up to the player to piece these together as they try to interpret the varying levels of complexity embeded within the game."

The first quote suggests the idea of a protagonist, adversaries, location and puzzles being the core elements in which a survival horror game can be made. Using traditional horror signs and sounds can create further the image of a survival game, making it more immersive to the player.
The second quote further explains that the world you are playing in isnt random and is in fact very thought through and made to show/represent something. This design enourages the player to explore. They have the choice to learn more and piece the game and the story together or leave the game up to their interpretation eniterly. In my game the world itself has been made to encourage exploration, as exploration progresses the story and the level your playing, while using the narrative of a character, danger and confined space I hace tried to recreate an isolated ambiant experience.


### Documentation Sources  
<iframe width="560" height="315" src="https://www.youtube.com/embed/H58y1Fp77_w?si=6oQG_i1nNOX5JJVa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

I used this video to make my quick-time event system more immersive and interactive. Since *The Quarry* is a cinematic game with minimal interactions, adding a visual quick-time event enhanced the experience.  
Quick-time events were new to me, and this source was very good in expanding my knowledge of nodes. However, I found it challenging to follow since it only provided notes and no audio. To overcome this, I looked to the designers in my group for help, which greatly improved my understanding and allowed me to implement the system successfully and efficiently. Additionally, my peers assisted me in troubleshooting and fixing issues when I encountered difficulties.

## Implementation

### Process
<iframe src="https://blueprintue.com/render/mey5o30d/" scrolling="no" allowfullscreen></iframe>
<iframe src="https://blueprintue.com/render/wqfjnmuz/" scrolling="no" allowfullscreen></iframe>
<iframe src="https://blueprintue.com/render/ou4bgjtp/" scrolling="no" allowfullscreen></iframe>
<iframe src="https://blueprintue.com/render/wtamd7af/" scrolling="no" allowfullscreen></iframe>
<iframe src="https://blueprintue.com/render/5iiwqmyw/" scrolling="no" allowfullscreen></iframe>

### New Approaches  
For this game i thought raycasting would be the best for the interaction. However after testing the raycasting alongside begin overlap I decided a trigger box was better for thos senario. It was intresting to learn as implementing a trigger box is alot more visual then in unity.

### Testing
When testing the game I came to the conclusion that the ui system, walk keys and puzzle elements (more complex) need to be more interactive. Some screens were timed and you couldnt exit until the timer had finished. For people that picked up on what they needed to do quickly this took away from the experience. Making puzzle hints and a bigger game area. this feedback was very informative for me to perfect this game and has pushed me outside my comfort zone to overcome this i used a varity of sources from teatcher  peer support to videos to inform and improve my work. responding to this feedback i discussed to my group the changes that needed to be make and delegated roles to each menber to allow everyone to have a direction and upon doing this weve been able to correct and firther improve the game to make the exsperiance more imersive and allow the player a greater exsperiance 

### Technical Difficulties
During the game progress there were several technical issues the mains ones being the Password system and the QTE (quick time event) system. While the password was functional before the game test you could put in any code as long as you used all 4 numbers and it would work, this was a majour flaw as well as not being able to back out of the screen. These were fixed and i have provided documentation sources which i looked at while trying to getb= this to work.
The QTE system had an issue when trasffering to main which gliched some variables, I had to go through and recheck the variables and replace the broken ones to fix this issue.

## Outcomes (remaining word count) 

- [itchlink]
- [gitlink] https://github.com/AnnaRogers04/SMGQuarry
- [youtubelink]


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
How do I press the buttons in the correct order using a variable? - Programming & Scripting / Blueprint - Epic Developer Community Forums (s.d.) At: https://forums.unrealengine.com/t/how-do-i-press-the-buttons-in-the-correct-order-using-a-variable/488873 (Accessed  01/04/2025).
Basic QTE System | Part 1 - Unreal Engine 4 Tutorial (2021) At: https://www.youtube.com/watch?v=teoJUExYjVI (Accessed  01/04/2025).
Tap Key System (QTE) in Unreal Engine 5 (Tutorial) (2022) At: https://www.youtube.com/watch?v=H58y1Fp77_w (Accessed  01/04/2025).
Kirkland, E. (s.d.) 'Storytelling in Survival Horror Video Games' In: Horror Video Games: Essays on the Fusion of Fear and Play. (s.l.): (s.n.). pp.62–78.
Sheldon, L. (s.d.) 'Character development and storytelling for games' (s.l.): (s.n.). pp.153–154.
Hoedt, M. (s.d.) 'Narrative Design and Authorship in Bloodborne' In: An Analysis of the Horror Videogame. (s.l.): (s.n.). pp.140–142.

## Declared Assets
