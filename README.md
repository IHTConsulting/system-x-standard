System X – Open Modular Dimensional Standard
System X: An open modular dimensional standard for paper, fabrication, and digital media based on exact halving and integer millimetre dimensions (X0–X9)

![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)
![Version](https://img.shields.io/badge/version-1.0-blue)
![Status](https://img.shields.io/badge/status-stable-green)

An open, freely usable dimensional standard for paper, fabrication materials, and digital media based on **exact halving** and **integer millimetre dimensions**.

---

## Overview

System X is a family of ten precisely defined sizes (X0 through X9) that prioritizes:

- **Integer millimetre dimensions** – no fractional arithmetic
- **Exact halving** – two Xn+1 sheets fit perfectly in one Xn sheet
- **Multiples of 5mm** – simplified division and mental calculation
- **Rational aspect ratios** – no dependence on √2 or other irrationals
- **Cross-domain applicability** – paper, screens, industrial fabrication

---

### Size Table

| Size | Width × Height (mm) | Area (m²) | Aspect Ratio |
|------|---------------------|-----------|--------------|
| **X0** | 2720 × 3840 | 10.44 | ~1.412 |
| **X1** | 1920 × 2720 | 5.22 | ~1.417 |
| **X2** | 1360 × 1920 | 2.61 | ~1.412 |
| **X3** | 960 × 1360 | 1.31 | ~1.417 |
| **X4** | 680 × 960 | 0.65 | ~1.412 |
| **X5** | 480 × 680 | 0.33 | ~1.417 |
| **X6** | 340 × 480 | 0.16 | ~1.412 |
| **X7** | 240 × 340 | 0.08 | ~1.417 |
| **X8** | 170 × 240 | 0.04 | ~1.412 |
| **X9** | 120 × 170 | 0.02 | ~1.417 |

All dimensions in **portrait orientation** (width × height).

---

### Use Cases

### Print & Publishing
- Magazine layouts with modular grids
- Poster series with consistent proportions
- Book formats with integer margins
- Educational materials for math teaching

### Industrial Fabrication
- CNC cutting with integer coordinates
- Laser cutting metal/plastic/wood sheets
- Textile cutting and pattern making
- Modular construction panels

### Digital Design
- Editorial grids for web/app design
- Image dimensions for print-digital workflows
- Screen layouts with rational proportions
- Custom canvas sizes for illustration

---

## Comparison with ISO 216

| Feature | System X | ISO 216 (A-series) |
|---------|----------|-------------------|
| Aspect ratio | ~1.41 (alternating) | 1:√2 (constant) |
| Dimensions | Integer mm | Irrational (rounded) |
| Mental calculation | Easy | Requires calculator |
| Halving property | Exact (0% waste) | Exact (theoretical) |
| Divisibility | Multiples of 5/10 | Arbitrary |

System X trades **constant aspect ratio** for **integer dimensions** and **arithmetic simplicity**.

---

## Quick Start

### For Designers
# System X – Design Software Setup Guide

## Adobe InDesign

### Manual Setup (Recommended)

**Create Document Presets:**

1. Open InDesign
2. Go to **File > Document Presets > Define...**
3. Click **New...**
4. Enter preset details:

**X4 Preset Example:**
- **Preset Name:** System X – X4
- **Intent:** Print
- **Number of Pages:** 1 (or as needed)
- **Width:** 680 mm
- **Height:** 960 mm
- **Orientation:** Portrait
- **Margins:** 40 mm (all sides) — or customize
- **Columns:** 4
- **Gutter:** 20 mm

5. Click **OK**, then repeat for other sizes (X0–X9)
6. To use: **File > New > Document**, select your System X preset

---

### All System X Presets (Copy These Values)

| Size | Width | Height | Suggested Margins | Columns | Gutter |
|------|-------|--------|-------------------|---------|--------|
| X0 | 2720 mm | 3840 mm | 80 mm | 6 | 40 mm |
| X1 | 1920 mm | 2720 mm | 60 mm | 5 | 30 mm |
| X2 | 1360 mm | 1920 mm | 50 mm | 4 | 20 mm |
| X3 | 960 mm | 1360 mm | 40 mm | 3 | 20 mm |
| X4 | 680 mm | 960 mm | 40 mm | 4 | 20 mm |
| X5 | 480 mm | 680 mm | 30 mm | 3 | 15 mm |
| X6 | 340 mm | 480 mm | 20 mm | 2 | 10 mm |
| X7 | 240 mm | 340 mm | 15 mm | 2 | 10 mm |
| X8 | 170 mm | 240 mm | 10 mm | 1 | — |
| X9 | 120 mm | 170 mm | 10 mm | 1 | — |

**Tips:**
- Set units to millimeters: **InDesign > Preferences > Units & Increments**
- Enable baseline grid: 5 mm or 10 mm increments
- Add bleed if printing: typically 3–5 mm

---

### Quick Custom Page Size

If you just need a one-off document:

1. **File > New > Document**
2. **Uncheck** "Primary Text Frame"
3. In **Width** field, type: `680 mm`
4. In **Height** field, type: `960 mm`
5. Adjust margins as needed
6. Click **Create**

---

## Figma

### Setup Custom Frames

**Method 1: Frame Tool**

1. Select **Frame tool** (F) or press `Ctrl/Cmd + G`
2. In the right panel, enter dimensions:
   - **W:** 680
   - **H:** 960
3. Set unit to **pixels** (Figma default) or scale for print:
   - At 96 DPI: 680 mm ≈ 2567 px
   - Or use mm values directly for concepts

**Method 2: Quick Frames**

Press **A** (Frame tool), then type in top toolbar:
- `680 × 960` → Creates X4 frame (in pixels)
- `340 × 480` → Creates X6 frame
- `170 × 240` → Creates X8 frame

---

### System X Frame Sizes for Figma

**In Pixels (assuming 1mm ≈ 3.78 px at 96 DPI):**

| Size | Pixels (approx 96 DPI) | Millimeters |
|------|------------------------|-------------|
| X0 | 10280 × 14515 | 2720 × 3840 |
| X1 | 7257 × 10280 | 1920 × 2720 |
| X2 | 5140 × 7257 | 1360 × 1920 |
| X3 | 3629 × 5140 | 960 × 1360 |
| X4 | 2571 × 3629 | 680 × 960 |
| X5 | 1814 × 2571 | 480 × 680 |
| X6 | 1285 × 1814 | 340 × 480 |
| X7 | 907 × 1285 | 240 × 340 |
| X8 | 643 × 907 | 170 × 240 |
| X9 | 454 × 643 | 120 × 170 |

**Or use actual mm values for print work:**

Simply enter mm dimensions directly:
- X4: `680 × 960`
- X6: `340 × 480`
- X8: `170 × 240`

Figma will interpret these as pixels, but the proportions remain correct.

---

### Layout Grids in Figma

**5mm Grid:**

1. Select your frame
2. In right panel, click **Layout grid** (+)
3. Click grid icon, choose **Grid**
4. Set **Size:** 5 (if working in ~px equivalent: 19 px)
5. Set **Color:** Light gray
6. Set **Opacity:** 20%

**10mm Grid:**

- Follow same steps
- Set **Size:** 10 (or 38 px at 96 DPI)

**Column Grid for X4 (680 × 960):**

1. Select frame
2. Add **Layout grid** (+)
3. Choose **Columns**
4. **Count:** 4
5. **Margin:** 40 (px or mm equivalent)
6. **Gutter:** 20
7. **Color:** Pink/Red (visible guide)

---

### Figma Components (Reusable Frames)

Create reusable frame components:

1. Draw a frame: **680 × 960** (X4)
2. Right-click → **Create Component** (or `Ctrl/Cmd + Alt + K`)
3. Name it: **"System X – X4"**
4. Repeat for X5, X6, X7, etc.
5. Store in a **System X Library** page
6. Use **Assets** panel to drag instances into new files

---

### Figma Plugins (Optional)

Search for these plugins to speed up workflow:
- **"Custom Page Sizes"** – Save and recall dimensions
- **"Grid Generator"** – Create complex modular grids
- **"Frame Sizer"** – Quickly resize multiple frames

---

## Adobe Illustrator

### Custom Artboard Sizes

1. **File > New**
2. Click **Print** tab (or Web/Mobile)
3. **Width:** 680 mm
4. **Height:** 960 mm
5. **Units:** Millimeters
6. **Orientation:** Portrait
7. Click **Create**

**To save as preset:**

1. Create document with System X size
2. **File > Document Setup**
3. **Edit Artboards** button
4. Set dimensions, then **Save Preset...**
5. Name: "System X – X4"

---

### Illustrator Grid Setup

1. **View > Show Grid**
2. **Illustrator > Preferences > Guides & Grid** (Mac) or **Edit > Preferences** (Win)
3. **Gridline every:** 10 mm
4. **Subdivisions:** 2 (creates 5 mm sub-grid)
5. **Grid style:** Lines or Dots
6. Click **OK**

Enable **Snap to Grid**: **View > Snap to Grid** (`Shift + Cmd + '`)

---

## Affinity Designer / Publisher

### Page Setup

1. **File > New**
2. **Type:** Print
3. **Page Width:** 680 mm
4. **Page Height:** 960 mm
5. **DPI:** 300 (for print)
6. **Orientation:** Portrait
7. **Margins:** 40 mm (or custom)
8. Click **Create**

**Save as Template:**

1. **File > Save As Template...**
2. Name: **System X – X4**
3. Store in Templates folder
4. Access via **File > New from Template**

---

### Affinity Grid

1. **View > Show Grid**
2. **View > Grid and Axis Manager...**
3. Set **Grid Spacing:** 5 mm or 10 mm
4. Enable **Snap to Grid**

---

## Sketch

### Artboard Setup

1. Press **A** (Insert Artboard)
2. In Inspector (right panel):
   - **Width:** 680
   - **Height:** 960
3. Name artboard: **System X – X4**

**Create Artboard Preset:**

1. Create artboard with System X dimensions
2. Right-click artboard → **Make Symbol** or **Create Shared Style**
3. Use **Insert > Artboard** and manually enter dimensions for future use

---

### Sketch Layout Settings

1. Select artboard
2. **View > Canvas > Layout Settings...**
3. **Total Width:** 680
4. **Columns:** 4
5. **Gutter:** 20
6. **Column Width:** Auto-calculated

---

## CSS / Web Design

For responsive web design using System X proportions:

```css
/* System X breakpoints (in pixels at 96 DPI) */
:root {
  --x9-width: 454px;   /* 120mm */
  --x8-width: 643px;   /* 170mm */
  --x7-width: 907px;   /* 240mm */
  --x6-width: 1285px;  /* 340mm */
  --x5-width: 1814px;  /* 480mm */
  --x4-width: 2571px;  /* 680mm */
}

/* Example media queries */
@media (min-width: 454px) { /* X9 */ }
@media (min-width: 643px) { /* X8 */ }
@media (min-width: 907px) { /* X7 */ }
@media (min-width: 1285px) { /* X6 */ }
```

---

## CAD Software (AutoCAD, Fusion 360)

### Drawing Setup

1. Start new drawing
2. Set **Units:** Millimeters
3. **Command:** `LIMITS`
4. **Lower-left corner:** 0,0
5. **Upper-right corner:** 680,960 (for X4)
6. **Command:** `ZOOM` → `A` (All)
7. Draw within these bounds

**Sheet Template:**

1. Create drawing with System X dimensions
2. Add title block
3. **File > Save As > Drawing Template (.dwt)**
4. Name: **SystemX_X4.dwt**

---

## Summary Table: Design Software Setup

| Software | Key Action | Dimensions Entry |
|----------|------------|------------------|
| **InDesign** | File > Document Presets > Define | Width: 680 mm, Height: 960 mm |
| **Figma** | Frame tool (F) | W: 680, H: 960 (or px equivalent) |
| **Illustrator** | File > New > Print tab | 680 mm × 960 mm |
| **Affinity** | File > New > Print | Page Width: 680 mm, Height: 960 mm |
| **Sketch** | Insert Artboard (A) | Width: 680, Height: 960 |
| **AutoCAD** | LIMITS command | Upper-right: 680,960 |

---

**Pro Tip:** Always set your document units to **millimeters** for consistency with System X specifications. For screen-based work, convert to pixels at your target DPI (typically 96 or 72).

### For Developers
```javascript
// Just use the dimensions directly - nothing to install!
const systemX = {
  X0: { width: 2720, height: 3840 },
  X1: { width: 1920, height: 2720 },
  X2: { width: 1360, height: 1920 },
  X3: { width: 960,  height: 1360 },
  X4: { width: 680,  height: 960  },
  X5: { width: 480,  height: 680  },
  X6: { width: 340,  height: 480  },
  X7: { width: 240,  height: 340  },
  X8: { width: 170,  height: 240  },
  X9: { width: 120,  height: 170  }
};

console.log(systemX.X4); 
// { width: 680, height: 960 }

// Set canvas size for X6
canvas.width = systemX.X6.width;
canvas.height = systemX.X6.height;
```

### For Fabrication
```python
# Copy these dimensions - no installation needed!
SYSTEM_X = {
    'X0': (2720, 3840),
    'X1': (1920, 2720),
    'X2': (1360, 1920),
    'X3': (960,  1360),
    'X4': (680,  960),
    'X5': (480,  680),
    'X6': (340,  480),
    'X7': (240,  340),
    'X8': (170,  240),
    'X9': (120,  170)
}

# Get X5 dimensions in mm
width, height = SYSTEM_X['X5']
print(f"Cut sheet to: {width}mm × {height}mm")
# Output: Cut sheet to: 480mm × 680mm

# Program your CNC
def cut_sheet(size):
    w, h = SYSTEM_X[size]
    return f"G1 X{w} Y{h}"
```

---

## 📄 License

**System X is released into the public domain** under the [CC0 1.0 Universal](LICENSE) license.

You are free to:
- ✅ Use System X commercially without attribution
- ✅ Modify and adapt for your needs
- ✅ Implement in software, tools, and products
- ✅ Redistribute freely
---

## Why System X?

> "In a world of irrational paper sizes, sometimes the most elegant solution is the one you can calculate in your head."

System X was created for:
- **Makers** who need integer coordinates for CNC/laser cutters
- **Educators** teaching proportions without calculator dependency
- **Designers** who want modular grids with clean math
- **Developers** building tools with predictable dimensions

If you value **simplicity**, **predictability**, and **mental arithmetic** over geometric purity, System X might be for you.

---

## Related Projects

- [ISO 216 on Wikipedia](https://en.wikipedia.org/wiki/ISO_216)
- [Paper Sizes Info](https://papersizes.io/)
- [The Modulor](https://en.wikipedia.org/wiki/Modulor) – Le Corbusier's proportional system
- [Golden Ratio in Design](https://www.goldennumber.net/)

---

**Star this repo** if you find System X useful!

---

*Last updated: December 2025 • Version 1.0*
