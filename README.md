# Real-time Scan2CAD

## Build Date

20220416

## Source

```bash
https://github.com/theycallmefm/Realtime-Scan2CAD
```

## Install

### Visual Studio

install

```bash
Visual Studio Community 2022
```

### DirectX SDK

Uninstall

```bash
Microsoft Visual C++ 2010 x86 Redistributable
Microsoft Visual C++ 2010 x64 Redistributable
```

and install

```bash
DirectX SDK June 2010
```

then, reinstall

```bash
Microsoft Visual C++ 2010 Service Pack 1 Redistributable Package MFC Security Update
```

### CUDA

install

```bash
CUDA 11.3
```

and copy files

```bash
C:/Program Files/NVIDIA GPU Computing Toolkit/CUDA/v11.3/extras/visual_studio_integration/MSBuildExtensions/*
->
C:/Program Files/Microsoft Visual Studio/2022/Community/Msbuild/Microsoft/VC/v170/BuildCustomizations/
```

### Kinect SDK

install

```bash
Kinect SDK 1.8 # prev. to 2.0
```

### Libtorch

download

```bash
Libtorch 1.11.0 cu113
```

and unzip at

```bash
C:/Program Files/libtorch
```

Make sure the folder structure is

```bash
C:/Program Files/libtorch/bin
C:/Program Files/libtorch/include
C:/Program Files/libtorch/lib
...
```

add the path

```bash
C:\Program Files\libtorch\lib
```

to the System Path

## Build

build with Release x64

## Run

TODO

## Enjoy it~
