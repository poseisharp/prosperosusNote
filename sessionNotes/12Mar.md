# Overhaul
- Game template [X]

# Enemies
- Set up a better Ai set-up
- Rethink the base enemy class <- Currently Doing
	- Patrol Behavior
	- Movement Steerings
	- Incorporate State Machine with AI [X]
	- Target and target priority [X]
	- Agro range [X]
	- Spawner
	- Standarized Projectile
	- Rework movement
	- Add buff / modifier system to the enemy too <- []
	- Add extra attributes
	- Ai will no longer be an inherited scene but will be a unique scene to for each enemy

- Polish Fromb
- Skacid
- Slime

# Character
- Nom's second skill 
- Emu's after casing animation
- Better attack propagation

# Looms
- Reconfigure Sword
- Cum splatter on Cum Stained Sword

# Scenes
- Fix the starting train scene


# Problem with the active attribute
- Trigger the tick before getting the attr [x]

# Game
- Add some juices
- Technical Doc

# Modifier 
- Visual queues on modifier?
- Should debuff and buff become one as a modifier Or should they have different class????
	- Probably make a modifier class instead with a type ENUM for buff and debuff
- Reduce bonus hp of excited or rather don't allow hp to exceed max_hp
