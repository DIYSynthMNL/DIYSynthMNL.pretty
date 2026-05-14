# DIYSynthMNL.pretty

KiCad footprint library used across the [DIYSynthMNL](https://github.com/DIYSynthMNL) Eurorack module projects.

Includes custom footprints for:

- Jacks: 3.5mm audio jacks with long pads for sturdy panel mounting
- Capacitors: rectangular electrolytics with oversized pads
- Diodes: 1N4148 / DO-41 with big pads, several pitches
- DIP IC sockets (DIP-8, DIP-14, DIP-18) with long pads
- Eurorack power: 16-pin IDC, 10-pin IDC with big pads
- Mounting: M3 mounting hole for Eurorack panels
- LEDs: 5mm with big pads
- Handmade vactrols: 5mm LED + LDR enclosure
- Audio transformer (Bourns TL016-R)

## Usage

Clone this repo into a stable location (not your Downloads folder):

```sh
git clone https://github.com/DIYSynthMNL/DIYSynthMNL.pretty.git ~/kicad-libs/DIYSynthMNL.pretty
```

Then add it to KiCad's footprint table:

1. **Preferences** → **Manage Footprint Libraries**
2. Click **Add existing library to table** (the folder icon)
3. Browse to the cloned `.pretty` folder and select it
4. Confirm — KiCad will use the folder name (`DIYSynthMNL`) as the library nickname

The footprints will then be available in any KiCad project's PCB editor.

## License

See [LICENSE](LICENSE).
