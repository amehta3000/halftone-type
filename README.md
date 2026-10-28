# Halftone Type

A graph-paper grid that turns what you type, or the current time, into letters built from shapes on the grid.

- **Type** – press any key and its character grows in from the grid intersections, holds while the key is down, then shrinks away when you let go.
- **Write** – what you type stays on the page, wrapping at word breaks. Backspace deletes, Enter starts a new line, Esc clears.
- **Time** – the current time (HH:MM). Only digits that change animate; the colon blinks each second.
- **Extended** – the current time with seconds (HH:MM:SS).

Four shapes: **Dots**, **Squares** and **Diamonds** grow from interior intersections, **Tiles** fill whole cells with corners rounded where the letter's edge passes.

Live: https://amehta3000.github.io/halftone-type/

A sun/moon button switches between light and dark. Scale the grid with the slider, the −/+ buttons, scrolling, or pinching. The grid springs to the new size, and letters keep their size on screen so they get coarser or finer as it moves.

It's a single `index.html` using React 18 from a CDN. Open it in a browser, no build step.
