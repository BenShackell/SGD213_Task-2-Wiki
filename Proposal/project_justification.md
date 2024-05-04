# Justification
[//]: # (This section is an example of justifying your design and development decisions.)

## Overview

### Brief
[//]: # (What was the client's brief?)
Hello! I’m looking for a simple 2D/3D sidescroller platformer game (2D sprites or 3D models - Must be sidescrolling). I want to focus on the art and I’m not so good with programming. I would need the game to be laid out in a way I could make levels, and enemies, control a player, and create pickups.

### Communication
* Would you like to give damage? and how will the player do this? 

I'm happy with the player not being able to deal damage to enemies, though if you have the time, you could add an ability to do so. Jumping on top of them, like Mario games would be suitable for the genre.

* How many enemies will you need? Will they give different amounts of damage to the player?

I will be able to configure enemy damage amounts in Editor, so a generic setup for enemies to deal damage upon contact with the player will be sufficient. 

* Do you have any artwork available for testing purposes?

I am not able to provide testing art at this time.

* Are you ok for us to place in some until you can replace with your own? 

feel free to use placeholder art in the meantime.

* Will you need sound?

No sound is required.

*We have been calling your game Kenny the Kid, what did you want to call your game?

I also have not decided on the name, so placeholder title is perfectly fine!

*What is the age range?

Round 25-34 years old

*How fast should the player/enemies be?

Not sure, this will need to be play tested


---

## Project Understanding

### Requirements
[//]: # (What are the requirements of the finished project?)
•	Needs the product 31 May 2024.
•	Gameplay should be fast paced.
•	Should be quick to restart.
•	Feedback is a major point.
•	People should be drawn to it by its appearance.
•	Needs a catchy name (Kenny the Kid) - place holder name.
•	Programming completed to allow client to easily add artwork and design the level.
•	Programming will allow client to change the amount of damage the enemies give.


### Expectations
[//]: # (What are the client's expectations?)
•	Project delivered on time.
•	Weekly updates on progress
•	Communication with the client when design issues encountered.
•	Quality transparent project management (Olexiy - Mimtendo)
•	Does not require audio.
•	Does not require high quality art - use place holder art.
•	Can use basic geometry.
•	Should still look nice using colour palettes.
•	Walk
•	Run
•	Jump
•	Be damaged - Damage will be on collision - ability to change damage amount in editor.
•	Give damage - by jumping on top (only if there is time not required)
•	Enemies
•	Pickups.


### Assumptions
[//]: # (What are you assuming based on client responses)
•	UI art does not need to be high quality, will just use basic Unity UI sprites.
•	Programming the player, levels and enemies will be important, but since we shouldn't spend time on art, will use standard asset or free assets - PLACE HOLDER
•	Client would like Crow studio to implement all programming in a way that they can add art easily and make damage amount changes in the editor.
•	In the expectations we have listed what the client has requested, if the team have time, we could add in more movement functions to allow the game to function like the Mario games to help the client achieve the end result they need.

---
## Risks

### Risks
[//]: # (What are the risks of this project)
* Unity and C# are excellent prototyping tools, but working quickly often means less than perfect code.
* Project may not be fit for use in further development.
* Bugs may be present in prototype due to the short turn-around.
* Working quickly is error prone.
* Deadline - Time management - staff becoming sick, client needing more programming added. The team not creating the what the client has requested. Or confusion with the request. Client changing the required.
* deliverables. The team will do their best to keep lines of communication open, we will be checking off each requested deliverable.
* Legal or copyright issues - ensuring any assets provided are free for use and are acceptable under fair use legality and maintaining documentation of any third-party assets used to manage any possible copyright issues.
* Damaged or faulty equipment - Computer crashing or malfunction slowing progress. The team will use GitHub to save work progress and back up files often.
* Technical Issues - Communication between the client and the team ensuring we are maximising work output. If issues do come up the client and team can resolve asap via email, discord, or Trello.


---

## Constraints

### Constraints
[//]: # (What are the constraints of this project)
* We have a tight timeframe, so we will need to make fast decisions, which may be less than perfect.
* Time constraints - Time needs to be managed correctly so we can meet all the needs of our clients’ requests. The deadline for this project is Friday 31st of May 2024.
* Budget constraints - can affect the scope and the quality of the game. The agreement between the team and client for what deliverables and in amount of time for $ quoted and agreed price.
* Technical limitations - Scope creep - adding in features that were not in the original agreement. Lack of funding - this can restrict the budget for publishing and polishing the game.
* Technical Challenges - coding, debugging, ensuring cross platform compatibility, making sure the client is happy with the performance.
* Platform limitations - Different platforms have varying technical specification requirements.


---

## Justification
Rigidbody directly as an engine.
We have chosen to use the Rigidbody for this game for the client to be able to inset their artwork and easiley make changes. We will have scripts laid out so it is easy to read.
-It uses the Rigidbody directly as an engine
-e. the playercontroller script directly touches the Rigidbody component, instead of going via an engine component
