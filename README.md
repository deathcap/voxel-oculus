voxel-oculus
============

Oculus stereo view for voxeljs.

## Example

```javascript
var createOculus = require('voxel-oculus');
var oculus = createOculus(game, {distortion: 0.2, separation: 5});
oculus.enable();
```

## Parameters
* **separation**: eye separation
* **distorsion**: distorsion factor to compensate lens distortion
* **aspectFactor**: modify width/height

E.g for 3d TV: distorsion=0 and aspectFactor=0.5

