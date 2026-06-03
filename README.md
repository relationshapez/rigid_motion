# Relationshapez: Rigid Motion

This single-file HTML tool lets students explore two-dimensional rigid motions using triangles on either a square grid or an equilateral-triangle grid.

https://relationshapez.github.io/rigid_motion/

## Files

- `index.html` — the interactive rigid motion tool
- `README.md` — this documentation

## How to Use

Open `index.html` in a web browser.

The app has two tabs:

- **Settings** — choose the problem type, grid type, rigid motion, and whether to display the solution.
- **Canvas** — view the problem and mark up the grid by hand.

## Settings

### Problem

Choose either:

- **Forward** — the original triangle and rigid motion are shown. Students find the image triangle.
- **Backward** — the original triangle and image triangle are shown. Students identify the rigid motion.

Use **Display Solution** to reveal the relevant construction.

### Grid

Choose either:

- **Square** — a standard Cartesian grid.
- **Triangle** — an equilateral-triangle grid.

Use **Snap to Grid** to draw straight construction segments between grid points. Snap to Grid is on by default.

### Rigid Motion

Choose one rigid motion:

- **Translation**
- **Reflection**
- **Rotation**
- **Transflection**
- **Random**

Random chooses one of the four rigid motions.

## Canvas Tools

### Drag

Drag the canvas to move the view. Use the mouse wheel or trackpad scroll to zoom.

### Draw

With **Snap to Grid** on, drawing uses a two-point straight-line tool:

1. Click or tap one grid point.
2. Click or tap another grid point.
3. A straight segment is drawn between them.

A single click or tap places a point.

With **Snap to Grid** off, drawing follows the cursor or finger freely.

### Erase

Erase removes only student markup. It does not erase the grid, triangles, or solution markings.

### Undo

Undo removes the most recent markup action.

### Reset

Reset clears the markup for the current problem.

### New

New clears the markup and loads a new problem.

## Solution Behavior

For forward problems, the solution shows the image triangle with a transparent fill so student markup remains visible.

For backward problems, the solution shows the relevant construction:

- **Translation** — vectors from original vertices to image vertices.
- **Reflection** — line of reflection, perpendicular construction segments, right-angle markers, and matching perpendicular-step labels.
- **Rotation** — perpendicular bisectors, rotocenter, rotation direction, and angle labels.
- **Transflection** — line of reflection and glide vectors parallel to the line of reflection.

## License

Copyright (c) 2026 Alan Miller.

This project is released under the **MIT License**.

See the [`LICENSE`](LICENSE) file for the full license text.
