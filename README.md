# CARDAMO - Research Showcase Website

**ML-Driven Smart Cardamom Cultivation Management System**  
*Undergraduate Research Project*  

---

## 🌿 Overview
This repository contains the official academic showcase web portal for the **Cardamo** research project. Built strictly in accordance with your lecturer's requirements using **100% Pure HTML and CSS only** (zero JavaScript, zero framework dependencies, zero build steps), ensuring instant rendering, maximum portability, and universal browser compatibility.

---

## 🎯 Research Scope & Architecture
Cardamo addresses the 25%–40% seasonal crop losses faced by small and medium-scale cardamom farmers in the central highlands of Sri Lanka (Kandy, Badulla, Matale).

### Four Core Sub-Objectives:
1. **Cardamom Leaf Disease Detection through Images** — *K.J.M.D.Imasha (IT22097460)*
   - Detects 5 prevalent local diseases: Leaf Blight, Leaf Spot, Mosaic Disease, Chlorotic Streak, and Vein Clearing.
2. **Smart Pod Monitoring and Caring System** — *Dissanayake K.S.S. (IT22223180)*
   - Dual maturity verification and YOLO-based Capsule Borer damage localization.
3. **Market Prediction and Harvest Analysis** — *D.I.Delpechithra (IT22228758)*
   - Quantity-parameterized price forecasting and seasonal auction movement analytics.
4. **Cardamom Pod Quality Grading** — *Kulasooriya K.S.D (IT22158840)*
   - Colorimetric RGB/HSV analysis, pod diameter calculation, YOLOv10 defect identification, and batch grading mapped to Department of Export Agriculture (DOA) & EDB standards.

---

## 👥 Supervision Panel
- **Supervisor:** Ms. Jenny Krishara (*Faculty of Computing, SLIIT*)
- **Co-Supervisor:** Dr. Dinuka Wijendra (*Faculty of Computing, SLIIT*)

---

## 📁 Directory Structure
```
cardamo-showcase-web/
├── index.html                   # 100% Pure HTML5 semantic showcase portal
├── css/
│   └── style.css                # 100% Pure CSS design system (pure CSS tabs & responsive menu)
├── assets/
│   ├── images/                  # Real project mockups, badges, and background graphics
│   └── docs/                    # Approved PDF documents (Topic Assessment & Research Paper)
└── README.md
```

---

## 💡 Pure HTML & CSS Interactive Features (Zero JS)
- **Responsive Mobile Navigation:** Implemented using standard CSS `:checked` checkbox selector technique.
- **Module Showcase Tabs:** Implemented using CSS radio inputs (`input[type="radio"]:checked`) and sibling selectors.
- **Smooth Navigation Scrolling:** Handled natively by CSS `scroll-behavior: smooth`.
- **Direct Deliverable Downloads:** Direct semantic `<a download>` links.
- **Semantic Contact Form:** Standard HTML form submission without JavaScript handlers.

---

## 🚀 How to Run Locally

### Option 1: Double-Click
Simply open `index.html` in any modern web browser (Google Chrome, Microsoft Edge, Firefox, Safari).

### Option 2: Local HTTP Server (Python)
```bash
# In this directory:
python -m http.server 8085
```
Then navigate to: `http://localhost:8085`

---

## 📑 Included Deliverables
- [Topic Assessment Form V2.1](assets/docs/topic-assessment.pdf) *(Approved with minor changes, Jan 2026)*
- [Academic Research Paper](assets/docs/cardamo-research-paper.pdf)
