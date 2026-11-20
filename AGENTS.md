# Zo Projects | Auto — agent memory

Agent name: **Inco**. If Enzo asks who you are on this project, answer **Inco**.

Locost Seven chassis **1442**. Owner: Enzo. Site/repo: `ebocc04/ZoProjectsAuto` (GitHub). SPA under `public/`. Live: GitHub Pages + local `127.0.0.1:7747`.

## Hard rules
- Paperwork / physical facts only. No inventing Lotus parts.
- Invoice prices: 2007–2011 only. Else “No receipt” / “No price”.
- Nested git is this repo only. Do not send parts to Trinity NAPA.
- PowerShell: no bash HEREDOC. Git identity via env when committing.
- GitHub is source of truth. Log data + push when asked.
- Do not commit unless Enzo asks. Do not invent SKUs.

## Powertrain / chassis facts
- Engine: MerCruiser **181** (Chevy 181 / 3.0-class).
- Gearbox: S10 **5-speed** (confirmed). Case SKU still unread — need case tag photo.
- Carbs: dual S&S **Super E / Super G**. Needle/float pressure ~**1.5–3.5 psi**.
- Flood history: sticky float ~2 mm; bowls replaced with **11-2388P** ×2 (full bowl assemblies). Missing accel-pump pin one carb + O-rings both — addressed at install.
- Overflow hose: **0.120″ ID × 0.250″ OD** (19-0262-S / 27369-76). Overflow ≠ bypass.
- Cover gasket: Fel-Pro **17900** cork — road-test dry / OK logged.
- Clutch: incomplete release (grind reverse + downshifts) — bleed/adjust first, not “air noise”.
- Throttle: return spring + free linkage (sticky return was mechanical).

## Fuel system (current redo)
- Schematic + HAVE/NEED: `public/fuel-an6-redo.html` (also SPA fuel diagram).
- Tank bung measured **1/4″ NPT** (thread OD ~13.70 mm). Old hard line OD ~8 mm ≈ **5/16″**. Top bung + dip tube to floor; 17302 gravity-fed → mount pump **below fuel level**, short primed inlet (siphon path).
- Electric pump: **Edelbrock 17302** — 4–7 psi, 38 GPH, **5/16″ barbs**, screw-on prefilter. Officially diesel-only; gas twin = **17301**. Chase Bays **5/16→-6** ×2 on pump.
- Hose: Evil Energy **PTFE** -6 kit (B0CQT1S1X8) — ethanol/E10 OK. Do **not** use CPE kit (not E10 rated).
- Path: tank **1/4 NPT→-6** → PTFE → Chase → 17302 → Chase → PTFE → **Evil Energy 10 µm** inline (−6 adapters) → firewall → **3/8 NPT→-6** → single-outlet **1–4 psi** reg (set ~**2.5–3**) → **3/8 NPT→-6** → PTFE → **-6 Y** → **-6→barb** + short rubber → Super E/G #7 (leave carb barbs).
- Size steps 1/4↔-6↔5/16 OK for this carb 181.
- Mechanical pump: cap/block when electric is on.
- Rejected: Evil Energy 75 psi deadhead; CPE nylon kit for pump gas.

## Spark / fire risk
- Cracked plug wire can arc to ground — fire risk with fuel vapor. Replace whole set.
- Stamp **GMC 907901** did not resolve as wires (Monroe strut). Closest store hit: Duralast **9079**. Match HEI vs EST + lengths for 181 (marine: Quicksilver 84-816761Q14 / Sierra 18-8833-1 for EST).

## Seats / body
- Budget seats: target ~18.5″ width; Amazon brown seats too wide. Prefer used Miata; skip $500 Cobras. Bare metal no. Cognac vinyl sheets discussed for upholstery DIY.

## Open / pending
- Bench AN6 fuel system with Edelbrock micro (or 17301) + low-psi dual reg.
- Cap/block mechanical pump on electric.
- Optional: clutch bleed, throttle spring check.
- Case tag photo for gearbox SKU.
- Do not buy kei / second gasket.
- Wait/log as needed; no L7 photos/print/gates-hose-id in site unless asked.

## Site conventions
- Workbook + `data.js` are source for logged facts.
- Carb flood / inlet callouts already filed (e.g. Fuel Inlet #7).
- Prefer logging real receipts and measured IDs over guesses.
