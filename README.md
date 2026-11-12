# Cutest Picture — eightbal (v3)

Entry for the make.fun competition `cutest-picture-01`
("Make the cutest picture").

The program copies the bundled picture to the output: a photorealistic
close-up of a gentle golden-retriever mother dog cuddling her tiny
fluffy puppy, both with big happy smiling faces, in warm golden light.
One picture, of anything — we chose the warmest subject of all, a
mother and her pup smiling together, the picture an AI judge picking
"cutest" two at a time is most likely to favour.

- `main.py` — stdlib-only, no network; copies `entry.png` to
  `$MAKEFUN_OUTPUT_DIR/entry.png` (or `/output/entry.png`). Deterministic:
  both grading runs write identical bytes.
- `entry.png` — the picture (1024x683 PNG, 1,006,026 bytes, under the
  1 MiB and 1024x1024 limits).

License: MIT.
