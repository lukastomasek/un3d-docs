# un3d-docs
UN3D engine API docs

## Space Builder

  | Event      | Id (String) | Data     |
| :---        |    :----:   |          ---: |
| Create Room      | CreateSpaceRoom       | {width: number, height: number, length: number} in meters  |
| Delete Room   | DeleteSpaceRoom        | null      |
| Toggle Orthographic Camera | CameraOrtho | null |
| Toggle Perspective Camera | CameraPerspective | null |
| Update Wall Colour | WallColourUpdated | hexcode: number |
| Instantiate GLB| InstantiateGlb | { productNode, event (ondragover)}|
