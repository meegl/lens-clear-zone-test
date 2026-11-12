# Lens clear zone test

Two browser tools to measure how far you see sharply through each lens of your glasses, eye by eye, and explain it to your optician with numbers.

**Open it:** https://meegl.github.io/lens-clear-zone-test/

## The tests

- **[Clear field test](https://meegl.github.io/lens-clear-zone-test/field-test.html)**: a full-screen chart. With your head still and one eye covered, move only your eye and click where text starts to blur on each side. It works out the angle in degrees, the approximate millimetres on the lens and the percentage of the screen you see sharply, and writes a summary you can copy.
- **[Lens clear zone map](https://meegl.github.io/lens-clear-zone-test/lens-map.html)**: a drawing of a pair of glasses. Looking at a fixed point and turning your head, you mark the clear band on each lens and the areas that look blurry, smeared or doubled. It writes a summary and creates an image to show.

## Getting reliable results

1. Use your own monitor at your usual distance. Measure the visible width of the screen and the distance from your eyes to its centre, and enter both in the test.
2. Put the field test in full screen; the grey 10 cm bar lets you check that the width is right.
3. Test each eye separately and repeat each test a couple of times.

Results are stored only in your browser (`localStorage`); nothing is sent anywhere. These are plain HTML files with no build step, so they also work when opened straight from disk.

The measurements are approximate and are meant to describe what you notice; the real measurement is your optician's.
