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

**Adobe InDesign:**
1. Download `templates/indesign/system-x-presets.indd`
2. Import page size presets: File > Document Presets > Define
3. Select System X size when creating new document

**Figma:**
1. Copy dimensions from `sizes/system-x.json`
2. Create custom frames: 680 × 960 (X4), 340 × 480 (X6), etc.
3. Use 5mm or 10mm layout grids

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
