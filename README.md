# recursize

Live nested screenshot-preview windows. Windows hold windows hold windows;
resizing one pushes, squeezes, ripples, or bakes up and down the tree.
Born from ⌥-dragging macOS screenshot previews and being disappointed
that a screenshot of a screenshot is dead pixels. Here nothing is dead
unless you bake it.

One file. No dependencies. Open `recursize.html` in a browser.

- **dblclick** any surface = a window is born there · **N** arms a deploy cursor (drag draws one to size; digits 1–9 drop an N-deep chain)
- drag corners to resize — **⌥ tap** latches symmetric-from-center, **⇧** proportional
- inner growth pushes ancestors; outer shrink squeezes kids (they remember)
- **⊕** window inside · **⇧⊕** engulf · **⊗** close (kids promote; a root's kids go free)
- controls.cfg cascades from the selected window down its subtree (• = set here, dblclick label = inherit)
- fills: rainbow / random / palette file (.hex, .gpl, hex text) / images + video — drop them on the desk; they cycle through the windows (**TAP** tempo)
- looper: **R** arms a tree — every window you grab records its lane and loops on release; grab it again to take it back; **W:TREE / W:LANE** clocks
- **E** eases everything to stillness · **ESC** cuts

jon satrom · speed project, 2026-08-27
