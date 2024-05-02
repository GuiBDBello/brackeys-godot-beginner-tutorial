# Brackeys Godot Beginner Tutorial

## Licensing

- CC0: Completely free to use with no requirement to credit.

## Nodes

- To make anything in Godot we use Nodes.
- Nodes are the fundamental building blocks of your game.
- Making a game in Godot is combining and extending Nodes to get the result we're looking for. 

## Scenes

- Allow us to bundle together Nodes into reusable packages.
- Nesting: Putting Scenes inside of other Scenes.
- If you update the Scene, it automatically updates everywhere that Scene is being used.
- Scene Tree: All the Nodes and Scenes in our game resemble a tree-like structure. The Node at the beginning of the tree is called "Root".

## Godot

- F5: Run Project.
- F8: Stop Running Project.
- "+" sign on top: Add a new scene.
- Ctrl + A or click "+" sign on top-left: Add Child Node.
- Ctrl + Shift + F11: Toggle distraction-free mode.
- F: Focus. Center selected object on screen.
- Q: Select Tool.
- W: Move Tool.
- Hold Shift while dragging an object: Snap the object to an axis.
- Hold Ctrl while releasing a Node into a script to create a reference for that Node.

### AnimationPlayer

- New animation;
- Add keyframe;
- Change timeline;
- Change Node state;
- Add keyframe;
- Select loop/ping-pong;
- Select autoplay.

### GDScript

- `func _ready()`: Called when the Node enters the SceneTree.
- `func _process(delta)`: Called every frame. `delta` is the elapsed time since the previous frame.

### Signal

- Signals allow us to trigger code based in events that happen in our game.
- All Signals are displayed at the upper right "Node" tab.
- To add, double-click a Signal and select "Connect". Then, at the green icon at the left of the line number, select the Node that triggers that Signal.
