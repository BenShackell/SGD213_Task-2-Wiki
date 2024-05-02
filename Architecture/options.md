# Architecture Options

**Rigidbody directly as an engine.**

**Components that implement IEngine**

You should consider 3 different architecture options in here.

You **don't** need UML in here.

You should also justify your thinking.

Hot tip: use our text book for guidance.

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

## Inheritance from other objects?
Fill with information
