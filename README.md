# mw-travel-tooltips

My edit ensures destination tooltips remain small enough to appear below the mouse pointer, but without significantly shrinking the Vvardenfell map.

I've fixed it by decreasing the scale divider in createTravelMap function from 100 to 50: `local scale=config.scale/50`
