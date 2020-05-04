# PREFAB PREPARATION ASSETS

## This is the folder where all non prefab prop assets will be stored. Until a game engine is chosen and mechanics are finalized all models will need to be submitted as OBJ or FBX files. 

If you are an asset modeler volunteering on this project this is where you can find info on what can be done.

The following requirements should be followed when submitting assets to this folder.

1. Assets are low poly in the range of 1,000 triangles to a max of 10,000 triangles per Asset depending on complexity.
2. 2K texture maps for Assets marked with a *. 1K texture Maps for all others. RMA maps are an exception as these are all 1K maps. In some cases an opacity map will be required and can be added to the RMA map as an alpha channel.
3. Each prop requires a Normal map, a Diffuse map, and an RMA map. see below the note on RMA maps
4. Props with moving parts should be modeled as separate meshes but rigged and exported as a single OBJ or FBX. An example of this is the hospital bed.
5. Any object with moving parts such as the hospital bed or ventilator tubes should be rigged.
6. All texture files should be in the PNG format.
  
  
RMA Maps: An RMA map is an RGB texture map with the Roughness, Metallic and AO maps all stored within the RGB channels of one image. The roughness is stored within the red channel, the Metallic is stored within the green channel and the Ambient occlusion is stored within the Blue Channel. This can be achieved with your image editor of choice manually by adding your maps to each channel or automatically if you are exporting maps from a texture software such as Substance painter or Mari.
  
  
Below for the current list of assets needed. as a volunteer you can work on any item in any order. This list will be updated regularly with new items:
  
- [ ] Face Shield: Unused ( if possible pack into same UV space as used shield)
- [ ] Face Shield: Used and contaminated
- [ ] Gloves: Clean and unused ( If possible into same UV space as used gloves)
- [ ] Gloves: Used and contaminated
- [ ] Folded unused Gown
- [ ] Used Gown
- [ ] Multi position semi electric hospital bed *
- [ ] ICU specific hospital bed( has features not included in regular beds) *
- [ ] Ventilator( full equipment) *
- [ ] Desk Chair
- [ ] Medical storage cabinet
- [ ] N95 mask: Unused*
- [ ] N95 mask: Used
