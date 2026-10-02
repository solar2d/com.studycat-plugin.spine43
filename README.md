# plugin.spine43 (publisherId `com.studycat`)

Spine runtime plugin for Solar2D, for skeletons exported with Spine 4.3. It loads Spine `.json` or `.skel` files with
their `.atlas` and plays them as display objects. Current version: 3.0.0.

Platforms: Android, iOS, iOS Simulator, macOS Simulator, Windows Simulator. It needs Solar2D 2026.3731 or newer.

## build.settings

```lua
settings =
{
    plugins =
    {
        ["plugin.spine43"] =
        {
            publisherId = "com.studycat",
        },
    },
}
```

```lua
local spine = require("plugin.spine43")
```

Use one Spine plugin per app: `plugin.spine43`, `plugin.spine42` or the older `plugin.spine`.

To stay on one release, add `version = "vN"` to the entry, with a tag from this repository's Releases page.

## Links

- Documentation: https://spineplugin.readthedocs.io/en/4.3/
- Moving from `plugin.spine42` (Spine 4.2): https://spineplugin.readthedocs.io/en/4.3/migration.html
- Source, changelog and issues: https://github.com/depilz/spinePlugin
- Skeletons exported with Spine 4.2 need `plugin.spine42`: https://github.com/solar2d/com.studycat-plugin.spine42

## License

The plugin includes the Spine Runtimes by Esoteric Software, under the Spine Runtimes License Agreement in
[Spine-Runtimes-License-Agreement.txt](Spine-Runtimes-License-Agreement.txt). Each user of the plugin needs their own
Spine Editor license: https://esotericsoftware.com/spine-editor-license
