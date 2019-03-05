# What is this?
This is the script fixed the problem that fbx importer changes Shape key order unintensiously.

# HOW TO FIX BLENDER
Replace Blender/2.79/scripts/addons/io_scene_fbx/import_fbx.py with this repo's import_fbx.py.  
I tested in Blender v2.79 and addon "Import-Export: FBX format" Version 3.7.17.
You SHOULD copy original file berfore replace.

# これは?
Blenderのfbxのインポートでシェイプキーの順番が変更されないようにしたスクリプト
要するにfbxのUnity上での順番がBlenderでインポートしても保持される

# これの使い方
Blender/2.79/scripts/addons/io_scene_fbx/import_fbx.pyをこのリポジトリにあるimport_fbx.pyで置き換えるだけ  
Blender v2.79、"Import-Export: FBX format" Version 3.7.17でテストした  
置き換える前にバックアップを取ること  
とりあえずクレリックとミーシェとスノウエルフでは動いた、メッシュが多かったり同名のシェイプキーがあるとバグるかも