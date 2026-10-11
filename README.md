# STEP400 r2

Hardware development repository for the next revision (r2) of [STEP400](https://ponoor.com/en/docs/step-series/), a 4-axis stepper motor driver board with an Ethernet interface by Ponoor Experiments Inc.

> **Status: in development.** The design in this repository is not finished and has not been manufactured. For the current product (r1), see [ponoor/STEP400](https://github.com/ponoor/STEP400).

## Repository layout

| Path | Contents |
|---|---|
| [`hardware/step400/`](hardware/step400/) | KiCad project for the main board |
| [`hardware/lib/`](hardware/lib/) | Shared KiCad library (`step_series`): symbols, footprints, 3D models, design blocks |
| [`firmware/`](firmware/) | Firmware for hardware inspection |
| [`tools/`](tools/) | PC-side test tools and scripts |
| [`mechanical/`](mechanical/) | Dimension drawings and 3D data for fixtures |
| [`production/`](production/) | Manufacturing data for each released revision |
| [`docs/`](docs/) | Design notes and datasheet links |

Additional boards, such as a test fixture, will be added as separate KiCad projects under `hardware/`.

## Tools

- [KiCad](https://www.kicad.org/) 10

## Related repositories

- [ponoor/STEP400](https://github.com/ponoor/STEP400): STEP400 r1 design files (EAGLE) and configuration tool
- [ponoor/step-series-universal-firmware](https://github.com/ponoor/step-series-universal-firmware): firmware for the STEP series
- [STEP series documentation](https://ponoor.com/en/docs/step-series/)

## License

[MIT License](LICENSE) © Ponoor Experiments Inc.
