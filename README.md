# CityU-FYP-Elston-Trial-NvLab-InstantNeRF
3D
1. Put image in data folder
2. python scripts/colmap2nerf.py --colmap_matcher exhaustive --run_colmap --aabb_scale 16 --images data/name
3. Modify folder structure
4. C:\Users\elsto\Documents\GitHub\CityU-FYP-Elston-Trial-NvLab-InstantNeRF\instant-ngp\build\testbed.exe --scene data/name

Gigapixel
1. Put image in data folder
2. Convert to bin
python scripts\convert_image.py --input data/map01/Tile_+5571_+5480_0.jpg
3. C:\Users\elsto\Documents\GitHub\CityU-FYP-Elston-Trial-NvLab-InstantNeRF\instant-ngp\build\testbed.exe --scene data/map01/Tile_+5571_+5480_0.bin
4. python scripts\convert_image.py --output data/map01/Tile_+5571_+5480_0.bin