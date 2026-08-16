# Samsung TV Remote — AJE Fork

This is an AJE-maintained fork of the Samsung TV Remote driver.

## Install with Hubitat Package Manager

Use HPM's **Install via URL** option with this package manifest URL:

```text
https://raw.githubusercontent.com/aerickson/HubitatActive/20260804-children_devices/SamsungTvRemote/packageManifest.json
```

The manifest installs the forked driver and tracks subsequent numeric version
updates, such as `2.3.10.1`.

## Switch an existing TV device

Do not delete the existing TV device or its child devices.

1. Install the fork using the manifest URL above.
2. Open the existing parent TV device and choose **Edit Device**.
3. Change **Type** to `Samsung TV Remote (AJE Fork)`.
4. Save the device.
5. Click **Save Preferences**.
6. Test the TV power and child remote buttons.

The existing device ID, dashboards, automations, preferences, and child
devices should remain in place. Remove the old duplicate driver code only
after the existing TV device has been switched successfully.

## Updating

After installation, use HPM's **Update** option. The fork uses numeric
versions because HPM compares dot-separated numeric version components.

