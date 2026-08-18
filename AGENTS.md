# Rika's Dalamud Plugins feed

- Keep `pluginmaster.json` valid JSON and limited to verified release packages.
- Release archives belong in each plugin's source GitHub Release, not this repo.
- The sync workflow validates the internal name, version and Dalamud API level
  from the packaged manifest before publishing an entry.
- Do not add a feed entry until its source plugin completed its live-game test
  gate and has an immutable `latest.zip` release asset.
