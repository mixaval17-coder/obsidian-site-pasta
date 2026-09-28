# Obsidian — Interactive Liquid Metal Concept

A minimalist, single-file creative web development experiment featuring an interactive GLSL liquid metal sculpture synchronized with smooth scroll choreography.

## Disclaimer

This project is purely an experimental concept and a creative playground. "Obsidian Studio" is an entirely fictional entity. This website is not a real commercial product, nor does it represent any existing company, brand, or organization. 

It was built strictly for educational purposes, experimentation, and technical demonstration.

## Purpose and Code Extraction

The primary goal of this repository is to serve as an open resource for developers, designers, and creative coders. You are welcome and encouraged to take, extract, and adapt any parts of this codebase for your own projects, including:

- **Procedural GLSL Shaders**:
  - Simplex noise vertex displacement with analytical normal recalculation (sharp specular highlights without mesh tearing).
  - Procedural reflection environment computed directly in the fragment shader (zero external HDRI maps or textures required).

- **Scroll and Motion Architecture**:
  - Smooth scroll integration using Lenis and GSAP ScrollTrigger.
  - Decoupled physics damping (`THREE.MathUtils.damp`) bridging scroll timeline progress to WebGL uniforms for stable frame rates.
  - Pinned sequence transitions (Liquid -> Fracture -> Stillness).

- **Typography and Layout**:
  - Minimalist pairing of Unbounded and Manrope fonts.
  - Metallic text gradient masks and inline SVG fractal noise overlay to eliminate gradient banding.

## Getting Started

The entire project is contained within a single file. There are no build steps, bundlers, or package installations required.
