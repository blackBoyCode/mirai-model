# Mirai OS Model

### A flexible mirai open source model. 

#### Info

##### _All models are build using Blender_  

I created a folder structure to organize the models. The `base_model` folder contains the `character_simple_poly` and has unmerged mirror modifiers and the subdivion is not applied. I made it this way if I need to go back and fix the main body. The model is not centered, the main reason is for matching the reference images. the `character_simple_poly` is the base model for modeling clothing or other character variants.

The `solar_marine_model` folder contains 3 subfolders: modeling folder which has `character_solar_marine` which is a base model with the model outfit and the `millennium_blade` that goes with it. These models has also unmerge mirror and modifier but contains all the guide image with pieces that make the model. The `output_mesh` folder contains the final model meaning that it in .fbx, the model have collapsed modifiers, cleanup has been made and it's centered ready for use. The rigging folder contains the mesh with the rig along with test pose file.


#### RoadMap

Currently a few things are still under development:

- [x] Base Model
- [x] Solar Marine Model
- [X] Solar Marine UVs
- [ ] Solar Marine Rigging
- [x] Millennium Blade Model
- [ ] Millennium Blade UVs
- [ ] clean file structure in all folders

#### Workflow

If I map the workflow I did it would be like this:

`base model` -> `outfit`(base model + outfit "eg: solar marine" ) -> `uv`(outfit + material/texture) -> `rigging`(outfit+uv+rig) -> `output mesh`(all together in fbx format)

keep in mind that the model is not perfect and might have some problem(such as typology, uvs or rigging) as I'm still learning to build a proper model with blender and I iterate as I learn new things. 



