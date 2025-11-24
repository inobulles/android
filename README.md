# AQUA Android Distribution

LineageOS-based Android ROM with features to integrate with AQUA ecosystem 👽🤖

The tentative stylized name for this is A₂D.

## Building

Android is only really buildable on Linux.

With [`repo`](https://source.android.com/docs/setup/download) installed:

```sh
repo init -u https://github.com/inobulles/android.git --git-lfs
repo -j4 sync
```

Then you can follow the LineageOS build instructions for your device.
E.g. for the Xiaomi Mi 9T (davinci): <https://wiki.lineageos.org/devices/davinci/build/variant1>
