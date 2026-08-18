# Rika's Dalamud Plugins

This repository is a third-party Dalamud plugin feed. It publishes metadata
only; plugin archives are immutable GitHub Release assets from their source
repositories.

## Install

In game, open `/xlsettings`, go to **Experimental**, and add this URL under
**Custom Plugin Repositories**:

```text
https://raw.githubusercontent.com/RikaKagurasaka/DalamudPlugins/main/pluginmaster.json
```

Then open `/xlplugins` and install the desired plugin.

This is an unofficial third-party repository. Use plugins at your own risk and
report issues to their source repository, not the XIVLauncher support channels.

## Maintenance

`pluginmaster.json` is updated by the **Sync Damage Info Extended** workflow.
It downloads the `latest.zip` release asset, validates its generated Dalamud
manifest, and commits an install/update entry. Do not edit package version or
download links by hand.
