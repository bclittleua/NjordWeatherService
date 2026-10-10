# NWS — Njord Weather Service

Primarily intended as a tool for sailors and trip planning, NWS adds weather forecasting to Valheim, including predicted weather, wind direction, and wind strength for selectable biomes.
<img width="1920" height="1080" alt="NWS_example_02" src="https://github.com/user-attachments/assets/96ca592c-4b97-4caa-b32e-1a8870494b51" />
<img width="1920" height="1080" alt="NWS_example_01" src="https://github.com/user-attachments/assets/8ad51ff2-5e1b-4d5e-b8eb-93f07dc5cdd4" />

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
| F6 | Show/hide NWS |
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

## Mouse controls

Open Valheim's map (**M**) to interact with the NWS window: drag to reposition, select a forecast biome, change outlook tabs, or toggle Full/Mini. Close the map to resume gameplay. NWS does not unlock or manipulate the mouse cursor.

## Configuration

All NWS keybindings can be changed in the BepInEx configuration file:

`BepInEx/config/nws.njordweatherservice.cfg`


## MOD compatability

- As far as I can tell, works fine with [LongerDays](https://thunderstore.io/c/valheim/p/TastyChickenLegs/LongerDays/), but your mileage may very.
- I have given up trying to have no keybind conflicts with other mods, use the bepin config and fix your own mess.
