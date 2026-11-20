# Zo Projects | Auto — agent memory

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
- Skip Holley **12-804** as permanent plan (was temp; 1–4 psi, inlet ≤7).
- Original electric pump found: **Edelbrock 17302** — 4–7 psi, 38 GPH, **5/16″ barbs**, officially **diesel-only**. Gas twin = **17301**.
- Path: carb-pressure pump → low-pressure dual-outlet reg (~**2.5–3 psi**) → dual bowls. Prefer native AN6 / ORB-06 where possible.
- Good pumps: Aeromotive **13222** (1.5–5 psi, dual ORB-06), Facet 40104/40106, ATL CFD-600-LP.
- Rejected: Evil Energy 75 psi deadhead. Evil Energy only with real bypass + return + reg.
- AN6 from 17302 barbs: Chase Bays / Pegasus clamp-on 5/16→-6, or short 5/16 rubber stubs + Amazon -6 male flare ↔ 5/16 barb jumpers (local stores don’t stock clamp-on).
- Mechanical pump: leave capped (NPT plugs) or block-off when electric is on.
- Rubber fuel lines refreshed; full AN6 redo later / bench then tuck.

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
