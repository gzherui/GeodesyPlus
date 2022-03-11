##### Compilation

```bash
git submodule update --init
mkdir build; cd build; cmake ..; make
```

##### Run
```bash
./geodesy ../dat/bear/bear.graph
```

##### Dependency
NOTE: compiling in Ubuntu 20.04 causes seg faults for some reason
- build-essential
- xorg-dev
- libgl1-mesa-dev
- libigl --> cloned from repo
- eigen3
- ShapeOp
