# nascar-aero-slayer
# 🏁 Aero Drag Slayer - NASCAR High-Mount Wing Optimizer

**Live Demo**: [https://aero-drag-slayer.vercel.app](https://aero-drag-slayer.vercel.app)  
**🎥 Demo**: [20s Screen Record](demo.mp4)

## The Problem
NASCAR restrictor-plate racing = drag-limited passing. **5% Cd reduction = 0.3s/oval lap gain** at 190mph drafting.

## Baseline vs Optimized
| Metric | Baseline | Optimized | Gain |
|--------|----------|-----------|------|
| Cd @ 10° yaw | 0.85 | **0.80** | **5.9%** |
| Cl/Cd Ratio | 4.2 | **4.5** | +7% |
| Lap Delta (oval) | - | - | **0.31s** |

![Pressure Maps](screenshots/before-after-pressure.png)

## Tech Stack
- **CAD**: AutoCAD → STEP export
- **CFD**: SimScale k-ω SST (500k cells, 190mph + 10° yaw)
- **Validation**: BeamNG.drive dynamic aero overlay
- **Dashboard**: Streamlit + Plotly WebGL streamlines

## Engineering Workflow

