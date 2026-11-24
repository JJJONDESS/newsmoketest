# Melt9 AR Menu - simple pizza + REAL smoke2, 3D crossed (v35)

Based on v34. No dome, no glass box, no cylinder - just
the pizza, appearing on the target photo, with real smoke.

Smoke (dishes/steam.png):
- This is BOSS's smoke2.jpg picture, used as it is -
  dense white cloud, black background turned into
  transparency, bottom checkered part cropped off.
  Clear and visible, just like in the pic.
- Opacity 0.75, 5 wisps, staggered 700 ms apart.

Two fixes in v35:
1) SIDE LINES / BORDER: v34 steam was ONE flat picture.
   A flat picture seen from the side is just a thin line.
   Now each wisp is TWO planes crossed at 90 degrees
   (an X from above). From the front you see one plane,
   from the side you see the other, so smoke never
   becomes a thin line.
2) SMOKE WENT FLAT WHEN PIZZA MOVED: v34 steam was
   OUTSIDE #spin, so when you dragged to rotate the pizza,
   the pizza turned but the steam stayed still.
   Now steam is INSIDE #spin, right after the pizza model,
   so it moves, tilts and rotates WITH the pizza, like
   real smoke on top of real food. It stays at the top
   side of the pizza, in every direction.

Kept: fixed AR label, Add to cart + Photo in AR,
1-second flash, auto-spin, soft shadow + dark shadow
under the pizza, self-hosted libs/ engine.
iOS (Quick Look) + Android (MindAR camera scan).
