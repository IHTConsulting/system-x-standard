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

## Size Table

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

Use Cases

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
// Install (npm example - hypothetical)
npm install system-x-dimensions

// Use in code
const systemX = require('system-x-dimensions');
console.log(systemX.X4); 
// { width: 680, height: 960, units: 'mm' }
```

### For Fabrication
```python
# Python example
from system_x import sizes

# Get X5 dimensions in mm
x5 = sizes.get('X5')
print(f"Cut sheet to: {x5.width}mm × {x5.height}mm")
# Output: Cut sheet to: 480mm × 680mm
```

---

## Documentation

- **[Full Technical Specification](specification.md)** – Complete system definition
- **[Use Cases & Examples](docs/use-cases.md)** – Real-world applications
- **[Comparison Guide](docs/comparison.md)** – System X vs other standards
- **[Implementation Guide](docs/implementation.md)** – Software setup instructions
- **[FAQ](docs/faq.md)** – Frequently asked questions

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

**Star this repo** ⭐ if you find System X useful!

---

*Last updated: December 2025 • Version 1.0*
