# common-android13-5.10

```
sudo apt-get install git ccache automake flex lzop bison \
gperf build-essential zip curl zlib1g-dev \
g++-multilib libxml2-utils bzip2 libbz2-dev \
libbz2-1.0 libghc-bzlib-dev squashfs-tools pngcrush \
schedtool dpkg-dev liblz4-tool make optipng maven libssl-dev \
pwgen libswitch-perl policycoreutils minicom libxml-sax-base-perl \
libxml-simple-perl bc libc6-dev-i386 lib32ncurses-dev \
x11proto-core-dev libx11-dev lib32z1-dev libgl1-mesa-dev xsltproc unzip

sudo apt-get install repo
repo init -u https://android.googlesource.com/kernel/manifest -b common-android13-5.10
repo sync
tools/bazel build //common:kernel_aarch64_dist
```
