# Assets Directory

Place your downloaded 3D models here from free databases:

## Recommended Sources
- [OpenGameArt.org](https://opengameart.org/) - Free 3D models, textures, sounds
- [Sketchfab](https://sketchfab.com/) - Filter by 'downloadable' + 'free'
- [Kenney.nl](https://kenney.nl/assets) - Game-ready free assets
- [Quaternius](https://quaternius.com/) - Free low-poly models
- [GrabCAD](https://grabcad.com/library) - Engineering 3D models

## Supported Formats
- OBJ (.obj, .mtl)
- FBX (.fbx) - via Assimp
- GLTF/GLB (.gltf, .glb)
- Collada (.dae)
- 3DS (.3ds)
- BLEND (.blend)

## Example Setup
1. Download a model (e.g., `tree.obj` and `tree.mtl`)
2. Place in `assets/` directory
3. Update the model path in `src/main.cpp`:
   ```cpp
   Model ourModel("assets/tree.obj");
   ```
4. Add textures if needed

## Note
Assets are .gitignored - you'll need to download them separately.
The game will look for `assets/model.obj` by default.
