# Lights

Lights will have three points of data associated with each. A light’s `status` is `false` (light is off) by default, `true` if light is on. For `intensity` the light will be `low` (standard) or `high`, or 1-100 variable intensity if the light’s prototype supports it. A bulb’s `bulb` data is `true` (default) if the light bulb exists and is operable, `false` if bulb is bad or missing.

```
{
  “status”: “false”,
  “intensity”: “low”,
  “bulb”: “true”
}
```

### Exterior lights, grouped by intensity setting:

+ left/right head lights (high/low intensity)
+ left/right/center brake lights (high/low intensity)
+ left/right tail lights (variable intensity)
+ left/right front turn signals (low intensity only)
+ left/right daytime running lights (low intensity only)
+ left/right side turn signals (low intensity only)
+ left/right puddle lights (low intensity only)
+ left/right rear turn signals (low intensity only)

### Interior lights, all variable intensity:

+ dash/gauges backlighting
+ map light
+ left/right visor lights
+ glove box light
+ left/right front footwell lights
+ dome light
+ left/right rear footwell lights
+ trunk light

