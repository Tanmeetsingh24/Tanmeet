# Bone strain gauge (FlexiForce)

Arduino sketch for an **A301-25 FlexiForce** sensor on analogue pin A0, with a 10 kΩ pulldown. Readings are streamed over serial in a PLX-DAQ-style format so they can be logged and plotted in Excel.

This is a **lab/measurement** project: collect force-sensor data to inform how a support might be loaded. It is not a medical device and was not used to treat injuries.

## Hardware

- Arduino
- Tekscan A301-25 FlexiForce sensor
- 10 kΩ pulldown to analogue input A0

## Files

| File | Role |
| --- | --- |
| `force_sensor.ino` | Serial acquisition and coarse pressure bands (no pressure → heavy squeeze) |
| `Data_V5(N).xlsm` | Logged data / spreadsheet |
| `Data_Graph.png` | Example plot from collected readings |

![Example force readings](Data_Graph.png)
