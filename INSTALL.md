# How to Add Krhom's Presets to Betaflight

To use these custom tuning and filter presets in Betaflight Configurator, you need to add this repository as a custom preset source.

## Step-by-Step Instructions

1. Open **Betaflight Configurator** and connect your flight controller.
2. Navigate to the **Presets** tab on the left-hand menu.
3. Click on **Preset sources** (usually located near the top right).
4. In the Preset Sources dialog, click the **Add new source** button at the bottom left.
5. A new source entry will appear. Fill in the details exactly as follows:
   - **Name**: `Krhom's Presets`
   - **Url**: `https://github.com/Krhomv/firmware-presets/`
   - **GitHub branch**: `krhom-default-setup`
6. Click the **Save** button next to your new entry.
7. Make sure the source is active! You should see a yellow circle with a checkmark next to your preset source name, and the button below the branch name should say **Make disabled** (which means it is currently enabled).
8. Click **OK** to close the dialog.

### Adding the Source Configuration Example
Reference the screenshot below to ensure your setup is correct:

![Betaflight Preset Sources Configuration](preset_sources.png)

## Applying the BandoLovers Tune

Once the custom source is configured and active, you can apply the tune to your drone:

1. In the **Presets** tab, locate the search bar at the top.
2. Type `BandoLovers 5" Bando Tune` or just `bando` to filter the available presets.
3. Select the tune that appears from `Krhom's Presets`.
4. Choose the appropriate options for your **Frame & Action Cam**, **Tuning Profile Aggressiveness**, and **Center of Gravity Setup**.
5. Click **Pick** (or **Apply**) and then **Save and Reboot** to apply the settings to your flight controller.

### Preset Search Example
Reference the screenshot below for an example of searching for the tune:

![BandoLovers Tune Search](bl_tune.png)

*(Note: Please save your screenshots as `preset_sources.png` and `bl_tune.png` in the root of this repository so they display correctly above).*
