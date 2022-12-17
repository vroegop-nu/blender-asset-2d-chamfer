# Node groups

## 2D Chamfer

The [Original implementation](https://blender.stackexchange.com/a/266230) is by [Robin Betts](https://blender.stackexchange.com/users/35559/robin-betts). I've adjusted it slightly for Blender 3.4 and turned it into a node group.

### Input Parameters

| Parameter | Description                                   |
| --------- | --------------------------------------------- |
| Geometry  | Faces where the z of all vertices is the same |
| Width     | Float value of the chamfer width              |

### Output Parameter

| Paramater     | Description                                            |
| ------------- | ------------------------------------------------------ |
| Geometry      | Chamfered faces                                        |
| Chamfer Edge  | Boolean, true for the new vertices of the chamfer edge |
| Original Edge | Boolean, true for the vertices of the original edge    |