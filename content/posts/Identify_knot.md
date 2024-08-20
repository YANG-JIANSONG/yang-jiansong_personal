+++
authors = ["Yang Jiansong"]
title = "The usage of Identify knot  program"
date = "2024-08-20"
description = "Construction time and method"
tags = [
    "hugo",
    "markdown",
    "knot",
]
categories = [
    "syntax",
    "theme demo",
]
series = ["Theme Demo"]
+++
使用方法: Identify_knot, Identify_knot_new

```bash
## requirement
安装eigen, libginac-dev, libcln 这三个c++库。

sudo apt install libeigen3-dev
sudo ln -s /usr/include/eigen3/Eigen /usr/include/Eigen
sudo apt install libginac-dev

#-h
-a: alexander map file, example "-a /home/user/table_alex.txt"
-c: set number of thread, example -c 1
-n: number of beads
-k: knot type desired, example "-k 4_1"
-t: number of tail base pairs, set save core+2*tail for knot conf
-r: ring, default for open
-h: help
-s: save chain, default for false
-u: save chain for unknot, default for false
-f: format type, xyz or lammps, default for xyz



 ```