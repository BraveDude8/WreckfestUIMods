# wf_hud_layout


<img width="960" height="540" alt="wreckfest UI mod shot 2" src="https://github.com/user-attachments/assets/b6da0315-d50a-4ed7-bc3d-690ba2bfd141" />

Move, resize and hide the **Wreckfest** race HUD in game, with the keyboard or the mouse, and save the layout.

## Install
1. Download the release files.
2. Open your Wreckfest folder: Steam → Library → right-click Wreckfest → Manage → Browse local files.
3. Copy `VERSION.dll` and `wf_hud_layout.ini` next to `Wreckfest_x64.exe`.
4. Start Wreckfest from Steam as usual.

**Uninstall:** delete `VERSION.dll` (and `wf_hud_layout.ini`, `wf_hud_layout.ini.bak`, `wf_hud_layout.log`).

## Use
In a race press **F8** to open UI Edit. A key panel appears and the selected HUD part blinks.

<img width="960" height="540" alt="wreckfest UI mod shot 3" src="https://github.com/user-attachments/assets/5dfc9a2c-5f0e-4e1d-9464-2c754eb026c3" />

| Key | Action |
|---|---|
| O / U | next/previous UI element |
| I J K L | move |
| ] / [ | increase/decrease size |
| H | hide/show |
| Y | reset selected element |
| F9 | save config |
| F10 | reload saved config |
| B | DVD mode (bounce) |
| F8 / Esc | close UI Edit |
| left click | click and drag |
| right click | reset selected element |
| scroll wheel | increase/decrease size (shift = faster) |

- Hold a key to go faster. Clicking an empty spot selects the whole HUD (scale only).
- Saved layouts apply to every race. Units are 1920×1080, so a layout carries across 16:9 resolutions.

## Notes
- Steam version of Wreckfest (64-bit). Not for Wreckfest 2.
- Only changes where HUD parts are drawn. No game files are modified; nothing about physics, cars or your save is touched.
- The key panel shows in windowed and borderless mode; in exclusive fullscreen the keys work but the panel is hidden.
- Keys are read only while the game window is focused. If a key clashes with your controls, rebind it in `wf_hud_layout.ini`.
- Set `enabled = 0` under `[global]` in the ini to turn the mod off without deleting it.
- `wf_hud_layout.log` next to the DLL records what it did. Please attach it to bug reports.
- Tested in singleplayer. Use online at your own risk.
