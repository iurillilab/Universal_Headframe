# Universal\_Headframe ─ Accessories Library 
Welcome!  This repository collects every **Accessories** we currently use or test at IIT Rovereto.  Each model comes as a STEP file (`.step`) ready for CAM / 3‑axis milling, direct metal‑AM printing, or SLA 3D printin, plus a PNG preview so you can eyeball the geometry before downloading CAD.

> **TL;DR**  • All files are **metric** (ISO M‑series screws, millimetres).

---

## How this README is organised

| Section                                 | What you’ll find                              |
| --------------------------------------- | --------------------------------------------- |
| [Quick chooser](#quick-chooser-table)   | one‑line guide to pick the right plate        |
| [Fabrication notes](#fabrication-notes) | tips for CNC vs SLM printing                  |

---

## Quick chooser table

| File name                    | Preview                                           | Mass\* | Aperture Ø | Typical use‑case                                                         |
| ---------------------------- | ------------------------------------------------- | ------ | ---------- | ------------------------------------------------------------------------ |
| `0160-073-01_FR.step`        |<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/20e613a6-1551-495d-99be-24074df01efd" />| xx g | x mm       | **Allen institute lineage** 	Cone for 2P|
| `Stamp_tool_SH_FR.step`|<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/d0ac0edf-2456-4354-9aa9-0d79c8c84b49" />| xx  g | x mm       | **Allen institute lineage** 	[SHIELD]( https://cad.onshape.com/publications/a9da3d5bea6057b1de9dcbe4/w/e8fb183696b8dd84a43603fb/e/8e9294519ca4564a8390c596?renderMode=0&leftPanel=false&uiState=687e53a48cc3d5295ef9be1f ) stamp tool for creating impression of implant (0251-160-01) in putty during coating process|
| `DHC Stamp Tool_Stamp_tool_DH_FR.step`|<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/3ecd9ac8-04aa-446b-b253-25f46d9e0356" />| xx g | x mm        |**Allen institute lineage**	[SHIELD]( https://cad.onshape.com/publications/a9da3d5bea6057b1de9dcbe4/w/e8fb183696b8dd84a43603fb/e/8e9294519ca4564a8390c596?renderMode=0&leftPanel=false&uiState=687e53a48cc3d5295ef9be1f ) Dual Hemisphere Implant stamp tool for creating impression of implant (0274-100-22) in putty during coating process |
| `AH_USSEnterprise_cone_FR.step`|<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/69788197-ef33-473d-af85-80593c9403bf" />| xx g | x mm        | **Skull‑contoured** cone for WFI compatible with AH_USSEnterprise_FR Headplate |
| `AH_USSEnterprise_cover.step`|<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/01f281ae-5c43-4015-b1a3-6a12e42c780a" />| xx g | x mm       |**Skull‑contoured** screwable open cover for the cone       			           |
| `Luigi_cone.step`|<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/4102c793-59dc-4f1c-ae96-98d3bcd61f12" />| xx g | x mm       |Luigi Headplate variant cone for Ephys|
<sub>\*Mass values are printed Ti‑TC4 as measured on a 0.1 mg balance</sub>

---

## Fabrication notes

* **3‑D printing (SLM)** – upload to JLC3DP or similar; choose **Ti‑TC4** and "high precision" option if offered.
* **CNC milling** – water‑jet or laser‑cut 1.6 mm Ti sheet, then finish on 3‑axis mill;
* **3-D printing  (SLA)** - Used a Form 2 for parts that does not endure loads.

---


### Contributing

Pull requests welcome—open an issue if you have a new variant or measurement data to share.

### License

CERN-OHL-P-2.0 license.
