# Open-Source ReRAM Fabrication

## Executive Summary
This whitepaper presents a low-cost, garage-scale method for producing resistive random-access memory (ReRAM) using printable metal-oxide materials and simple deposition techniques. The approach is compatible with domestic microfabrication and provides a path toward high-temperature, non-volatile memory production for embedded systems and secure electronics.

## Motivation
Modern computing relies on memory systems that are fragile, proprietary, and centralized. ReRAM offers a scalable, low-power, and non-volatile alternative that is well-suited to harsh environments and small-scale fabrication. With advances in printable electronics and low-cost tools like UV laser engravers and spin coaters, fabrication is now accessible to small labs and individuals.

## Basic Cell Architecture
A ReRAM cell consists of:
- **Bottom Electrode**: Conductive layer (e.g., graphite, TiN, or aluminum)
- **Switching Layer**: Metal oxide such as TiO2, HfO2, or doped perovskites
- **Top Electrode**: Conductive metal (e.g., aluminum, silver, or platinum)

Memory state is defined by the resistance across the oxide, modulated by the formation and rupture of conductive filaments.
## Fabrication Method
### Materials:
- Substrate: Alumina ceramic, glass, or FR4 with Cu
- Bottom Electrode: Graphite ink or sputtered metal
- Switching Layer: Sol-gel TiO2 or HfO2 precursor
- Top Electrode: Printable conductive ink or sputtered aluminum

### Tools:
- Spin coater or blade coater
- Hotplate or kiln (200–500°C)
- UV or IR laser for patterning
- Photolithography setup (optional)
- Precision probe station for testing

### Process:
1. **Prepare Substrate**: Clean and optionally pattern the bottom electrode
2. **Deposit Oxide**: Spin-coat or stencil-print the oxide layer
3. **Bake**: Anneal to form crystalline oxide (400–500°C typical)
4. **Apply Top Electrode**: Pattern metal contacts via mask or laser
5. **Laser Trim/Test**: Program or test via microprobe

## Performance and Scaling
- **Bit Size**: ~25–50 μm achievable with low-cost lasers; ~800 nm with photolithography
- **Operating Voltage**: 1–5 V (write), <1 V (read)
- **Endurance**: >10^5 cycles (estimate)
- **Retention**: 10+ years, up to 600°C (material-dependent)

## Applications
- Secure embedded systems
- Harsh environment computing (space, automotive, defense)
- Local cache/storage for open-source chips

## Cost Estimate
- **Material Cost/wafer** (5" x 5"): <$10
- **Bit Yield** (at 25 μm pitch): ~400,000 bits/wafer
- **Unit Cost**: ~$0.000025/bit (excluding packaging)

## Next Steps
- Characterize endurance vs. oxide thickness
- Develop DIP/SOIC wirebonding integration
- Explore multi-layer stacks for vertical scaling
- Investigate BEOL integration with logic

## Conclusion
ReRAM fabrication using garage-scale tools is viable and strategically important. It enables local, secure memory production and advances the broader goal of small-scale, open semiconductor manufacturing.
