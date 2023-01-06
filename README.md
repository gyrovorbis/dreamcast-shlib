# Strip Header Library 2.0 #
Dreamcast Strip header generation library.

 This can generate vertex strip headers for use with the Sega Dreamcast's PVR.
 It supports most parameters that are of interest.

## Supported Headers
 Type | Primitive | Color      |     Modifier type |  Textured |  32BIT UV
 ---- |  ---------|   -----    |   -------------   |--------   |--------
 00   |  Polygon  |   Packed   |   Shadow          |No         |-
 01   |  Polygon  |   Float    |   Shadow          |No         |-
 02   |  Polygon  |   Intensity|   Shadow          |No         |-
 03   |  Polygon  |   Packed   |   Shadow          |Yes        |Yes
 04   |  Polygon  |   Packed   |   Shadow          |Yes        |No
 05   |  Polygon  |   Float    |   Shadow          |Yes        |Yes
 06   |  Polygon  |   Float    |   Shadow          |Yes        |No
 07   |  Polygon  |   Intensity|   Shadow          |Yes        |Yes
 08   |  Polygon  |   Intensity|   Shadow          |Yes        |No
 09   |  Polygon  |   Packed   |   Two-parameter   |No         |-
 10   |  Polygon  |   Intensity|   Two-parameter   |No         |-
 11   |  Polygon  |   Packed   |   Two-parameter   |Yes        |Yes
 12   |  Polygon  |   Packed   |   Two-parameter   |Yes        |No
 13   |  Polygon  |   Intensity|   Two-parameter   |Yes        |Yes
 14   |  Polygon  |   Intensity|   Two-parameter   |Yes        |No
 15   |  Sprite   |   Packed   |   -               |No         |-
 16   |  Sprite   |   Packed   |   -               |Yes        |No
 17   |  Modifier |   -        |   -               |-          |-

## Author ##
Anton Norgren (Tvspelsfreak) (2011)  

## Note ##
I, Falco Girgis, am not the author of this work. It was developed by my long-time friend and mentor growing up, Tvpselsfreak, who taught me everything I knew about programming for the Sega Dreamcast when I was just a teenager. Anton has since disappeared from the Dreamcast-scene, and nobody has been able to get into contact with him. He gave me a copy of his unreleased SHLib to use within my own engine many, many years ago, and it has served me well ever since then. I believe it would have been his wish that this work got released, so I have uploaded it to share with the community, but I do not take credit for any of it.
