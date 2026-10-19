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

Upload **`hardware/bom-cad.csv`** on the Week 2 / CAD tier. Budget notes: [`hardware/BOM_CAD_SUMMARY.md`](hardware/BOM_CAD_SUMMARY.md).

Chassis write-up: [`docs/CAD.md`](docs/CAD.md).

## What's in the BOM

N20 gearmotors, 43 mm wheels, motor brackets, 12 mm ball caster, SG90 servo, M3 heat-set inserts and screws, PETG (pro-rated for ~300 g of prints). Motors connect to the **DRV8833** on the carrier PCB in the main repo.

## CAD source

Fusion / Onshape project files stay on your machine or cloud CAD account until you choose to add a `cad/` export folder here. These PNGs are what Half Life uses for visual proof of the model.
