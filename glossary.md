# Glossary

Plain-language definitions for terms used in the checklist files, for a
first-time EV/Tesla owner. Scoped to what actually shows up in this
checklist — not a general EV encyclopedia (see README.md for scope).

**Frunk** — the front trunk. EVs have no engine up front, so that space
becomes extra storage.

**Monroney** — the federal window-sticker record of a car's as-built
configuration (options, wheels, color, etc.). Used at delivery to confirm
the car you're getting matches what you actually ordered.

**Supercharger** — Tesla's DC fast-charging network. Fastest way to charge
(significant range added in ~15–25 minutes), meant for road trips and
quick top-ups — not for routinely charging to 100%, which is harder on
battery health over time than slower charging (for non-LFP batteries —
see LFP below). See also Idle Fee / Congestion Fee below and the etiquette
items in `04-day-to-day.md`.

**Supercharger V2 / V3** — two generations of Supercharger hardware. V2
tops out at 150kW and has a thicker cable with a visible silver ring below
the connector. V3 (and newer) tops out at 250kW with a thinner,
liquid-cooled cable and no ring — spottable at a glance (see
`04-day-to-day.md`).

**Trip Planner** — a nav setting that automatically adds Supercharger (or
Destination Charger) stops to a route when needed to reach the
destination, factoring in driving style, elevation, weather, traffic, and
stall availability. Stops can be dragged/adjusted on the touchscreen
rather than accepted as-is (see `04-day-to-day.md`).

**Idle Fee** — a per-minute charge (roughly $0.50/min, doubling to
$1.00/min at a fully-occupied station) for leaving your car plugged into a
Supercharger after charging has finished, at a station that's 50%+
occupied. A 5-minute grace period applies before it kicks in. Tesla is
transitioning most sites to Congestion Fee instead (see below), but some
still use this older model.

**Congestion Fee** — the newer per-minute fee (roughly $0.50–$1.00/min,
varies by location) charged while still actively charging above ~80% at a
fully-occupied Supercharger site, since charging that last 20% is
intentionally slower and ties up the stall longer. Also has a 5-minute
grace period.

**LFP battery** — Lithium Iron Phosphate, one of two battery chemistries
Tesla uses (the other being NMC/nickel-based). Common on Standard Range
trims. Unlike NMC batteries, LFP is fine being charged to 100% regularly —
Tesla actually recommends doing so about once a week, for accurate
BMS/range calibration (see `04-day-to-day.md`). Check the Tesla app's
Charging screen to see which chemistry your car has.

**BMS (Battery Management System)** — the car's internal system for
monitoring and balancing battery cells and reporting range/charge level.
Occasionally needs a full charge to recalibrate its readings — how often
and to what percentage depends on battery chemistry (see LFP above).

**4680 / 2170 cells** — two individual battery cell formats Tesla uses
(the numbers are the cell's dimensions in mm — diameter x length). 2170
cells (from Panasonic) have been the standard for US-delivered Model Y and
have a faster Supercharger curve. 4680 cells are physically larger,
cheaper for Tesla to produce, and have a notably slower charging curve
(10-80% in 40+ min) — worse for the owner despite being cheaper for Tesla.
Reintroduced into some Model Y production in early 2026 as a
supply-chain/tariff hedge, though how widely this reaches US retail
deliveries is unconfirmed. Check on-screen rather than assume either way
(see `02-delivery-day.md`).

**Destination Charger** — a slower AC (Level 2) charger, usually installed
by hotels, businesses, or at home. Charges overnight rather than in
minutes; not built for a quick top-up the way a Supercharger is.

**J1772** — the standard plug used by most non-Tesla Level 2 chargers in
North America. Tesla's own charge port uses a different connector, so you
need the J1772 adapter (see `02-delivery-day.md`) to use non-Tesla
Level 2 stations.

**State of Charge (SOC)** — the battery's charge level as a percentage,
like a fuel gauge. Delivery cars often leave the factory around ~50% and
get topped up before handoff (see the Express Pickup note in
`02-delivery-day.md`).

**Sentry Mode** — records footage from the car's exterior cameras while
parked, to deter or document break-ins and vandalism. Needs a USB drive
plugged into the car (glovebox or center console) to save footage. Keeps
the car awake while active, which drains the 12V battery faster — set a
Sentry excluded location (a saved location, like home, where Sentry
automatically turns off) or use HomeLink to avoid running it overnight in
your own garage (see `04-day-to-day.md`).

**Phantom drain** — battery charge lost while the car sits parked, from
features that keep it awake or powered (Sentry Mode, Keep Accessory Power
On, Cabin Overheat Protection). See `04-day-to-day.md` for the settings
that reduce it.

**HomeLink** — lets the car trigger a paired garage door opener (or other
HomeLink-compatible device) automatically based on location, without a
separate remote.

**Dashcam** — the same camera system, recording continuously while
driving. Shares the same USB drive requirement as Sentry Mode.

**Park Assist** — camera-based system (Tesla Vision) that detects nearby
obstacles while parking or maneuvering at low speed and warns the driver.
Juniper-era Model Y uses cameras only — no ultrasonic sensors.

**Blind Spot Camera** — shows a camera view of the lane next to you when
you signal a turn or lane change, covering the blind spot your mirrors
miss.

**Firmware / OTA update** — the car's software. Tesla pushes updates
over-the-air (OTA), like a phone update, which can add features or fix
bugs after delivery — part of why an issue noticed at delivery might
improve later without a service visit (and also why some checklist items
are software-version dependent — see the flagged items in
`02-delivery-day.md`).

**One-pedal driving** — lifting off the accelerator applies regenerative
braking (regen) hard enough to slow and often fully stop the car, so the
physical brake pedal goes largely unused. Convenient, but see Brake Disk
Wiping below for a side effect.

**Hold mode** — the default (and often only) stopping behavior on newer
Teslas: lifting off the accelerator brings the car to a full stop and
holds it there, unlike a gas car's "creep" forward at idle (see
`04-day-to-day.md`).

**Creep** — a gas-automatic-like behavior (car rolls forward slowly at a
stop when you ease off the brake) that older Teslas offered as a setting
alongside Hold and Roll; newer builds have mostly dropped it in favor of
Hold-only.

**Preconditioning** — warming or cooling the cabin and/or battery before
driving, either on a schedule or by navigating to a Supercharger (which
warms the battery for faster charging). Best done while still plugged in,
since it draws grid power instead of battery charge (see
`04-day-to-day.md`).

**Wade Mode** — a Cybertruck-only feature that pressurizes the battery
pack to resist water intrusion during a deliberate water crossing. Model
Y has no equivalent (see `04-day-to-day.md`).

**Brake Disk Wiping** — a setting that periodically applies light,
imperceptible braking to keep the rotors dry and free of surface rust,
which can otherwise build up from one-pedal driving rarely putting the
pads in contact with the rotors (see `04-day-to-day.md`).

**Level 2 charger** — a 240V AC home or public charger, as opposed to a
standard 120V household outlet (Level 1). Level 2 adds roughly 25–30
miles of range per hour, making overnight charging practical. The Tesla
Wall Connector is a Level 2 charger; so are most public non-Supercharger
stations. Requires a dedicated 240V circuit installed by an electrician
(see `01-pre-delivery.md`).

**Wall Connector** — Tesla's own Level 2 home charger. Hardwired to a
dedicated 240V circuit. The Universal Wall Connector works with both
Tesla's connector and the J1772 standard, so it can charge non-Tesla EVs
too.

**Chill Mode** — a driving mode (Controls > Dynamics > Acceleration > Chill)
that significantly softens the car's throttle response and reduces the
instant-torque punch at launch. Useful on slick roads, when handing the
car to an unfamiliar driver, or any time the default acceleration feels
too aggressive.

**Slip Start** — a setting (Controls > Dynamics > Slip Start) that
temporarily disables traction control to let the wheels spin freely. Use
only when stuck in snow, ice, or mud; turn it back off once you're moving.

**Pet Mode** — a climate setting (fan icon > Pet Mode) that keeps the cabin
at a safe temperature while the car is parked unattended and displays a
message on the touchscreen reassuring passersby that the animal inside is
comfortable and the AC is running. Prevents well-meaning strangers from
breaking a window.

**Camp Mode** — a climate setting (fan icon > Camp Mode) that keeps climate
control, interior lighting, USB power, and air circulation running
overnight without the car going to sleep or the alarm triggering. Intended
for sleeping in the vehicle on road trips.

**NEMA 14-50 / NEMA 5-15** — two common household outlet types. NEMA
14-50 is a 240V/50A outlet (same as a large appliance or RV hookup) —
Tesla's Mobile Connector includes a 14-50 adapter for use where a Wall
Connector isn't installed. NEMA 5-15 is a standard 120V/15A household
outlet — functional but slow (Level 1), for emergencies or overnight
trickle charging only.
