# Game-Engines-Quiz

# Role: Artist

# Explanation
What I aim to do is that I want to remove shadows of a gameobject in order to achieve a certain aesthetic , and the solution to that is to set the bool of Recieving Shadows to false.

The code is basically an exported function that returns a bool. Then within unity, I created a script that basically imports the function through the dll. The script prompts you to get a game object(which is the game object) and then it accesses its mesh renderer to change the bool of the RecieveShadow variable.

Changing [DllImport("Plugin")] in the PluginScript to [DllImport("RestorePlugin")] will restore things to default.

# Live Demo: 
https://youtu.be/66FR3UIQ9yw
