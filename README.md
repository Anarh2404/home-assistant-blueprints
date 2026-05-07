# Home Assistant Blueprints

Personal Home Assistant blueprints.

## Automation blueprints

- `automation/external_humidity_humidifier.yaml` - controls a humidifier using an external humidity sensor with hysteresis and can skip turn-on commands when an optional tank-empty sensor is on.

## Import

Use the raw GitHub URL for the blueprint file in Home Assistant:

```text
https://raw.githubusercontent.com/<owner>/<repo>/main/automation/external_humidity_humidifier.yaml
```

After importing, create one automation per room/device and select the room humidity sensor, humidifier entity, humidity thresholds, and optionally a tank-empty binary sensor.
