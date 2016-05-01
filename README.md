## TWRP device tree for Galaxy S7 edge (Korea)

Add to `.repo/local_manifests/hero2ltekor.xml`:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
	<project path="device/samsung/hero2ltekor" name="android_device_samsung_hero2ltekor" remote="TeamWin" revision="android-6.0" />
</manifest>
```

Then run `repo sync` to check it out.

Kernel sources are available at: https://github.com/jcadduono/nethunter_kernel_herolte/tree/twrp-6.0

