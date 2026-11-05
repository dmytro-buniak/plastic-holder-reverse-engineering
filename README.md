<div align="center">

# 🔧 Plastic Holder: Reverse Engineering

**A destroyed industrial part, measured by hand with a digital caliper, modelled in FreeCAD and 3D-printed as a working replacement.**

![FreeCAD](https://img.shields.io/badge/FreeCAD-1.1-C0392B?style=for-the-badge&logo=freecad&logoColor=white)
![Material](https://img.shields.io/badge/material-PLA%20carbon%20fibre-444?style=for-the-badge)
![Tolerances](https://img.shields.io/badge/tolerances-ISO%202768--m-1F3A5F?style=for-the-badge)
![Status](https://img.shields.io/badge/status-in%20use-2E8B57?style=for-the-badge)

<br>
<p float="left">
<img width="49%" height="75%" alt="original-vs-print" src="https://github.com/user-attachments/assets/254eebcd-1306-41c0-aa87-14d520a562c2" />
<img width="49%" height="45%" alt="side-view-ribs" src="https://github.com/user-attachments/assets/7f834946-2028-4365-86cb-b763d271a803" />
</p>







</div>

<!-- Photo tip: the original and the printed copy side by side, on a plain background, with the same orientation. -->

---

## 📌 The problem

A plastic holder on an industrial machine broke, and the original spare part is too expensive. The machine needed the part to keep running, so the part had to be recreated from the damaged original.

## 🧭 The method

| Step | What I did |
|---|---|
| 1. **Measure** | Measured the broken part with a digital caliper and marked every measurement point on a sketch. |
| 2. **Model** | Built a model in FreeCAD. |
| 3. **Draw** | Created a technical drawing in TechDraw with overall sizes, details of the small features and general tolerances to ISO 2768-m. |
| 4. **Print** | Printed the part in carbon-fibre-filled PLA and test-fitted it. |

From the first measurement to a printable model took about four hours.

## 📐 Technical drawing

<img width="1555" height="1099" alt="image" src="https://github.com/user-attachments/assets/3c02827c-0ac3-4f4b-a34e-58a4df2d21d7" />


The full-size PDF is in [`/drawings`](drawings/). It has:

- the front view, side view and an isometric view
- a profile view showing the angled wall
- detail views of the clips, the pin holes and the grip ribs
- dimensions taken directly from the caliper measurements

> All dimensions are in mm and were measured with a digital caliper. General tolerances follow ISO 2768-m.

## 🔩 Part at a glance

| | |
|---|---|
| Overall width | about 81 mm |
| Overall height | about 73 mm |
| Overall depth | about 35mm |
| Material | PLA with carbon fibre |
| Pin holes | Ø2.5 mm |
| Design tool | FreeCAD 1.1 (Part Design and TechDraw) |

**Features:** two snap clips with pin holes, a row of grip ribs on an angled wall, and chamfered bottom corners.

## 📁 Repository

```
.
├── cad/          FreeCAD source file (.FCStd)
├── drawings/     PDF technical drawing
├── stl/          print-ready files
```

<!-- Adjust the folder names to match what you upload. -->

## 🔎 Related projects

- [Spring-release key fob](https://github.com/dmytro-buniak/key-fob-spring-release): a mechanism designed from scratch, with assembly drawings
- [ESP32 handheld](https://github.com/dmytro-buniak/esp32-handheld): a 3D-printed enclosure around real electronics

---

<div align="center">

Made by [Dmytro Buniak](https://github.com/dmytro-buniak)

</div>
