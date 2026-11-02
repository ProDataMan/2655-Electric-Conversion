# State-of-the-Art Marine Electric Motors for Planing Hull & Pontoon Conversions

**Date**: November 2026  
**Focus**: High continuous power (80-150+ kW class) suitable for planing a loaded ~26 ft Bayliner 2655 (~5,000-6,000+ lb) while retaining efficient low-speed displacement operation. Also relevant lower-power options for pontoons/party barges.

## Key Requirements for the 2655 Project

- Peak/continuous power high enough to plane a loaded planing hull (typically 80-150+ kW continuous or strong peak with good continuous rating).
- High torque at low RPM for acceleration onto plane.
- Water-cooled or efficient marine-rated cooling.
- Compatible with large LFP (or other high-cycle) battery banks (target 80-150+ kWh for dual-mode use).
- 350-800 V architectures preferred for efficiency and fast charging (CCS/shore).
- Reliability and serviceability for rental fleet use.
- Options: outboard (easier install/swap), inboard (adapted sterndrive or shaft), or pod.

## Leading High-Power Options

### Evoy (Norway)
- **Storm 300+**: 225 kW continuous / 450 kW peak, ~385 kg (outboard), 800 V architecture. Designed for 25-35 ft single or up to 40 ft twin. Liquid-cooled batteries (63/126/189 kWh options, ~3,000 cycles @ 70% DoD). Strong planing performance reported (e.g., Axopar examples >50 kt in testing; real-world range ~20-30 nm at planing speeds).
- **Breeze 120+**: 90 kW continuous / 137 kW peak, ~240 kg. More suitable for lighter or dual setups; also available as Gen 2 inboard. Batteries around 63 kWh class. Configurator prices previously indicated ~€40k for Breeze outboard / higher for Storm (batteries separate and significant).
- Strengths: Proven high-power outboards, good cooling, fast charging capability (up to 200 kW DC limited to 1C). Commercial and leisure use.
- Considerations: High cost; battery weight/volume significant; primarily outboard form factor.

### RAD Propulsion (UK)
- **RAD 40**: 40 kW continuous, 400 V, axial-flux, ~98-104 kg. Integrated ±90° steering. Recommended 20-61 kWh battery. Compact, low maintenance (closed-loop cooling). Available with Power Console battery packs (21/42 kWh).
- **RAD 120**: 120 kW continuous, 350-450 V, ~175 kg. Launched METS 2025; trials Q1 2026, expected availability late 2026. Large prop capability (up to 17"), integrated steering. Min recommended ~61 kWh, preferred 122+ kWh.
- Strengths: Axial-flux efficiency, compact form, integrated steering, commercial/defense focus with leisure applicability. Fast-charge compatible.
- Considerations: RAD 120 not yet widely available; twin RAD 40 could be a practical mid-power solution for the 2655.

### Bosch Engineering EDM 160
- Plug-and-play inboard system: 120 kW continuous / ~140 kW peak, ~180 kg total unit (motor + inverter + gearbox options + cooling + onboard charger).
- ~0.7 kW/kg density, up to 94% efficiency. Open seawater cooling. Compatible with various HV batteries. Cruise/maneuver modes, NMEA/CAN, limp-home.
- Strengths: Automotive-grade quality, integrated system (reduces integration complexity), suitable for sterndrive or shaft adaptation. Twin possible.
- Considerations: Relatively new marine product (2025 launch); battery separate.

### Vision Marine Technologies E-Motion 180E
- ~135 kW continuous (180 hp at propeller), high-voltage integrated outboard system. Purpose-built marine (IP67, glycol cooling).
- Strong pontoon presence: V24/V30 electric pontoons, P Powerpack for integration (43/86/129 kWh battery options). Range examples 40-90+ nm at low speeds depending on pack.
- Strengths: Proven on pontoons and planing boats; turnkey systems; commercial interest.
- Considerations: Primarily outboard; good match for both 2655 (single or twin considerations) and party barge.

### ePropulsion
- **X-Series Outboards**: X12 (12 kW), X20 (20 kW), X40 (40 kW) on 96 V eSSA platform. More economical for displacement or lighter planing/pontoon use.
- **POD Drive eSSA**: 12 kW / 20 kW pods (higher voltage). Adapter plates for saildrive mounts. Hydrogeneration capable.
- **Classic POD 6.0 EVO**: 6 kW used in the Swedish 2655 (dual setup). Excellent for pure displacement but insufficient for planing a 2655.
- Strengths: Mature ecosystem, batteries (G-Series), good support, scalable. Lower power density for planing needs.
- Note: Newer higher-power options emerging but still lag Evoy/RAD/Vision in continuous high-kW class.

### Helix (UK)
- **Pod Cartridge** range: Ultra-high power density radial-flux motors (e.g., 300 kW continuous from ~31 kg motor). Designed for compact pods with claimed 70% drag reduction vs traditional pods. Initial sizes 100/200/300 kW; scalable higher.
- Strengths: Extreme power density, potential for low-drag pods or compact inboards. F1/automotive heritage.
- Considerations: Emerging marine product (2025-2026); integration complexity for full pod system; more developmental for this timeline.

### Other Notes
- **ABB AMXE**: High-density water-cooled PMSM up to ~269 kW continuous. More industrial/commercial.
- **Torqeedo**: Exiting inboard/hybrid markets (2026 news); Deep Blue higher-power options less relevant going forward.
- DIY / adapted automotive motors: Possible but higher risk for marine reliability, cooling, sealing, and rental fleet duty.

## Recommendations for 2655 (Planing + Displacement)

| Priority | Option | Rationale | Rough Power Class |
|----------|--------|-----------|-------------------|
| High | Evoy Breeze 120+ or dual RAD 40 | Proven or near-term planing capability with manageable size; dual for redundancy/maneuverability | 90-120+ kW total |
| High | Bosch EDM 160 (single or twin) | Integrated inboard, good for sterndrive adaptation, automotive reliability | 120 kW |
| Medium | RAD 120 (when available) or Evoy Storm | Higher performance headroom | 120-225 kW |
| Medium | Vision Marine 180E | Strong outboard ecosystem, pontoon crossover | ~135 kW |
| Low (displacement-only) | Dual ePropulsion POD 6.0 or X20/X40 | Swedish precedent; quiet, efficient, but no planing | 12-40 kW |

**Battery strategy**: Target 80-150+ kWh LFP (or manufacturer packs) for dual-mode. Planing consumes heavily (~2-4+ kWh/nm); displacement is far more efficient (~0.5-1.5 kWh/nm). Solar for top-up. Fast DC charging preferred for rental turnaround.

**Installation notes**: Removing ~450 kg Mercruiser V8 creates significant weight budget for batteries. Pods free engine room; outboards simplify sterndrive removal. Retain or adapt sterndrive only if using high-power inboard.

## For Party Barge / Pontoon

Lower continuous power often sufficient (40-80 kW class for moderate speeds; higher for planing tri-toons). Vision Marine P Powerpack + 180E, ePropulsion X-Series, RAD 40, or dual lower-power units are strong candidates. Large deck area favors battery placement and solar.

---

*Sources include manufacturer sites, METS 2025 coverage (Plugboats, Powerboat News), Skippo/Praktiskt Båtägande on Swedish conversion, and industry reports (2024-2026). Prices and availability fluctuate; confirm current quotes.*
