StealthOS
===========
Just another aosp flavour with additional topping of stealth club.


Getting started
---------------

To get started with Android/StealthOS, you'll need to get
familiar with [Repo](https://source.android.com/source/using-repo.html) and [Version Control with Git](https://source.android.com/source/version-control.html).
### Setting up build environment
```
$ sudo apt-get install openjdk-8-jdk default-jdk
$ git clone https://github.com/akhilnarang/scripts
$ cd scripts
$ bash setup/android_build_env.sh
```

To initialize your local repository using the StealthOS trees, use a command like this:
```
$ repo init -u git://github.com/Stealth-OS/manifest -b 11
```
Then to sync up:
```
$ repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```
### Build
---------------
```
$ cd ~/stealth
$ source build/envsetup.sh
$ lunch stealth_<devicecodename>-eng
$ m stealth
```
### Obtaining zip output
```
$ cd ~/stealth/out/target/product/<device-name>
```
OR
```
$ cd $OUT
```

Project status 
---------------
WIP [DO-NOT-SYNC]

also join t.me/Stealthos for project updates 

# Credits
[Lineage OS](https://github.com/LineageOS)<br>
[Evolution X](https://github.com/Evolution-X)<br>
[Google for AOSP](https://www.google.com/aosp)<br>





