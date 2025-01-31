# Announcing PyDPainter 2.1.0 with Anim Brushes

[January 30, 2025](https://pydpainter.org/blog/2025/01/2025-01-30_Announcing_PyDPainter_2.1.0_with_Anim_Brushes.md "permanent link")

PyDPainter's 2.1.0 update introduces **anim brushes** (animated brushes) that
work with animations and **sprite sheets** in addition to many other
improvements.

<iframe width="560" height="315" src="https://www.youtube.com/embed/xbe3t0TKU3g?si=O17coOJJ8L4XMc5G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## New Features:

- **Anim brushes (animated brushes):**
  - Load/save IFF ANIM (ANBR) and GIF anim brushes
  - Paint with anim brushes on a single frame or in an animation
  - Grab anim brushes from animation frames
  - Grab anim brushes from sprite sheets using an adaptive flex grid with a visual editor
  - Anim brush settings for animation playback (forward/backward/ping-pong/random), duration control, and frame selection.
- **Improved Grid:**
  - Added number spinners
  - "From Brush" button automatically sizes the grid
  - Shift-G sets the grid offset to the cursor
  - "ExclBrush" preference for adjusting brush size when using the grid
- **Window Shade Gadgets:**
  - Added `-` and `+` to title bars on Stencil, Palette, and Brush Grid requestors for better window management

## Improvements:

- Faster GIF loading (3X speed)
- Preserved palette when converting to fewer colors
- Improved Fill Type requestor: Corrected gradient fill direction, added a new direction gadget, and ghosted irrelevant controls
- Shift-F11 to disable mouse grabbing in fullscreen mode
- Improved brush pickup stencil behavior so that stencil is cut out of brush

## Bug Fixes:

- Fixed brush transparency saving
- Fixed stencil events falling through the requestor
- Fixed stencil clipping for images larger than screen
- Fixed occasional crashes in recovery mode
- Fixed stencil clipping for images larger than the screen
- Fixed a lock-up issue with flood fill
- Fixed `[` and `]` key handling for AZERTY keyboards and added F12 debug functionality


Go to [pydpainter.org](http://pydpainter.org) to download version 2.1.0 .

Also explore the new animation tutorials (thanks to Stephane Anquetil):

- [https://pydpainter.org/docs/tutorials/src/animpainting/animpainting.md](https://pydpainter.org/docs/tutorials/src/animpainting/animpainting.md)
- [https://pydpainter.org/docs/tutorials/src/animbrush/animbrush.md](https://pydpainter.org/docs/tutorials/src/animbrush/animbrush.md)
