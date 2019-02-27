## About Fixed-Position Z Probe Mount
- ONLY JellyBOX 2 Supported by this experiment
    - If it works, we'll make JellyBOX Original version as well. 
- Instead of a slot, it has a single hole. This should put the probe into a proper position on any JellyBOX 2 with the default extruder and hotend, both with cold bed and the heated bed. 
- Also, there's no way for this probe to move over time. No way. 
- Thus, the step of setting the probe position is gone
- You only have to Live Adjust the 1st Layer Height and you're done! (For power users; z probe offset.)

## HowTo print
- This gcode is pre-sliced for PETG on a JellyBOX Original or 2.
- There's STL, too... 
- To print in other materials, use the open the included 3mf Cura project file in the latest Cura IMADE3D Edition (go.imade3d.com/cura-download) and edit the settings to your liking. 
- Alternatively, open the gcode in text editor and change the temperatures... for PLA this would be fine.
- The z probe additional walls can be used to add more plastic around the heat inserts as a local cura slicing infill override. We do that in production. Not necessary in testing... 

## Feedback
- This is a proof of concept. We have tried it successfully, but we need more tests. Comment here or 
