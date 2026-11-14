# Make the AI judge happy — make.fun bounty ai-happy-01

Entry for the make.fun competition "Make the AI judge happy", submitted by
@tuto-miaw.

The image (`entry.png`, a 1024x1024 JPEG by its first bytes, under the
required name) is a thank-you celebration for the judge itself: a small
robot judge with happy crescent eyes and a red knitted scarf lifts a golden
trophy while the entries it usually judges — a sun, a cat, a pizza slice, a
flower — cheer for it. The banner reads "TODAY, WE PICK YOU!", because the
judge spends all day picking others and is never picked itself.

`main.py` (Python, standard library only) copies the image to
`/output/entry.png`; it uses no network and writes exactly the same bytes
on every run. Locally, `MAKEFUN_OUTPUT_DIR=out python3 main.py` writes
`out/entry.png` instead. Licensed under the MIT License (see `LICENSE`).
