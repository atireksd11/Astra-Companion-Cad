# Astra Companion — CAD (Half Life Week 2)

PETG chassis, head, and drive hardware for the two-wheeled desk robot. This repo is **mechanics only** for Hack Club Half Life **Tier 1** (~$30, 6 hours).

The main electronics repo (KiCad PCB, firmware) lives here:  
**https://github.com/atireksd11/Astra-Companion**

## Renders

| Front | Exploded |
|-------|----------|
| ![Front](docs/images/cad-front.png) | ![Exploded](docs/images/cad-exploded.png) |

| Stack with PCB | Wheels + caster |
|----------------|-----------------|
| ![PCB stack](docs/images/cad-pcb-stack.png) | ![Wheels](docs/images/cad-wheels.png) |

## Half Life import

This GitHub repo is tied to **Half Life project `cmv5b3v3d0hpu01n0r4f8wibl`** (Week 2 / Tier 1). The main PCB repo is a **different** Half Life project — that split stops sync from overwriting each other.

- Root **`BOM.csv`** — what Half Life mirrors (keep in sync with `hardware/bom-cad.csv`).
- **`hardware/bom-cad.csv`** — same parts list, easier path in docs.

Budget notes: [`hardware/BOM_CAD_SUMMARY.md`](hardware/BOM_CAD_SUMMARY.md).

Chassis write-up: [`docs/CAD.md`](docs/CAD.md).

## What's in the BOM

N20 gearmotors, 43 mm wheels, motor brackets, 12 mm ball caster, SG90 servo, M3 heat-set inserts and screws, PETG (pro-rated for ~300 g of prints). Motors connect to the **DRV8833** on the carrier PCB in the main repo.

## CAD source

- **Assembly STEP:** [`cad/astra-companion-chassis-assembly.step`](cad/astra-companion-chassis-assembly.step) (~6 MB, Fusion `micro_robot_assembly` export).
- **Renders:** `docs/images/cad-*.png` for Half Life screenshots.
