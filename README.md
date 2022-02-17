<p align="center">
  <img src="https://i.imgur.com/lyJkVeK.png"/>
</p>

We aim to bring a more consistent, fluent and smooth experience with all your must-have customizations, for you, for the community, and for everyone.



### Instructions
1. Run the following commands to sync source

```
repo init -u https://github.com/redlinegame/Useless_android -b 12
```
2. To sync source, enter

```
 repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```

3. Once the source is downloaded/synced, prepare your device trees, dependencies and start the build by the following commands

```
   source build/envsetup.sh
   lunch awaken_<devicecodename>-userdebug
   make bacon -j$(nproc --all)
```


