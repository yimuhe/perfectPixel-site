# PerfectPixel website

Open https://yimuhe.github.io/perfectPixel-site/

## Alpha edge fix v1

Hard edges (default) decides foreground coverage separately from colour selection
and emits alpha 0 or 255. Adjust coverage to keep thin edges or tighten contours.
Preserve translucency retains genuine coverage alpha for glass, smoke, and effects.
Original runs the legacy sampler for comparison. Regenerate after changing options.
No erosion or small-component deletion is performed. Images stay in the browser.

This repository contains generated browser files only. The maintained project,
website sources, regression tests, and documentation are in a private repository.

Based on https://github.com/theamusing/perfectPixel_webdemo
and https://github.com/theamusing/perfectPixel by theamusing.
