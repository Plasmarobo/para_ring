## Para_Ring

para_ring is a parametric ring module for scad.
It generates a ring by slicing a sphere, and has 3 parameters:
`para_ring(diameter, width, thickness)`

### Parameters
`diameter` is the outer diameter of the ring
`width` is the minimal chord distance of the sphere (the place it will be cut, centered on the x axis)
`thickness` is difference in diameter between the inner subtracted sphere and the outer sphere.