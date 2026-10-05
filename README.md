# Vertical Farm Controller Animal Intrusion Alarm

Build a smart agriculture prototype that uses water pump, capacitive soil sensor, pH sensor to detect and report animal movement. Include setup instructions, a circuit diagram, tested firmware, and sample output.

## Project details

| Field | Value |
| --- | --- |
| Roadmap ID | 178 |
| Category | Smart Agriculture |
| Platform | Arduino Mega |
| Difficulty | Intermediate |
| Estimated build time | 28 hours |
| Connectivity | Wi-Fi |
| Core components | water pump, capacitive soil sensor, pH sensor |
| Control mode | threshold alert |

## Repository layout

- `firmware/vertical-farm-controller-animal-intrusion-alarm/vertical-farm-controller-animal-intrusion-alarm.ino`: runnable firmware or application
- `docs/wiring.md`: suggested low-voltage wiring plan
- `docs/architecture.md`: system data flow
- `docs/test-plan.md`: repeatable verification steps
- `sample-data/example.json`: example telemetry record
- `tools/validate.py`: dependency-free repository validation

## Quick start

1. Open `firmware/vertical-farm-controller-animal-intrusion-alarm/vertical-farm-controller-animal-intrusion-alarm.ino` in Arduino IDE or Arduino CLI.
2. Select the board matching **Arduino Mega**.
3. Compile and upload, then open the serial monitor at 115200 baud.

## Expected behavior

Animal Intrusion Alarm demonstration with repeatable test steps. The default implementation supports simulated or generic analog inputs so the control path can be exercised before hardware-specific drivers are added.

## Hardware adaptation

The included code is a safe reference implementation. Update pin assignments and sensor conversions from the exact component datasheets, then repeat the test plan before connecting actuators.

## License

MIT
