# Stick Test Chamber

`v1.3.0`

A ragdoll physics sandbox that runs entirely in the browser — no build step, no
dependencies, one self-contained HTML file.

**Play it:** https://aussiescupper.github.io/stick-test-chamber/

Spawn any of 25 objects — bowling balls, anvils, saw blades, spears, TNT, rockets,
fans, magnets, turrets — and use eight tools (spawn, grab, rip, blast, laser, gun,
pin, delete) on the stick figures, who walk around, panic and run from danger.

Figures are 11-point skeletons solved with position-based dynamics, so limbs bend,
bodies tumble and damage is computed from real impact velocity.

## Blood and gore controls

Everything gruesome sits behind toggles in the **Gore** tab: blood, floor stains,
visible wounds, bleeding, blood volume, stain darkness, dismemberment, chunks and
limb toughness. **Safe mode** turns all of it off in one press — figures simply
power down instead of coming apart.

The **Clean-up** tab clears the whole room, or just the items, figures, dead,
debris or stains.

## Controls

| | |
|---|---|
| `1`–`8` | Select tool |
| Right-click | Delete the object under the cursor |
| `Space` | Pause |
| `F` | Slow motion |
| `B` | Add a stick figure |
| `V` | Clear the whole room |
| `X` | Heal everyone |
| `Q` | Show / hide the item list |

## Install it on a phone or tablet

It is a full PWA — installable, and it keeps working with no connection.

**iPad / iPhone:** open the link in **Safari** (not Chrome — only Safari can install
on iOS), tap the **Share** button, then **Add to Home Screen**. It launches
fullscreen with no browser chrome.

**Android / desktop Chrome:** use the install icon in the address bar, or
*Menu → Install app*.

Sound is off by default — turn it on in the **Settings** tab, where there is also
a volume slider. Browsers only allow audio to start after you interact with the
page, so switch it on with the toggle rather than expecting sound on load.
