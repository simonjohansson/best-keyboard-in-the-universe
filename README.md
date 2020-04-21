![image](https://i.redd.it/zhrj9a4d1gt41.jpg)

This keyboard and associated libraries take heavy inspiration from the
 [dactyl](https://github.com/adereth/dactyl-keyboard) and
the [dactyl_manuform](https://github.com/abstracthat/dactyl-manuform) keyboards.
 Major thanks to Matthew Adereth and Tom Short for their work.

The dactyl-cc keyboard takes a different approach to the structure of the code (and language)
 as well as being more similar in feel to the Kinesis Advantage 2.

```
// Build. Requires g++.
./build.sh.

// If changing files under util you must run a clean build.
./build.sh --clean

// To generate STL from command line:
openscad -o things/left.stl out/left.scad
```
