# mw-travel-tooltips

My edit for [Travel Tooltips](https://www.nexusmods.com/morrowind/mods/48306) ensures destination tooltips remain small enough to appear below the mouse pointer, but without significantly shrinking the Vvardenfell map.

I've fixed it by decreasing the scale divider in createTravelMap function from 100 to 50: `local scale=config.scale/50`
