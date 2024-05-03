# Chosen Architecture

![Crow Studio UML](https://github.com/BenShackell/SGD213_Task-2-Wiki/assets/132724681/a97c7c3d-659d-4432-96f0-32e6dc3c513b)

## Justification
Rigidbody directly as an engine.

We have chosen to use the Rigidbody for this game for the client to be able to inset their artwork and easiley make changes. We will have scripts laid out so it is easy to read. 

-It uses the Rigidbody directly as an engine

-e. the playercontroller script directly touches the Rigidbody component, instead of going via an engine component

-It has a weapon component (stored as type BaseWeapon)

-The weapon component is removed/replaced when a new weapon is needed

-Each weapon inherits from BaseWeapon
