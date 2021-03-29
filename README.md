# GLTFast_MipMapFix
Fix Unity plugin "GLTFast" mipmap issue

# Reproduced Issue
- Use Unity 2020.3.1 (LTS)
- Use Universal RP
- Install [GLTFast](https://github.com/atteneder/glTFast) plugin
- Load model [result.gltf](https://yadi.sk/d/2lbcDajqgQ8wSg) in runtime
# Expected result
- Texture represented correctly in long and short distance, with filtering and mip maps
# Actual result
- Texture represented as "sharp" colorize "noise" in long distance without filtering and mip maps
# Limitation
- Model can be processed, but should be still .gltf (.glb also not exepteble)
- GLTFast plugin should remain in "Packeges" you can put source code in to "Assets" folder
