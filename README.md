# ciscovfx.github.io

VFX texture tools that run in your browser.

## What's here


Pack up to 4 grayscale textures into a single RGBA image. Supports PNG, TGA, and EXR (half-float) output. Per-channel controls for luminance conversion, brightness, invert, and fill.


Drop a sequence of images, configure your grid, export a spritesheet. Auto-grid, per-frame scaling, drag reorder. Same export formats.

**[Flipbook Packer](https://ciscovfx.github.io/tools/flipbook-packer/)**
Drop a sequence of images to instantly arrange them into a spritesheet. Includes automatic grid calculation, drag-and-drop frame reordering, and per-frame scaling. Features a grid overlay preview to ensure perfect alignment for VFX particles.

**[Channel Packer](https://ciscovfx.github.io/tools/flowmap-painter/)**
Paint and generate custom flow maps directly in the browser to control VFX distortion. Use directional strokes or procedural tileable noise to define flow vectors. Features multiple brush tools (swirl, pinch, ripples) and a real-time animated distortion preview using reference textures.

**[Channel Packer](https://ciscovfx.github.io/tools/rgba-packer/)**
Pack up to four grayscale textures into the R, G, B, and A channels of a single optimized image. Features drag-and-drop channel swapping, custom resolution output, and per-channel controls for luminance conversion, brightness, invert, and solid fill values.

## Why

When I started in VFX, these were the kinds of simple tools I needed. Had to do it the manual way back then. Hopefully they help someone else now.

## How to use

Go to [ciscovfx.github.io](https://ciscovfx.github.io), pick a tool, drop your files, export. Everything runs locally in your browser, your files never leave your machine.

## Built with

HTML, CSS, vanilla JS. No frameworks, no dependencies, no server. Made with AI assistance (MiMo).

