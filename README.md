<div align="center">

# 🔧 Plastic Holder: Reverse Engineering

**A destroyed industrial part, measured by hand with a digital caliper, modelled in FreeCAD and 3D-printed as a working replacement.**

![FreeCAD](https://img.shields.io/badge/FreeCAD-1.1-C0392B?style=for-the-badge&logo=freecad&logoColor=white)
![Material](https://img.shields.io/badge/material-PLA%20carbon%20fibre-444?style=for-the-badge)
![Tolerances](https://img.shields.io/badge/tolerances-ISO%202768--m-1F3A5F?style=for-the-badge)
![Status](https://img.shields.io/badge/status-in%20use-2E8B57?style=for-the-badge)

<br>

<img src="docs/original-vs-print.jpg" alt="Original part next to the 3D-printed replacement" width="80%">

</div>

<!-- Photo tip: the original and the printed copy side by side, on a plain background, with the same orientation. -->

---

## 📌 The problem

A plastic holder on an industrial machine broke, and there was no drawing, no CAD model and no spare part to order. The machine needed the part to keep running, so the part had to be recreated from the damaged original.

## 🧭 The method

| Step | What I did |
|---|---|
| 1. **Measure** | Measured the broken part with a digital caliper and marked every measurement point on a sketch. |
| 2. **Model** | Built a parametric model in FreeCAD, so a wrong measurement can be corrected in one place and the rest updates. |
| 3. **Draw** | Created a technical drawing in TechDraw with overall sizes, details of the small features and general tolerances to ISO 2768-m. |
| 4. **Print** | Printed the part in carbon-fibre-filled PLA and test-fitted it. |
| 5. **Use** | The printed replacement went into production. |

From the first measurement to a printable model took about three hours.

## 📐 Technical drawing

<img src="docs/drawing-preview.png" alt="Technical drawing of the plastic holder" width="100%">

The full-size PDF is in [`/drawings`](drawings/). It has:

- the front view, side view and an isometric view
- a profile view showing the angled wall
- detail views of the clips, the pin holes and the grip ribs
- dimensions taken directly from the caliper measurements

> All dimensions are in mm and were measured with a digital caliper. General tolerances follow ISO 2768-m. <!-- TODO: list the 2 or 3 critical fits, with their tolerance, e.g. clip width ±0.1 -->

## 🔩 Part at a glance

| | |
|---|---|
| Overall width | about 81 mm |
| Overall height | about 73 mm |
| Overall depth | <!-- TODO --> mm |
| Material | PLA with carbon fibre |
| Pin holes | Ø2.5 mm |
| Design tool | FreeCAD 1.1 (Part Design and TechDraw) |
| Printer and settings | <!-- TODO: printer, layer height, walls, infill, orientation --> |

**Features:** a large circular opening, two snap clips with pin holes, a row of grip ribs on an angled wall, and chamfered bottom corners.

## 📁 Repository

```
.
├── cad/          FreeCAD source file (.FCStd)
├── drawings/     PDF technical drawing
├── stl/          print-ready files
└── docs/         photos and images
```

<!-- Adjust the folder names to match what you upload. -->

## 🧠 What I learned

<!-- TODO: 3 to 5 sentences in your own words. Prompts:
     - What was hardest to measure with a caliper (angles, curves, the ribs)?
     - What did you have to adjust after the first print?
     - What would you do differently next time (a scanner, a template, a better tolerance plan)? -->

## 🔎 Related projects

- [Spring-release key fob](https://github.com/dmytro-buniak/key-fob-spring-release): a mechanism designed from scratch, with assembly drawings
- [ESP32 handheld](https://github.com/dmytro-buniak/esp32-handheld): a 3D-printed enclosure around real electronics

## 📄 License

<!-- TODO: choose one, for example CC BY 4.0 for the design files. -->

---

<div align="center">

Made by [Dmytro Buniak](https://github.com/dmytro-buniak)

</div>
