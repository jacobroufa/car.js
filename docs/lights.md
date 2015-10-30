# Lights

Lights will take up to three points of data on a trigger event. A light’s `status` is `false` (light is off) by default, `true` if light is on. For `intensity` the light will be `low` (standard) or `high`, or 1-100 variable intensity if the light’s prototype supports it. A bulb’s `pattern` data is one of `solid` (default), `flash` for a rapid flash followed by a solid, `blink` for continuous interval blinking until a trigger says otherwise, or `blink-x` where `x` is a specific number of blinks.

```
{
  “status”: “false”,
  “intensity”: “low”,
  “pattern”: “solid”
}
```

A light trigger event will return true of the bulb exists and the operation can be performed, or false if the bulb is unavailable.

Calling a light trigger with a single boolean argument instead of the defined data object above will set the status and respect a light’s defaults.

### Exterior lights, grouped by intensity setting:

+ left/right head lights (high/low intensity) (default: low intensity)
+ left/right/center brake lights (high/low intensity) (default: high intensity, flash pattern)
+ left/right tail lights (variable intensity) (default: low intensity)
+ left/right rear turn signals (variable intensity) (default: blink pattern)
+ left/right front turn signals (low intensity only) (default: blink pattern)
+ left/right side turn signals (low intensity only) (default: blink pattern)
+ left/right daytime running lights (low intensity only)
+ left/right puddle lights (low intensity only)

### Interior lights, all variable intensity:

+ dash/gauges backlighting
+ map light
+ left/right visor lights
+ glove box light
+ left/right front footwell lights
+ dome light
+ left/right rear footwell lights
+ trunk light

