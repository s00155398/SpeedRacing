# Speed Racing

## Introduction

In this project my aim was to create a fast paced race against the clock game in the same vein as the Swoop racing mini-games
in the Star wars games KOTOR and KOTOR 2. I chose this idea partly because of my nostalgia of said games but also as a personal
challenge for myself.

## Gameplay

The core gameplay of this project gives the player the goal of first attempting to beat the par time of each course and then beating
their best possible time. To achieve this the player must navigate each course in a fast and effecient manner, hitting speed boosting
pads, avoiding rocks and clearing vast pits. To do this, the player controls a racing speeder that can achieve quite high gears if
it gets to its maximum gear.

### Features

#### Gear-Changing System

This feature operates within the speeder to track the speed of the vehicle and prompt the player when they have reached suffecient speed
to change up a gear. In doing so, the acceleration and top speed of the speeder is increased allowing the player to complete the course
in a shorter time. This is done by tracking the velocity of the speeder and through the use of three booleans(first , second and third)
These booleans are set and unset as the velocity is checked to be within a certain range each time the player inputs and if they are 
within that range when the player inputs to change gear then the gear will change up to the next highest.

 The Speeder itself also features dynamic engine audio whereby depending on the velocity of the Speeder the audio outputted by its engine
 will change accordingly.

#### Save System

This was needed to keep track of the players top time, so that the next time the player opens the game they will have their fastest time
on each particular course displayed if that time was faster than the par time of the particular course. I managed this by creating a collision
volume named race end which would be placed at the end of the course(duh), once the player collided with this volume the current time would
be compared against the par if the par had not been beaten yet. If the player has beaten the par for the first time the race time would then be 
saved and stored to be compared against the players future times for them to beat. This new time would then be displayed on the screen at the race
start. This allows the player to have a scaling challenge as once they beat the par time, they can improve and work to beat their best time over
and over again.

#### Course Design

When I was designing the courses, I wanted to keep the fast paced flowing feel of the Mini Games in KOTOR 1 & 2. To do this, I made use of the 
rocks and environmental obstacles along with the speed boosters to create this style where the player will have to weave throught he obstacles
to avoid being slowed down or trapped whilst also hitting the booster pads to increase their overall speed. This involves alot of tight spaces
and jumps where the player must keep an eye ahead to see the spaces inbetween that lead to the boosters. To show the layout of the courses I have 
included annotated maps of them to view.


#### Art Style

I inclined towards this style of low polygonal because of my personal skill level in regards to art, I am no artist by anymeans but I am happy
with the outcome as it all fits and nothing sticks out or breaks the theme.

#### Landscape

To create the landscape I used the landscape tool within Unreal, Textures featured are sourced from Unreal Engine Starter content.

#### Models

The model for the Speeder was created by me using a swoop racer as a reference. The rock model was sourced from Unreal Engine Starter content.

##### My Model

##### Reference Material

#### Audio

All audio was sourced from this video .[here](https://www.youtube.com/watch?v=7NxJ7sKeKvM)

#### Thoughts

This project was selected as said before on the notions of Nostalgia and I find this to be a particularly good motivation, To see if
you can replicate or emulate a past experience of a found memory and develop new skills in doing so. I enjoyed this project as a result
of these factors and I would like to revist this project once I have attained better moddeling and texturing skills aswell as better skills
in general.
