# NWS — Njord Weather Service

NWS adds weather forecasting to Valheim, including predicted weather, wind direction, and wind strength for selectable biomes.

## Forecast outlooks

- **24 Hours:** Hourly forecasts.
- **3 Days:** Morning, afternoon, and evening forecasts.
- **5 Days:** Extended morning, afternoon, and evening forecasts.

## Display modes

- **Full:** Expanded, scrollable forecast grid.
- **Mini:** Single row of four forecast cards, designed for unobtrusive use while sailing.
- Click **FULL/MINI** in the NWS header to switch modes (open the map to use the mouse).

## Default keyboard controls

| Key | Action |
|---|---|
| F9 | Show/hide NWS |
| Left / Right Arrow | Previous/next forecast page in Mini; scroll one row in Full |
| Up / Down Arrow | Previous/next biome (wraps around) |
| Right Ctrl + Left / Right Arrow | Previous/next outlook (24 Hours, 3 Days, 5 Days; wraps around) |
| Right Ctrl + Up / Down Arrow | Increase/decrease opacity by 10% (10–100%) |
| Numpad 1 | Meadows |
| Numpad 2 | Black Forest |
| Numpad 3 | Swamp |
| Numpad 4 | Mountain |
| Numpad 5 | Plains |
| Numpad 6 | Mistlands |
| Numpad 7 | Ashlands |
| Numpad 8 | Deep North |
| Numpad 0 | Ocean |
| Right Ctrl + Numpad 0 | Detect and select your current biome on demand |

**F9 is always active.** All other NWS shortcuts only work when the NWS window is visible. Right Ctrl is the default modifier; Left Ctrl does not activate these shortcuts. Modified shortcuts take priority over unmodified ones.

## Mouse controls

Open Valheim's map (**M**) to interact with the NWS window: drag to reposition, select a forecast biome, change outlook tabs, or toggle Full/Mini. Close the map to resume gameplay. NWS does not unlock or manipulate the mouse cursor.

## Configuration

All NWS keybindings can be changed in the BepInEx configuration file:

`BepInEx/config/nws.njordweatherservice.cfg`

## Biome behavior

The **Current biome (last checked)** label shows the biome recorded when NWS was opened or when the current-biome shortcut was pressed. Selecting a forecast biome manually does not change it automatically when you travel. Press **Right Ctrl + Numpad 0** to read the current biome and switch the forecast to it. NWS does not periodically poll for biome transitions.
