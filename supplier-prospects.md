# Supplier Prospect List — Tolerance Supply

Target manufacturers to pitch for a dealer/distribution relationship, organized by the
4 categories on the site. Not on the storefront — Shop by Brand stays empty placeholder
slots until an actual agreement exists (see [homepage build notes]).

Approach: most of these run formal reseller/dealer programs — look for "Become a Dealer"
/ "Reseller Program" / "Partners" on their site rather than a generic sales inbox.

## 3D Printing
- **Prusa Research** (prusa3d.com) — FDM, strong maker/education reputation
- **Bambu Lab** (bambulab.com) — fast-growing, high consumer/prosumer demand right now
- **Creality** (creality.com) — high-volume budget/mid-tier, huge SKU range
- **Elegoo** (elegoo.com) — resin printing (SLA/MSLA) leader, complements FDM lineup

## CNC Machines
- **Carbide 3D** (carbide3d.com) — Shapeoko line, strong maker/small-shop fit
- **Onefinity** (onefinitycnc.com) — benchtop/desktop CNC, community-driven brand
- **SainSmart** (sainsmart.com) — budget CNC + laser crossover, good entry-tier fit

## Laser Systems
- **xTool** (xtool.com) — diode + CO2, strong maker/small-business focus
- **Glowforge** (glowforge.com) — premium consumer/prosumer, high brand recognition
- **OMTech** (omtechlaser.com) — CO2 laser cutters, wider power range for shops

## Test & Measurement
- **Fluke** (fluke.com) — industry-standard multimeters, strong trust signal alone
- **Rigol** (rigolna.com) — oscilloscopes, well-regarded price/performance for the bench
- **Siglent** (siglentna.com) — oscilloscopes + signal generators, education-market friendly

## Notes
- Education/STEM angle (per site copy: "Classroom & Lab Ready") is a real differentiator worth
  leading with — several of these brands (Prusa, Fluke, Rigol) have existing education program
  pricing that could pair with a dealer conversation.
- Once even 1–2 of these confirm, update `shopify/templates/index.json` → `shop_by_brand` blocks
  with real logos, and drop the "added once supplier agreements are confirmed" note in
  `sections/ts-brand-wall.liquid`.
