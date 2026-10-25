<p align="center">
  <img src="assets/branding/hardware-header.png" alt="OhmLab Neuro N6 Hardware" width="100%">
</p>

<p align="center">
  Open hardware documentation, schematics, mechanical files, and product resources for the<br>
  <strong>OhmLab Neuro N6</strong> and <strong>Neuro Vision</strong> ecosystem.
</p>

<p align="center">
  <a href="https://neuron6.com"><strong>neuron6.com</strong></a>
  &nbsp;&bull;&nbsp;
  Estimated shipping: <strong>late October / early November</strong>
</p>

---

## Hardware status

All boards listed below are currently in production and have not yet shipped. Availability is planned for **late October / early November** from [store.neuron6.com](https://store.neuron6.com).

| Product | Part number | Revision | Production | Schematic | Datasheet | Shipping |
|:--|:--:|:--:|:--:|:--:|:--:|:--:|
| **Neuro N6** | `OL-DEV-N6-001` | **Rev C** | 🟢 In production | [Available](schematics/neuro-n6/Neuro-N6-Schematic-Rev-C.pdf) | [Rev E](datasheets/neuro-n6/Neuro-N6-Datasheet-Rev-E.pdf) | Not yet shipped |
| **Neuro Vision OV5640** | `OL-DEV-N6-002` | **Rev B** | 🟢 In production | [Available](schematics/neuro-vision-ov5640/Neuro-Vision-OV5640-Schematic-Rev-B.pdf) | [Rev D](datasheets/neuro-vision-ov5640/Neuro-Vision-OV5640-W-Datasheet-Rev-D.pdf) | Not yet shipped |
| **Neuro Vision OV5640-W** | `OL-DEV-N6-003` | **Rev B** | 🟢 In production | [Available](schematics/neuro-vision-ov5640-w/Neuro-Vision-OV5640-W-Schematic-Rev-B.pdf) | [Rev D](datasheets/neuro-vision-ov5640/Neuro-Vision-OV5640-W-Datasheet-Rev-D.pdf) | Not yet shipped |
| **Neuro Vision ST Cam** | `OL-DEV-N6-004` | **Rev B** | 🟢 In production | [Available](schematics/neuro-vision-st-cam/Neuro-Vision-ST-Cam-Schematic-Rev-B.pdf) | [Rev D](datasheets/neuro-vision-st-cam/Neuro-Vision-ST-Cam-Datasheet-Rev-D.pdf) | Not yet shipped |
| **Neuro Vision Thermal** | `OL-DEV-N6-005` | **Rev C** | 🟢 In production | [Available](schematics/neuro-vision-thermal/Neuro-Vision-Thermal-Schematic-Rev-C.pdf) | [Rev D](datasheets/neuro-vision-thermal/Neuro-Vision-Thermal-Datasheet-Rev-D.pdf) | Not yet shipped |
| **Neuro Vision TFT** | `OL-DEV-N6-006` | **Rev A** | 🟢 In production | [Available](schematics/neuro-vision-tft/Neuro-Vision-TFT-Schematic-Rev-A.pdf) | [Rev D](datasheets/neuro-vision-tft/Neuro-Vision-TFT-W-Datasheet-Rev-D.pdf) | Not yet shipped |
| **Neuro Vision TFT-W** | `OL-DEV-N6-007` | **Rev B** | 🟢 In production | [Available](schematics/neuro-vision-tft-w/Neuro-Vision-TFT-W-Schematic-Rev-B.pdf) | [Rev D](datasheets/neuro-vision-tft/Neuro-Vision-TFT-W-Datasheet-Rev-D.pdf) | Not yet shipped |
| **Neuro N6 Debug Adapter** | `OL-DEV-N6-010` | To be announced | 🟢 In production | To be announced | To be announced | Not yet shipped |
| **B-CAMS-IMX Adapter** | `OL-DEV-N6-011` | To be announced | 🟢 In production | To be announced | To be announced | Not yet shipped |

> Shipping dates are estimates and may change as production progresses.

The OV5640 and OV5640-W share one datasheet, as do the TFT and TFT-W. The Neuro N6 alpha datasheet in `legacy/` is kept for reference only and does not describe the current Rev C hardware.

## Product family

<table>
  <tr>
    <td align="center" width="20%"><img src="assets/boards/neuro-n6.png" alt="Neuro N6" width="150"><br><strong>Neuro N6</strong><br><sub>Rev C</sub></td>
    <td align="center" width="20%"><img src="assets/boards/ov5640.png" alt="Neuro Vision OV5640" width="150"><br><strong>OV5640</strong><br><sub>Rev B</sub></td>
    <td align="center" width="20%"><img src="assets/boards/ov5640-w.png" alt="Neuro Vision OV5640-W" width="150"><br><strong>OV5640-W</strong><br><sub>Rev B</sub></td>
    <td align="center" width="20%"><img src="assets/boards/st-cam.png" alt="Neuro Vision ST Cam" width="150"><br><strong>ST Cam</strong><br><sub>Rev B</sub></td>
    <td align="center" width="20%"><img src="assets/boards/thermal.png" alt="Neuro Vision Thermal" width="150"><br><strong>Thermal</strong><br><sub>Rev C</sub></td>
  </tr>
</table>

## Documentation

- **[Datasheets index](datasheets/README.md):** current datasheets for every board
- **[3D-printed case](3d-printed-case/):** upper and lower enclosure STL files
- **[Schematics index](schematics/README.md):** released schematics and revision notes
- **[Legacy Neuro N6 alpha datasheet](legacy/Neuro-N6-Datasheet-Alpha-01.pdf):** superseded documentation retained for reference

## Repository contents

```text
.
├── assets/
│   ├── boards/                  Product imagery
│   └── branding/                OhmLab branding and repository header
├── 3d-printed-case/
│   ├── Neuro-N6-Lower-Case.stl
│   └── Neuro-N6-Upper-Case.stl
├── datasheets/
│   ├── neuro-n6/                Neuro N6 datasheet
│   ├── neuro-vision-ov5640/     OV5640 and OV5640-W datasheet
│   ├── neuro-vision-st-cam/     ST Cam datasheet
│   ├── neuro-vision-thermal/    Thermal datasheet
│   └── neuro-vision-tft/        TFT and TFT-W datasheet
├── legacy/
│   └── Neuro-N6-Datasheet-Alpha-01.pdf
├── schematics/
│   ├── neuro-n6/
│   │   ├── Neuro-N6-Schematic-Rev-C.pdf
│   │   └── archive/             Earlier Neuro N6 schematic revisions
│   ├── neuro-vision-ov5640/     OV5640 schematic
│   ├── neuro-vision-ov5640-w/   OV5640-W schematic
│   ├── neuro-vision-st-cam/     ST Cam schematic
│   ├── neuro-vision-thermal/    Thermal schematic
│   ├── neuro-vision-tft/        TFT schematic
│   └── neuro-vision-tft-w/      TFT-W schematic
└── README.md
```

## Revision policy

Hardware revision and document revision are tracked independently. Always confirm that a schematic matches the revision printed on your PCB before using it for assembly, debugging, or repair. Superseded documents remain available under an `archive` directory and are clearly labelled.

## Availability

Boards will be available directly from **[OhmLab](https://store.neuron6.com)**. Watch this repository for schematic releases and documentation updates as production moves toward shipping.

---

<p align="center">
  <a href="https://neuron6.com"><img src="assets/branding/icon.png" alt="OhmLab" width="72"></a>
  <br><br>
  <img src="assets/branding/ohmlab.png" alt="OhmLab" width="220">
</p>

