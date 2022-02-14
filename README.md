UselessRom
===========

This is a useless rom that iI am building for training purposes.

Getting Started
---------------


<p align="center">
  <img src="https://i.imgur.com/tnI2yLM.jpg"/>
</p>

We aim to bring a more consistent, fluent and smooth experience with all your must-have customizations, for you, for the community, and for everyone.


### Instructions
1. Run the following commands to sync source

```
repo init -u https://github.com/Project-Awaken/android_manifest -b 11
```
&nbsp; &nbsp; &nbsp; To save more time and space, you can do a shallow clone using

```
repo init --depth=1 -u https://github.com/Project-Awaken/android_manifest -b 11
```

2. To sync source, enter

```
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

3. Once the source is downloaded/synced, prepare your device trees, dependencies and start the build.

