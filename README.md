Manifests
================================
These are various local manifests for my android builds. [cm,omni,RR etc.]


###Usage###
Ready the files.

```bash
# Create the appropriate directory. [This is useful in general too.]
$ mkdir -p ~/omni
# Get the repo.
$ repo init -u git://github.com/omnirom/android.git -b android-5.1
```
Create the local manifest.

```bash
# Symlinks.
$ mkdir -p .repo/local_manifests
```
Now get the right file.

```bash
# Get the local manifest.
$ wget https://github.com/HaoZeke/Manifests/blob/master/z3/omni/z3_omni.xml
```
