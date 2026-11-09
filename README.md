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

## Log 2
I've been going through a lot of struggles as of late with player movement. I've encountered one primary issue as of late.

Low gravity. This is primarily caused by the code I've been using for the player's horizontal movement. Which led to the vertical speed and therefore effected gravity.

## Log 3

I decided to completely rewrite the player script. Instead of using the VLE's implementation, used another video's.
This completely eliminated the low gravity. This also allowed for a far simpler implementation of jumping.

I've got to implement ground detection for the player.

After that I will be finished with the player character alongside the first component.
