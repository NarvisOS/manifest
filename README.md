NarvisOS
========

<p align="center">
 <img src="https://github.com/narvisos/manifest/blob/mark10/frame.jpg" > 
</p>


To initialize your local repository, use this command:

	repo init -u https://github.com/NarvisOS/manifest.git -b mark10

To Sync:

	repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags

Setup build enviroment :
```
. build/envsetup.sh 
```

Start build process :
```
brunch <device>
```

A Project By - Nayan Arora , JamieH  , ZèD
