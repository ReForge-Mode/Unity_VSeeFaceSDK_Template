# Unity VSeeFace Template
Installing VSeeFaceSDK on Unity is such a hassle. So here, just download this project and you're good to go. 

This project has cleaned up every problematic modules and includes all of the required dependencies to run VSeeFaceSDK:
- UniVRM v0.89: https://github.com/vrm-c/UniVRM/releases/tag/v0.89.0
- VSeeFace SDK v1.13.38c: https://github.com/emilianavt/VSeeFaceSDK/releases/tag/v1.13.38c

All you gotta do is to open this with Unity Hub. If you didn't have Unity version 2019.4.31f1, it should immediately prompt you to install it. After that, you can open this project and import your model as usual.

## What hassle? 
Four reasons:
- That project is severely outdated, using 2019.4.31f1 (from September 30, 2021) and UniVRM version 0.89 (from November 9, 2021)
- That has a side effect of causing several Unity module to no longer work and immediately cause errors on startup. For example: like Unity Collab being deprecated and replaced with PlasticSCM.
- You would need to remove problematic modules one by one and restart Unity several times to get it to work.
- This is unacceptably inaccessible for people who never use Unity before and just want to get your vtuber model running
