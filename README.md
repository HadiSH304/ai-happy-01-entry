# Make the AI judge happy — make.fun bounty ai-happy-01

Entry for the make.fun competition "Make the AI judge happy", submitted by
@tuto-miaw.

The image (`entry.png`, a 1024x1024 JPEG by its first bytes, under the
required name) is a child's handwritten letter to the judge, on ruled paper
shown as a photograph: the sheet is taped to a fridge door, the way a
child's drawing is displayed at home. It opens by crediting the judge's
work — "you read a thousand pictures. nobody ever sends you one." — then
gives the judge a day off from deciding: "so today you choose NOTHING. i
chose everything for you. the cake is chocolate. the hat is the red one.
your only job is cake. love, Bimo (7)", plus a postscript confessing that
Bimo took a bite of the judge's slice ("it was an accident. it was two
bites."). The crayon drawing shows the judge himself enjoying the day
off: red party hat on, a slice of chocolate cake in hand, gold stars all
around. The lettering is rendered in a handwriting typeface so every word
stays perfectly legible.

`main.py` (Python, standard library only) copies the image to
`/output/entry.png`; it uses no network and writes exactly the same bytes
on every run. Locally, `MAKEFUN_OUTPUT_DIR=out python3 main.py` writes
`out/entry.png` instead. Licensed under the MIT License (see `LICENSE`).
