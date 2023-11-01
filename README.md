#### Creative Crit vibes

I've been working with Amrit and Richie to produce an animated background to the header of the new Marlowe website. The Marlowe branding is all about these cubes / building blocks, so the brief was to do something that looked cool but didn't pull too much focus from the actual website content.

I tried a bunch of different ideas with code, which consisted of a uniform grid of cubes that moved in a gentle sine wave. The code would apply a random phase of the sinewave to each cube to give it a sort of random feel.

I tried a bunch of different materials and effects for the cubes. We quite liked the glossy black material but found it might steal focus from the text that would be sitting over it. 

After a few iterations, we decided that if we went down the route of making the animation with code then we would be a bit limited in terms of performance. In order to make it look awesome, we'd need to add in effects such as soft shadows, ambient occlusion and depth of field. While this is all very possible with code, it does add a significant performance overhead, which I thought was overkill for a non-interactive animation.

So I decided to use a 3D graphics package called Blender to simulate the animated cubes and render out a looping MP4 video that we could use as the header background.

Blender is awesome because you can be very specific in how your simulation looks with things like lighting, materials, and post-processing effects, and the rendering process actually simulates beams of light interacting with the materials to create a very realistic image. After a few rounds of iteration and fedback we settled on a matte material so eliminate any bright reflections.

<video src="dark.mp4"></video>

<video src="light.mp4"></video>

Here are some examples of some of the test-renders:

![bees-and-wasps](bees-and-wasps.png)

![entirely-unnecessary-chromatic-abberation](entirely-unnecessary-chromatic-abberation.png)

![marlow-dark-matte-1](marlow-dark-matte-1.png)

![marlow-dark-matte-2](marlow-dark-matte-2.png)

![marlow-dark-matte-3](marlow-dark-matte-3.png)

![marlow-dark-matte-4](marlow-dark-matte-4.png)

![marlow-dark-matte-5](marlow-dark-matte-5.png)

![marlow-light](marlow-light.png)

![marlowe-dark-matte-6](marlowe-dark-matte-6.png)

![octane-dark-1](octane-dark-1.png)

![octane-dark-2](octane-dark-2.png)
>>>>>>> ce4729c (Initial commit)
