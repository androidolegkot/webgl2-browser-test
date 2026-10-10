# WebGL 2.0 Browser Test

A lightweight browser test for checking WebGL 2.0 support and graphics acceleration, especially on older PCs.

**Live demo:** https://androidolegkot.github.io/webgl2-browser-test/

## Purpose

Quickly check whether browser graphics acceleration is working correctly. The test can help troubleshoot browser settings, hardware acceleration, and graphics driver installation, particularly on older PCs and systems with integrated graphics.

## Features

- WebGL 2.0 support detection
- GPU and renderer information, when available
- WebGL and GLSL version detection
- Real-time FPS and frame-time measurements
- Drawing buffer resolution
- WebGL context loss detection
- Fixed Three.js r160 version for consistent testing

## How to Use

1. Open the live demo.
2. Check the WebGL 2.0 test result.
3. Inspect the reported GPU and renderer information.
4. Observe the rotating 3D cube, FPS, and frame time.
5. If the test fails or performance is unexpectedly low, check browser acceleration settings, graphics drivers, and hardware compatibility.

## Interpreting Results

- **WebGL 2.0 PASS** — the browser successfully created a WebGL 2.0 context.
- **GPU / renderer** — may help identify the graphics hardware or a software renderer.
- **Low FPS** — may indicate a performance limitation, software rendering, a driver issue, or another system bottleneck.
- **WebGL 2.0 FAIL** — the test could not initialize WebGL 2.0.

**Note:** A successful test does not conclusively prove that hardware acceleration is enabled or that the graphics driver is installed correctly. FPS depends on hardware, browser configuration, display refresh rate, and system load. This is a quick functional check, not a comprehensive GPU benchmark.

## Web App

[WebGL 2.0 Browser Test](https://androidolegkot.github.io/webgl2-browser-test/)

A lightweight browser-based tool for checking WebGL 2.0 support, graphics renderer information, and real-time 3D rendering performance. Useful for troubleshooting hardware acceleration, browser settings, and graphics drivers, especially on older PCs.

## Technologies

- HTML5
- CSS
- JavaScript
- [Three.js r160](https://github.com/mrdoob/three.js/tree/r160)

Runs as a static website on GitHub Pages and uses a local copy of Three.js.

## Development

AI-assisted development: **ChatGPT** (chatgpt.com)
