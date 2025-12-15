# Brah Rah's Save Some Seconds

BrsSSS is a Godot 4.4 editor addon that has a neat collection of tools that make developing in godot a bit faster and easier.


## Features

- Get code and node paths for copy and pasting into external editors
- Enable / disable editor addons
- Restart addons without restarting the editor
- And some more check the manual for details


## Installation

### Option 1: Godot Asset Library
(Not yet published)  
Link will be added once available.

### Option 2: Manual installation

1. Download the latest release ZIP from: https://github.com/BrahRah/BrsSSS_Addon/releases
2. Extract it into your project so you get:

```
res://addons/
  ├─ BrsSSS/
  └─ BrsLib/
```

3. Open Godot
4. Go to Project → Project Settings → Plugins
5. Enable BrsSSS


## Usage

1. Enable the plugin
2. Open the **BrsSSS** dock in the editor
3. Enter addon names (comma-separated)
4. Disable / re-enable addons as needed

For full usage instructions, see the manual below.


## Documentation

Full manual (HTML):
    `Manual/manual.html` (local)  

The manual includes:
- Full UI explanation
- Advanced usage
- Screenshots and Videos


## Requirements

- Godot 4.4
- Editor usage only (not runtime)


## Known Limitations

- Restarting addons relies on editor plugin reload behavior
- Some plugins may not re-initialize cleanly after reload


## License

Mozilla Public License 2.0


## Credits

Created by Brah Rah


## Related Repositories

- BrsSSS_Addon: https://github.com/BrahRah/BrsSSS_Addon
