# Make the AI judge happy — make.fun bounty ai-happy-01

Entry for the make.fun competition "Make the AI judge happy", submitted by
@tuto-miaw.

The image (`entry.png`, a 1024x1024 JPEG by its first bytes, under the
required name) is a child's handwritten letter to the judge, on ruled paper
with a crayon drawing. It gives the judge a day off from deciding: "today
you choose NOTHING. i chose everything for you. the cake is chocolate. the
hat is the red one. the song is the loud one. your only job is cake. your
slice is the biggest. love, Bimo (7)" — and the drawing shows exactly that:
the chocolate cake, the red party hat, and gold stars. The lettering is
rendered in a handwriting typeface so every word stays perfectly legible.

`main.py` (Python, standard library only) copies the image to
`/output/entry.png`; it uses no network and writes exactly the same bytes
on every run. Locally, `MAKEFUN_OUTPUT_DIR=out python3 main.py` writes
`out/entry.png` instead. Licensed under the MIT License (see `LICENSE`).
