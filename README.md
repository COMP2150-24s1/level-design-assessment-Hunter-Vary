[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Hunter Vary
### Student number: 46645713 

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience
### 1.1. Discovery
My level approaches discovery by slowly exposing the player to new gameplay elements in order to facilitate learning and develop a sense of understanding of the game’s core mechanics. This clearly demonstrated in the way weapons pickups are introduced. When the player finds the staff weapon in section one they are met with a hallway. This hallway serves as a soft tutorial, introducing the main mechanics of the staff. It features a chomper which the player can now defeat with their new weapon, as well as a breakable wall which the level design of the encounter guides the player to. Because the wall is paired with the monster the player can infer the staff is the solution as well, immediately establishing mechanically what the staff is used for. The gun is introduced in a similar way where progression is blocked by a gate, with a switch in the wall. The player has no means of accessing the switch, but when travelling to the other side of the hallway and picking up the gun the player will experiment and test the gun on the switch which will open the gate and teach the player the mechanics of the gun.
![Weapon Pickup Encounters](DocImages/weaponpickups.png)

### 1.2. Drama
In the first section of the level there is an encounter where the player must fall down a one-way drop. As the player approaches the drop they see the first enemies (two chompers) they will encounter, only they are trapped above by a gate. This builds tension as it foreshadows their  involvement in the level, however the player may find some relief that they are trapped and unable to harm the player The geometry of the level forces the player to land on a pressure plate, thus activating the gate and causing the chompers to drop. This dramatically ups the intensity as the player now, in an unfamiliar area, having to make quick decisions under pressure. The player currently has no means of dealing with the chompers making them even more of a threat. Shortly after the chompers drop, a box drops on the other side of the level. This gives the player a clear goal in the disarray and is their key to escaping, creating a sense of relief in the tension. From here they must push the box to the other side while being pursued, from there they make their jump to safety. This is an example of my broader approach to drama in the level, by managing the intensity curve of each encounter to set the bar of tension with suspense, only to suddenly escalate it I create a memorable sensation of pressure which is relieved by the player’s own actions, creating a satisfying sense of drama.

![Chomper Chase Encounter](DocImages/chomperchase.PNG)
![Chomper Chase Encounter Intensity Curve](DocImages/intensitycurve.png)
### 1.3. Challenge
Challenge is presented in the level through platforming, enemies, and puzzle solving. In the first section of the level the player is introduced to spikes through a tower they must climb, where each floor of the tower requires precise jumps in order to not get damaged by the spikes. How this encounter manages difficulty is by starting easy and then increasing the challenge the further the player progresses through the encounter, building up the player’s skill in the process, and not blindsiding them with a challenge too difficult, ultimately retaining a sense of flow. The same approach is taken with enemies. Once the player picks up the staff and is able to handle enemies they are faced with a lone chomper, a relatively easy encounter, setting the bar for what its like to fight enemies. As the player progresses the quantity of chompers distributed in encounters increases to continuously raise this bar alongside the player’s skill growth. The third section of the level puts all of the player’s acquired skills to the test where the player will have to solve a large puzzle, fully utilising the platforming, combat, and problem-solving experience they have gained over the course of the level. This section of the level is designed to offer a satisfying sense of challenge where the difficulty curve is measured by the player’s own skill.
![Spike Tower](DocImages/spiketower.PNG)
### 1.4. Exploration
The starting area where the player spawns act as a hub where the player can access all sections of the map, meaning they will have to pass through multiple times. The intention of this design is to create a familiar sense of space by reinforcing the location of these paths even though the player may not have the means to access it at that time. This is to prevent the player getting confused on where they can go and creates a reliable hub area that helps ground the player’s understanding of space in the level. 
![Spawn Paths](DocImages/spawn.png)
In the third section of the level, a large emphasis is placed on player autonomy and non-linearity. Upon reaching the start of section three the player has the freedom to travel and explore three different paths. The interconnected level design makes it so the paths blend together at certain points, meaning the player will not have to retread any large portion of the level and creates a sense of flow. This is especially important because the section itself acts as a big puzzle where the player needs to drop boxes onto acid in order to progress, and needing to backtrack may create confusion and deprive the feeling of progress. Depending on the path the player chooses they will encounter different challenges, so it is up to the player how they ultimately approach the level.
![Section 3 Puzzle Paths](DocImages/section3puzzle.png)

## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.1. Acid

### 2.2. Checkpoints

### 2.3. Chompers

### 2.4. Health Pickups

### 2.5. Keys

### 2.6. Moving Platforms

### 2.7. Passthrough Platforms

### 2.8. Spikes

### 2.9. Spitters

### 2.10. Weapon Pickup (Gun)

### 2.11. Weapon Pickup (Staff)

## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram
![Molecule Diagram](DocImages/moleculediagram.png)
### 3.2. Level Map – Section 1
![Annotated Level Map 1](DocImages/levelmapsection1.png)
![Player Path 1](DocImages/levelmapsection1Edit.png)
### 3.3.	Level Map – Section 2
![Annotated Level Map 2](DocImages/levelmapsection2.png)
![Player Path 2](DocImages/levelmapsection2Edit.png)
### 3.4.	Level Map – Section 3
![Annotated Level Map 3](DocImages/levelmapsection3.png)
![Player Path 3](DocImages/levelmapsection3Edit.png)
## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.

## Generative AI Use Acknowledgement

Use the below table to indicate any Generative AI or writing assistance tools used in creating your document. Please be honest and thorough in your reporting, as this will allow us to give you the marks you have earnt. Place any drafts or other evidence inside this repository. This form and related evidence do not count to your word count.
An example has been included. Please replace this with any actual tools, and add more as necessary.


### Tool Used: ChatGPT
**Nature of Use** Finding relevant design theory.

**Evidence Attached?** Screenshot of ChatGPT conversation included in the folder "GenAI" in this repo.

**Additional Notes:** I used ChatGPT to try and find some more relevant design theory that I could apply to my game. After googling them, however, I found most of them were inaccurate, and some didn't exist. One theory mentioned, however, was useful, and I've incorporated it into my work.

### Tool Used: Example
**Nature of Use** Example Text

**Evidence Attached?** Example Text

**Additional Notes:** Example Text


