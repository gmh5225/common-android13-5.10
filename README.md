# common-android13-5.10

```
sudo apt-get install repo
repo init -u https://android.googlesource.com/kernel/manifest -b common-android13-5.10
repo sync
tools/bazel build //common:kernel_aarch64_dist
```
