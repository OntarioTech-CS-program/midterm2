# Make-up Midterm Assignment


## Reflection Shader
![screenshot](reflection.png)

This shader allows an object to reflect a cubemap, and unlike the one in class, it also has adjustable metallic and roughness properties. This allows the reflecting object to appear even more like a shiny, reflective surface. This shader is great for the reflective armour that the battletoads wear, and the color changing property is perfect as well, since it will allow each player to have a different armor color when playing local co-op. The lighting from the lit shadergraph improves the look of this shader greatly.

## Tiling Shader
![screenshot](lava.png)

This lava shader has a scrolling noise texture, and also has a vertical vertex offset based on the noise texture. The scrolling noise offsets create an effect that makes the lava look like it's flowing and waving, just like in the game battletoads. The noise texture also looks a lot like the surface of lava, especially when it's multiplied by an orange color. Combined, these turn a simple plane into something that looks like real lava.

## Multiple UVs shader
![screenshot](fire.png)

This shader combines two noise textures that are sampled with two sets of scrolling UVs with different time scales. Not only is each noise texture at a different time scale, but they're also sampled at different noise scales, creating even more depth in this layered effect. The depth that this gives makes the shader appear much more like a real flickering flame.
