# Mesh Tools <sub><p align="right">Feature Added in: [v1.4.0](RELEASE_LOG.md#140)</p><sub>

[**Return to Home**](README.md)

**Mode:** Edit Mode

## Contents:

1. [Bevel](MESH_TOOLS.md#bevel)
2. [Edges Functions](MESH_TOOLS.md#edges-functions)
3. [Set Face Strength](MESH_TOOLS.md#set-face-strength)

![Mesh Tools Cover](/media/mesh_tools.png)

## Bevel

Module helps to set up to 3 values of bevel offset to switch between them while working on the asset.

**Affect**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The choice between edges and vertices to be affected by the bevel.


**Use Offset**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The choice between 3 values of the bevel. The selected option will be used after pressing "Bevel" button.


**Offset #1, Offset #2, Offset #3**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Three values of the bevel.


**Button 'Bevel'**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Apply the value of selected offset to selected edges of vertices.


## Edges Functions

**Mark Sharp**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The Sharp mark is used by the split normals and the Edge Split modifier, which are part of the smoothing or customized shading techniques. As seams, it is a property of edges, and these operators set or unset it for selected ones.


**Mark Seam**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;These operators set or unset this mark for selected edges. Seams are a way to create separations, “islands”, in UV maps.


**Clear All**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Clear all sharp and seam edges in the selected edges.

## Set Face Strength

Use the module to pick one of Weak, Medium, or Strong. Then this tool changes the Face Strength of currently selected faces to the chosen face strength.