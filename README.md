# local_manifests
1. fork this repo
2. clone forked repo
3. Create .xml file (you can use any name you want)
4. Copy&Paste this

        <?xml version="1.0" encoding="UTF-8"?>
        <manifest>
            <!-- remote source -->
            <remote name="LineageOS" fetch="https://github.com/LineageOS" />
            <remote name="TheMuppets" fetch="https://github.com/TheMuppets" />

            <!-- Device Tree -->
            <project name="android_device_samsung_beyond1lte"        path="device/samsung/beyond1lte"        remote="LineageOS"  revision="lineage-18.1" />
            <project name="android_device_samsung_exynos9820-common" path="device/samsung/exynos9820-common" remote="LineageOS"  revision="lineage-18.1" />
            <project name="android_device_samsung_slsi_sepolicy"     path="device/samsung_slsi/sepolicy"     remote="LineageOS"  revision="lineage-18.1" clone-depth="1" />
            <project name="proprietary_vendor_samsung"               path="vendor/samsung"                   remote="TheMuppets" revision="lineage-18.1" clone-depth="1" />
            <project name="android_kernel_samsung_exynos9820"        path="kernel/samsung/exynos9820"        remote="LineageOS"  revision="lineage-18.1" clone-depth="1" />
        
            <!-- HALs -->
            <project name="android_hardware_samsung"                 path="hardware/samsung"                 remote="LineageOS"  revision="lineage-18.1" clone-depth="1" />
            <project name="android_hardware_samsung_nfc"             path="hardware/samsung/nfc"             remote="LineageOS"  revision="lineage-18.1" clone-depth="1" />
        </manifest> 

5. replace everything to remotes&repos you need 
6. upload to forked repo
7. done
