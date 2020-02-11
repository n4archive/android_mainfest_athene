# android_mainfest_athene
Well, I do not even own that device lol. Done for https://www.reddit.com/u/micheat
## Building LineageOS
To get started with any project firstly you need to initialize the repository by

    repo init -u git://github.com/LineageOS/android.git -b lineage-16.0

Then go get the local manifests

Download lineage-16.0-rajatgupta1998.xml
Rename it to lineage-16.0.xml
And lastly move it to `*YOUR ROM DIRECTORY*/.repo/local_manifests`

Then to sync up:

    repo sync

Then to build:

     cd <source-dir>; . build/envsetup.sh; lunch lineage_athene-userdebug; brunch athene

## android_mainfest_athene
© 2020 nift4
Maintained by... nobody?
