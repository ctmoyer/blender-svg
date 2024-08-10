# blender-svg
Exploratory repo related to stacked animated SVGs in Blender

# Initial Question
What if we used grease pencil / curves / nurbs in Blender as a proxy for SVG data in Blender?

# Dream Outcomes
- Output visualizations in Blender into slices of SVG / generic bezier format
- Output animations of these sliced SVGs in 2 ways:
  1. As a sequence of frames (like with raster images) ((This is probably just better to render with Blender's built-in rendering capabilities rather than any special hacks from me))
  2. A list of changes of the individual bezier curves' values across time (potentially with easing functions)
- **Import the "rendered" output into the browser where a special custom element can interpret the SVGs and visualize the animations to a user in the browser with no special library required-- just CSS animations!
**

I'd love for Blender to make creating animations and assets for the web more accessible, without relying on Javascript libraries to make it all work. In a perfect world, the Blender customization would not only produce these SVG images but also optionally output details on how they should animate and be presented to users based on the context found in Blender.

This may take the form of a long CSS file or something.
