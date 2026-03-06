# LyftFin SKU Matrix (R01)

This matrix is the human-readable index for SKUs defined in:
- `catalog/products.json`
- `catalog/accessories.json`

## Key rules (final)
1) Surf/SUP fin blades are universal at the mount interface: Dolphin / Shark / Sailfish all bolt to the same LyftFin mount interface.
2) Mount type determines board system compatibility: **FCS II** or **Futures**.
3) Mount type also determines cant: **0° (vertical)**, **10°**, **18°**.
4) Longboard/SUP fins have an **integrated longboard base** (no modular mount) and are Dolphin-only in **S/M/L** with **Hard/Flexible** per size.

---

## A) Surf/SUP fin blades (standard templates, R01)

| Shape | SKU | Notes |
|------|-----|------|
| Dolphin | `LF-FIN-DOL-STD-R01` | Standard fin blade |
| Shark | `LF-FIN-SHK-STD-R01` | Standard fin blade |
| Sailfish | `LF-FIN-SFL-STD-R01` | Standard fin blade |

**Construction (design-level):** Ixoskin shell + Isogrid core (smaller isogrid cells near edges).

---

## B) Discount bundles (R01)

Bundles are blade-only counts; mounts are selected per fin at purchase.

| Bundle | Dolphin | Shark | Sailfish |
|--------|---------|-------|----------|
| Single | `LF-SET-1-DOL-R01` | `LF-SET-1-SHK-R01` | `LF-SET-1-SFL-R01` |
| Thruster (3) | `LF-SET-3-DOL-R01` | `LF-SET-3-SHK-R01` | `LF-SET-3-SFL-R01` |
| 5-Fin Set | `LF-SET-5-DOL-R01` | `LF-SET-5-SHK-R01` | `LF-SET-5-SFL-R01` |

---

## C) Modular mounts (Surf/SUP) — FCS II vs Futures (R01)

Mount interface to fins is universal; the only differences are:
- Board system: **FCS II** or **Futures**
- Cant: **0° / 10° / 18°**

### C1) FCS II mounts
| Cant | SKU |
|------|-----|
| 0° (Vertical) | `LF-MNT-FCS2-C00-R01` |
| 10° | `LF-MNT-FCS2-C10-R01` |
| 18° | `LF-MNT-FCS2-C18-R01` |

### C2) Futures mounts
| Cant | SKU |
|------|-----|
| 0° (Vertical) | `LF-MNT-FUT-C00-R01` |
| 10° | `LF-MNT-FUT-C10-R01` |
| 18° | `LF-MNT-FUT-C18-R01` |

**Mount conversion note:** Mounts bolt to the fin for strength. Conversion is not a quick swap.

---

## D) Longboard / SUP fins (integrated base; Dolphin only)

Longboard/SUP fins are separate products with integrated longboard bases (no modular mounts).

| Size | Flex | SKU |
|------|------|-----|
| S | Hard | `LF-LB-DOL-S-HRD-R01` |
| S | Flexible | `LF-LB-DOL-S-FLX-R01` |
| M | Hard | `LF-LB-DOL-M-HRD-R01` |
| M | Flexible | `LF-LB-DOL-M-FLX-R01` |
| L | Hard | `LF-LB-DOL-L-HRD-R01` |
| L | Flexible | `LF-LB-DOL-L-FLX-R01` |

**Size scaling:** fin height increases from S → M → L.

---

## E) R&D / concept item
| Item | SKU | Status |
|------|-----|--------|
| Rail-lift micro-foil concept | `LF-AUX-HF-001` | Concept (not finalized) |

---

## F) SKU prefixes (legend)
- `LF-FIN-...` = Surf/SUP fin blade
- `LF-SET-...` = Bundle (count of blades)
- `LF-MNT-...` = Modular mount (FCS II or Futures + cant)
- `LF-LB-...` = Longboard/SUP fin (integrated base)
- `LF-AUX-...` = Optional / R&D concept
