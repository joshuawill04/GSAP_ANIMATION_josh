# Suave Dynamic Showreel Stack

A premium, lightweight, modular GSAP card-stack animation designed for cinematic vertical showreels and reusable motion-beat systems.

This file is not just a visual snippet.
It is a dynamic shell for swappable assets.

---

## What This Is

This animation is a three-card premium stack with:

- dark cinematic background
- restrained ambient glow
- subtle floating motion
- smooth card transitions
- slot-based dynamic asset injection

It is intentionally built to be:

- sleek
- smooth
- minimal
- modular
- swappable
- more performant than blur-heavy alternatives

---

## Core Design Goal

The point of this snippet is not text animation.

The point is to provide a reusable, premium motion shell where the visual content inside each card can be replaced without rewriting the motion system.

This makes it suitable for:

- future asset retrieval systems
- dynamic backend-driven motion assembly
- reusable cinematic visual beats
- motion libraries prepared for vector search and semantic retrieval

---

## Features

- three-card premium vertical layout
- smooth entrance and swap choreography
- ambient idle motion
- configurable autoplay loop
- dynamic slot system
- dark/light card tone support
- built-in placeholder assets
- support for custom image and HTML injection
- transform-led animation for smoother playback

---

## Slot System

Each card contains a dynamic slot.

The slot content is defined in `CONFIG.states`.

Each state controls:

- card tone
- asset type
- asset source or asset name

### Supported asset modes

#### 1. Built-in assets
Use:
```js
{ type: "builtin", name: "wave" }
