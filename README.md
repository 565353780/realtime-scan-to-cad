# Real-time Scan2CAD

## Build Date

20220418

## Source

```bash
https://github.com/theycallmefm/Realtime-Scan2CAD
```

## Download

make a new dir

```bash
C:/ScanNet/
```

and run the script of ScanNet with python2

```bash
python2 download-scannet.py -o C:/ScanNet/ --id scene0022_00
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
C:/Program Files/libtorch/lib
```

to the System Path

## Build

build with

```bash
Release
x64
v143
c++14
```

## Run

### Run With ScanNet dataset

run the bat file directly

```bash
DepthSensingCUDA/runManolisScan.bat
```

### Run With Kinect camera

run the bat file directly

```bash
DepthSensingCUDA/runDefaultBinaryDump.bat
```

## Enjoy it~
