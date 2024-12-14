# mw-travel-tooltips

My edit allows to keep destination tooltips small, so that they appear below the mouse pointer, but at the same time it doesn't decrease the Vvardenfell map so much.

I've fixed it by decreasing the scale divider in createTravelMap function from 100 to 50: `local scale=config.scale/50`
