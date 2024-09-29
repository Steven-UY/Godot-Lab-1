# Godot-Lab-1

- [ ] Create main scene
- [ ] 2 Different Sprites
- [ ] Several instances of another scene
- [ ] Create a github repository with the godot project inside
and a README file where you describe the project and write out
any quetions or things you learned along the way

### Scenes

In Godot a game is a **tree of nodes** that you group together into
**scenes**. Essentially you break down your game into reusable scenes.
Scenes can be characters, weapons a menu, a level. Think of them kind 
of like a class. What a scene can be is very flexible.

#### Scene Nesting

You are able to nest scenes e.g you can put a character in a level
and drag and drop a scene as a child of it

![Alt text](https://docs.godotengine.org/en/stable/_images/key_concepts_scene_example.webp)

As you can see the elements nested in have the scene icon which indicates they are
scenes. 

### Nodes

Nodes are the game's smallest building blocks that make up a scene.
For example if we have a character it can be constructed out of many
nodes as demonstrated here. 

![Alt text](https://docs.godotengine.org/en/stable/_images/key_concepts_character_nodes.webp)

The character is made of the nodes **CharacterBody2D** node named "Player", a **Camera2D**, 
**Sprite2D**, and a **CollisionShape2D**.

Godot provides a set of base nodes to work with 2D,3D, user interface.
These will be used for most things.

### The Scene Tree

The scene tree is where all the game's scenes are organized. 

### Signals

Nodes emit signals when some events occur. Allows you to automatically
have nodes communicate without hardcoding it. 