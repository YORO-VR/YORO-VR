# You Only Render Once (YORO)

**You Only Render Once: Enhancing Energy and Computation Efficiency of Mobile Virtual Reality**

Xingyu Chen, Xinmin Fang, Shuting Zhang, Xinyu Zhang, Liang He, Zhengxiong Li

*Proceedings of the 23rd Annual International Conference on Mobile Systems, Applications and Services (MobiSys 2025)*

## Description

This is YORO's open source data and code.

This directory contains:
- code: Contains Unity project, python code and a build for android.
- data: Contains the raw data of evaluation and figures on the paper.

## System Requirements

- Windows 10 or Windows 11
- Unity 2021.3.12

## Installation Guide

- Execute the `setup.cmd`
- Extract the zip file in `./code/Compiled` folder

## Build for Oculus Quest

- Open the `UnityProject` using Unity 2021.3.12
- Open `Edit -> Project Settings`
- Click `XR Plug-in Management`
- Click `Android`
- Check `Oculus`
- Click `Oculus` under the `XR Plug-in Management`
- Click `Android`
- Switch `Stereo Rendering Mode` to `Multi Pass`
- Open `File -> Build Settings`
- Click `Android`
- Click `Switch Platform`
- Click `Build` and select a folder.
- Upon building finished, the built `.apk` file should be in the selected folder.

## Citation

If you find this work useful, please cite our paper:

```bibtex
@inproceedings{chen2025you,
  title     = {You Only Render Once: Enhancing Energy and Computation Efficiency of Mobile Virtual Reality},
  author    = {Chen, Xingyu and Fang, Xinmin and Zhang, Shuting and Zhang, Xinyu and He, Liang and Li, Zhengxiong},
  booktitle = {Proceedings of the 23rd Annual International Conference on Mobile Systems, Applications and Services},
  pages     = {263--276},
  year      = {2025}
}
```

## Copyright

Copyright © 2025 Xingyu Chen, Xinmin Fang, Shuting Zhang, Xinyu Zhang, Liang He, Zhengxiong Li. All rights reserved.
