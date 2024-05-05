# Architecture Options

## Rigidbody directly as an engine.
Fill this with information.

-You have a spaceship game object

-It uses the Rigidbody directly as an engine

-e. the playercontroller script directly touches the Rigidbody component, instead of going via an engine component

-It has a weapon component (stored as type BaseWeapon)

-The weapon component is removed/replaced when a new weapon is needed

-Each weapon inherits from BaseWeapon


## Components That Implement IEngine
Fill with information

-You have a spaceship game object

-It has a component that implements IEngine

-PlayerController interacts only with IEngine

-It has a WeaponManager: IWeapon

-When a new weapon is needed, you just ask the WeaponManager to equip it

## Events and Delegates

-allows for the decoupling of components

-use events and delegates to create a system where components can communicate without direct references to each other

-Can simplify debugging by providing clear points of interaction between components

-Event system is integrated with MonoBehaviour

## Justification 

However looking back, this project is for a not-as-experienced individual, so we are choosing to use the Rigidbody method. This is fairly simple and can be easily picked up if the client has any problems or wants to change some code around themselves. Not only this but Unity offers a lot of advantages when using Rigidbody, good physics simulations, collision detection, gravity and forces, integration with Unity physics, dynamic movement, interactivity and realistic animations. Although I have listed a lot of pros, we may not use them all to their maximum capabilities, again we want to keep things simple and basic in case the client wants to poke around with the code themselves. We could go in depth but that was not included in the contract so, instead of making hard-to-learn code and the client wasting hours learning what we did, we are simply making it easier for them or future use. 
