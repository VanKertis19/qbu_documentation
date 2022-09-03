# Batch Export

[**Return to Home**](README.md)

**Mode:** Object Mode

This module helps to export objects as .fbx files. There are two main types of batch export module:
1. [Standard](BATCH_EXPORT.md#standard-batch-export)
2. [Collections](BATCH_EXPORT.md#collections-batch-export)

## Standard Batch Export

![Batch Export Cover](/media/batch_export_standard.png)

**Selected Objects**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Export selected objects in the separate .fbx files or export all visible objects in one .fbx.


**Object Name**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The name of the single object if all visible objects are exported in one .fbx file (Selected Objects = False). 


**Export Children**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Export objects with all linked and visible children. You don't need to select children, only the target object. All children will be packed in .fbx of the target object. Suitable for export objects with linked collisions (as children).


**Apply Modifiers**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Apply all modifiers of the exported objects.


**Apply Transforms**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Apply rotation and scale transforms of exported objects. Location is not affected.


**Object Type**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Export only geometry objects or also empties (sockets for UE).


**Smoothing**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Export smoothing information. There are three variants: normals only, face, edge.


**Export Type**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Export type - [Standard](BATCH_EXPORT.md#standard-batch-export) or [Collections](BATCH_EXPORT.md#collections-batch-export).


**Use One Folder**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Use one folder for export or up to three to switch between them.


**Active Folder**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Active folder for export (if Use One Folder = False).


**Export Folder/s**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Address of the target folder for export (up to three options).


**Accept**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Choose target folder from the Blender folder manager.


**Open Folder**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Open the target folder.



## Collections Batch Export

![Batch Export Cover](/media/batch_export_collection.png)