# Comprehensive Text-Based Adventure Game with PDA Validation

This project blends the thrill of exploration with the precision of formal language theory, introducing a robust validation system based on Pushdown Automata (PDA) and a Custom List Automata.

## Theoretical Foundation

### Pushdown Automata (PDA)

In this game, the PDA serves as the backbone for command validation, ensuring that player actions adhere to a meticulously defined grammar, providing a controlled and structured gaming experience. These theoretical constructs, extending Finite State Machines, introduce a stack-based approach that enables the recognition of context-free languages. 

### CFG to PDA Conversion

The game engine dynamically converts a Context-Free Grammar (CFG) into a Pushdown Automata (PDA). This conversion process, deeply rooted in formal language theory, establishes a structured and theoretically grounded framework for command validation. The CFG, which defines the syntax rules of the game language, is seamlessly translated into a PDA, enforcing these rules throughout gameplay.

### Custom List Automata

Elevating the validation process, a Custom List Automata is introduced. This specialized Automata extends traditional PDA capabilities to handle dynamic lists such as inventories and sets of game locations. The Custom List Automata efficiently manages the evolving states of these lists, ensuring that player interactions align with the game's logic, introducing an extra layer of complexity and adaptability to the gaming environment.

## Features

### Room Exploration

Embark on a captivating journey through a diverse array of rooms, each presenting unique challenges and opportunities for discovery. The PDA validation ensures that your movements are not only thrilling but also conform to the specified rules, adding an extra layer of depth to the gaming experience.

### Inventory Management

Immerse yourself in the intricacies of inventory management. Collect and strategically utilize items to progress through the game. The PDA dynamically adjusts its validation criteria based on the changing state of your inventory, ensuring that interactions with items are contextually relevant and adhere to the game's grammar.

### Custom List Interactions

Experience the innovation of Custom List Automata as the game seamlessly manages dynamic lists like inventory and room history. This feature adds a new level of complexity to PDA validation, enabling the game to account for the dynamic nature of these lists and providing a more immersive and adaptive gaming environment.

### Grammar-Driven Gameplay

Engage in gameplay that is fundamentally driven by grammatical rules. Each command you enter is not merely an action but a statement in a formal language. The PDA ensures that your inputs are not only entertaining but also adhere to the syntactical structure defined by the game's grammar.

## How to Play

1. Clone the repository to your local machine.
2. Run the Python script to initiate the game.
3. Enter commands such as "go [room]," "look," "inventory," "take [item]," and "drop [item]" to interact with the game world.
