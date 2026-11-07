# Learning-Journal

## Log 1
As of writing this. I've currently got a very basic character controller working. It currently has basic movement alongside a jump.
I need to implement the ground checks to ensure you cannot jump in the air.

The main struggles writing the script for the player character were primarily due to me wanting to find a tutorial that kept the initial monobehavior structure.
This is primarily for two main reasons.

1. Its a simple structure to work with and much easier to understand.
2. I would like to avoid bloating the character script especially when adding extra functionality or adding compatability with other components.

I also need to figure out how to disable the capsule's ability to rotate as it currently begins shifting and falling onto its side at the moment.

Edit: Rotation can be frozen within Rigid body's constraints.
