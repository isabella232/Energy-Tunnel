# Energy Tunnel

## By @doc-code-hub

Resolution: `4250x4250`
Aspect ratio: `1:1`
Main project file: `Energy Tunnel - Swirls.xcf`
Main project file size: `1.6 GB`

![Alt text](export/Energy%20Tunnel%20-%20sm%202.png)

# How i did it

### Tunnel
- Color Circle
- Supernova generation with hue on upper layer
- Subctract blend method on the circle 
- Twick colors of both circle and supernova to get the desired pattern
- Merge the layers
- Duplicate many layers as the number of slice we want
- Set 2 guides (image > guides) both for vertical and horizontal at 50% (aka center guide)
- Create fixed selection to cut all the duplicated layer at different sizes (1:1 fixed round)
- Warp with clockwise and counter/clockwise swirls the layers
- Duplicate each cut layer and blur the copy and put behind the original slice
- Group each couple, and random rotate the groups

### Background
- Generate with lava filter the background 
- Apply waves effect to BG

