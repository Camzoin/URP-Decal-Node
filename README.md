# URP-Decal-Node
A node for Shader Graph that allows you to create custom decals.

## How to use
MAKE SURE you have the depth texture enabled in your URP asset.

Create a new Unlit Graph.
Click the cog on the master node, and set:\
	Surface -> Transparent.\
	Blend -> to the type of decal you'd like.

Add the 'Decal Node' node.

From here it's up to your creativity to create whatever decal you'd like.\
Refer to the examples to see how each of the blend modes work.

Once you've created your material, apply it to a default cube object.\
Make sure you turn off 'Cast Shadows' on the Mesh Renderer and remove the Box Collider component. 