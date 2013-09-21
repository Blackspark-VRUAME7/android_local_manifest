Local Manifest for the Verizon Samsung Galaxy S4

Getting Started
---------------
Create a directory to sync the source code to.
```
mkdir $SOURCE_DIR
cd $SOURCE_DIR
```

Initialize the appropriate repository to the directory you just created, add in local_manifest.xml and sync the code.
```
repo init -u https://github.com/Blackspark-VRUAME7/android -b cm-10.2
curl -L -o .repo/local_manifests/local_manifest.xml -O -L https://raw.github.com/Blackspark-VRUAME7/android_local_manifest/master/local_manifest.xml
repo sync
```

Readme based on KFire-Android android_local_manifest repository.
