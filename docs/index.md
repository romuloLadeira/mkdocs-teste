# Documentação da engine Last Hope

## Descrição 
A “Last Hope” é uma engine de adventures (3d, 2d, de texto) com um sistema de diálogos, inventário, gestão de objetos e salas extremamente flexível e customizável

## Classes degerenciamento

### Adventure
Class that handles the room loading and all arround.
### Answer Handler
Class that handles the available answers for the player while in a chat.
### Dialog Engine
### Input Interaction
Interpretador de ações
### Inventory engine
### World
Autoloload script. The brains of the adventure. All the relevant nodes that controll the game must be initialized here
### World Creatures
Class that shows and handles all the creatures in the current room
### World Objects
 Class that shows and handle all the objects in the current room
### WorldPlaces
Class that shows and handles all the exits in the room

## Classes Genéricas
### LH3DGenericAreaEvent
### LH3DObject
### LH3DPlayer
### LHAction
### LHAnswer
### LHAtribute
### LHBoxOfAction
### LHChat
### LHContainer
### LHCreature
### LHCutscene
### LHDescriptionBox
### LHDialogObject
### LHDialogTopic
### LHDoor
### LHExit
### LHFadeInOut
### LHMap
### LHObject
### LHPlayerEye
### LHRoom
### LHTimedEvent

