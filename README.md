# What is this?
This is the script fixed the problem that fbx importer changes Shape key order unintensiously.

# HOW TO FIX BLENDER
Replace Blender/2.79/scripts/addons/io_scene_fbx/import_fbx.py with this repo's import_fbx.py.  
I tested in Blender v2.79 and addon "Import-Export: FBX format" Version 3.7.17.

# これは?
Blenderのfbxのインポートでシェイプキーの順番が変更されないようにしたスクリプト  
つまりUnity上での順番が保持される

# これの使い方
Blender/2.79/scripts/addons/io_scene_fbx/import_fbx.pyをこのリポジトリにあるimport_fbx.pyで置き換えるだけ  
Blender v2.79、"Import-Export: FBX format" Version 3.7.17でテストした  
とりあえずクレリックとミーシェとスノウエルフでは動いた、メッシュが多かったり同名のシェイプキーがあるとバグるかも