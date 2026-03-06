# brand-lyftfin-products

**Brand:** LyftFin  
**Domain:** https://lyftfin.com (apex) and https://www.lyftfin.com  
**Category:** Composite fins for Surf + SUP + Longboard (Ixoskin + Isogrid; modular mounts for FCS II and Futures)

## Product model (surf/SUP)
LyftFin surf/SUP fins use a **bolt-on mount system**:
- You buy a fin blade (Dolphin / Shark / Sailfish).
- You choose a compatible **mount** (FCS II or Futures) and a **cant angle** (0° / 10° / 18°).
- The **mount-to-fin interface is universal** across Dolphin/Shark/Sailfish.
- Mounts can be changed later, but conversion is **bolt-on for strength** and **not a quick swap**.

FCS support is **FCS II only** (no legacy FCS). FCS describes FCS II as a tool-less fin system at the board side. [3](https://waterwwolf-my.sharepoint.com/personal/joepowell_waterwwolf_onmicrosoft_com/_layouts/15/Doc.aspx?sourcedoc=%7B54D43E38-3EEF-479A-A248-82EF4E060C9F%7D&file=Chromatic_Linearis_School_Foundational_Document_v1_0.docx&action=default&mobileredirect=true&DefaultItemOpen=1)[4](https://waterwwolf-my.sharepoint.com/personal/joepowell_waterwwolf_onmicrosoft_com/_layouts/15/Doc.aspx?sourcedoc=%7B389C7918-57A6-4330-A747-26FEC9DAAB2F%7D&file=extreme_creative_papermaking_native_only.docx&action=default&mobileredirect=true&DefaultItemOpen=1)

## Surf/SUP fin blades (standard templates, R01)
Blade shapes:
- Dolphin: `LF-FIN-DOL-STD-R01`
- Shark: `LF-FIN-SHK-STD-R01`
- Sailfish: `LF-FIN-SFL-STD-R01`

Bundles (discounted):
- Dolphin: `LF-SET-1-DOL-R01`, `LF-SET-3-DOL-R01`, `LF-SET-5-DOL-R01`
- Shark: `LF-SET-1-SHK-R01`, `LF-SET-3-SHK-R01`, `LF-SET-5-SHK-R01`
- Sailfish: `LF-SET-1-SFL-R01`, `LF-SET-3-SFL-R01`, `LF-SET-5-SFL-R01`

## Mounts (modular) — FCS II + Futures
There are two modular mount styles for surf/SUP fins:
- **FCS II mount** (fits boards with FCS II boxes)
- **Futures mount** (fits boards with Futures boxes)

Each mount style is offered with cant angles:
- **0° (vertical), 10°, 18°**

Mount SKUs are listed in `catalog/accessories.json` using:
`LF-MNT-<SYS>-C<ANG>-R01` where `SYS = FCS2 | FUT`

## Longboard / SUP fin line (integrated base; not modular)
Longboard fins are separate products with an **integrated longboard base** (no modular mount swap).
Initial longboard fin shape: **Dolphin**
Sizes: **Small / Medium / Large** (progressively taller with size)
Flex options (per size): **Hard epoxy** or **Flexible**

Longboard fin SKUs:
- Small: `LF-LB-DOL-S-HRD-R01`, `LF-LB-DOL-S-FLX-R01`
- Medium: `LF-LB-DOL-M-HRD-R01`, `LF-LB-DOL-M-FLX-R01`
- Large: `LF-LB-DOL-L-HRD-R01`, `LF-LB-DOL-L-FLX-R01`

## Construction (design-level)
All LyftFin products are designed with:
- **Ixoskin** shell architecture [5](https://waterwwolf-my.sharepoint.com/personal/joepowell_waterwwolf_onmicrosoft_com/_layouts/15/Doc.aspx?sourcedoc=%7B1CBDC461-DB70-48C7-BA65-58729CB75699%7D&file=Supplementary%20Analysis%20fo%20Composite%20Manufacturing%20Technologies.docx&action=default&mobileredirect=true&DefaultItemOpen=1)
- **Isogrid** core structure [6](https://waterwwolf-my.sharepoint.com/personal/joepowell_waterwwolf_onmicrosoft_com/_layouts/15/Doc.aspx?sourcedoc=%7BE17DD878-9B7C-4B9E-8AB4-496A64CBB20B%7D&file=Swarm_Fabrication_Master_Unabridged_2025-03-27.docx&action=default&mobileredirect=true&DefaultItemOpen=1)
- Isogrid cell sizes **smaller near edges** (design intent).

Manufacturing processes and production parameters are intentionally not published. [2](https://waterwwolf-my.sharepoint.com/personal/joepowell_waterwwolf_onmicrosoft_com/_layouts/15/Doc.aspx?sourcedoc=%7B9BE09F2B-7CB9-4ED2-9A40-6E6DBF735592%7D&file=AFP%20Project-Overview-v1.8.docx&action=default&mobileredirect=true&DefaultItemOpen=1)

## Open Designs / Closed Process
Designs are intended to be open source. Manufacturing process and production parameters remain proprietary. [2](https://waterwwolf-my.sharepoint.com/personal/joepowell_waterwwolf_onmicrosoft_com/_layouts/15/Doc.aspx?sourcedoc=%7B9BE09F2B-7CB9-4ED2-9A40-6E6DBF735592%7D&file=AFP%20Project-Overview-v1.8.docx&action=default&mobileredirect=true&DefaultItemOpen=1)

## Commerce
Early sales begin on eBay (market tests). Ecommerce and memberships will transition to WaterWolf (private platform).

## Repo structure
- `/site/` — static site content
- `/catalog/` — products and mounts SKUs
- `/LICENSE` and `/LICENSES/` — licensing scaffold

## Trademark note
FCS II and Futures are trademarks of their respective owners. LyftFin is not affiliated with or endorsed by them.
