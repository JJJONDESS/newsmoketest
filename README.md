# Melt9 AR Menu - simple pizza + cloudy wavy smoke (v36)

Based on v35. No dome, no glass box, no cylinder - just
the pizza, appearing on the target photo, with real smoke.

Smoke (dishes/steam.png):
- BOSS's smoke2.jpg picture, dense white cloud, black
  background turned into transparency, bottom checkered
  part cropped off. Opacity 0.78.

Two fixes in v36, from BOSS's video:
1) SMOKE DRIFTED TO THE SIDE: in v35 the smoke was
   INSIDE #spin. Auto-spin and drag-rotate turn #spin
   around, so the smoke orbited round the pizza like a
   clock hand - the smoke on the left side in the video.
   Now smoke is inside #tilt but OUTSIDE #spin. The pizza
   spins UNDER the smoke, the smoke stays on TOP of the
   pizza. It is still inside #tilt, so when you tilt the
   pizza from horizontal to vertical, the smoke tilts
   WITH the pizza and follows it to the side, properly.
   Crossed planes (2 per wisp, 90 degrees apart) are
   kept, so smoke never goes flat from the side.
2) MORE CLOUDY AND WAVY: each wisp now GROWS as it
   rises (scale 0.7 to 1.4, like real smoke expanding),
   CURLS side to side (rotation -18 to +18 degrees),
   and SWAYS sideways (+/- 0.12) on its way up, so the
   path is wavy, not a straight lift. Smoke starts LOW,
   over the pizza face (Y = -0.05), so it sits ON TOP
   of the pizza, like food fresh out of the oven.
   5 wisps, 2 crossed planes each, staggered 700 ms.

Kept: fixed AR label, Add to cart + Photo in AR,
1-second flash, auto-spin, soft shadow + dark shadow
under the pizza, self-hosted libs/ engine.
iOS (Quick Look) + Android (MindAR camera scan).
