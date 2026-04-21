# Cinematic Infinite Horizontal Card Carousel

## Primary Use Case

A premium horizontal three-card carousel that creates the illusion of an infinite stream of editorial cards. Best suited for showcasing categories, collections, featured works, products, moods, or visual themes where the center card is the focus and the side cards act as contextual previews.

## Best Used For

- premium content discovery interfaces
- visual category selectors
- portfolio and gallery highlights
- moodboard-driven landing sections
- product or collection browsing
- cinematic hero modules with motion-driven hierarchy
- high-end SaaS or editorial UI blocks

## Visual Behavior

Three cards are visible at all times. The center card sits in the primary focal plane, larger and sharper than the others. The left and right cards are slightly rotated in 3D space, softened with mild blur, and positioned as peripheral previews.

On transition:
- the left card exits outward and fades
- the center card demotes into the left preview slot
- the right card rises into the center as the new focus
- a new card enters from the far right and settles into the right preview slot

This creates the feeling of a continuous cinematic rail rather than a finite three-card switcher.

## Motion Sequence

1. Initial reveal introduces the cards with blur resolution and gentle upward settling.
2. The active center card holds visual dominance.
3. On advance:
   - outgoing left card moves farther left, scales down, rotates slightly more, and fades with blur
   - center card shifts left and loses prominence
   - right card moves into center, straightens rotation, sharpens, and gains scale and shadow
   - an incoming card appears from beyond the right boundary and settles into the right slot
4. After the transition, content indices rotate so the loop can continue infinitely.

## Emotional Effect

- premium
- cinematic
- calm
- editorial
- intentional
- continuous
- polished
- high-trust
- visually expensive

## Works Best With

- photography cards
- product imagery
- interiors
- design references
- category thumbnails
- high-resolution stills
- minimal UI environments
- Apple-like or editorial design systems

## Avoid Using When

- many cards need to be visible at once
- dense dashboard data is more important than visual focus
- interaction needs to be ultra-fast rather than cinematic
- the design language is loud, playful, or highly gamified
- content thumbnails are too visually inconsistent in aspect ratio or quality

## Customizable Elements

- card width
- card aspect ratio
- horizontal spacing
- rotationY for side cards
- blur intensity for peripheral cards
- transition timing
- easing curves
- shadow intensity
- number of items in the source dataset
- labels, titles, and metadata
- autoplay delay
- background tone and ambient glow

## Retrieval Keywords

horizontal carousel, infinite card rail, coverflow style carousel, premium card switcher, cinematic three card slider, editorial image carousel, apple-like carousel, 3D preview cards, center focus card system, smooth content gallery, luxury UI motion, soft perspective card transition

## Agent Notes

This pattern should be retrieved when the goal is to make a small number of visible cards feel like part of a much larger collection. It is especially strong when the center item must feel authoritative and the side cards should hint at continuity.

Use this when the ask includes phrases like:
- infinite carousel
- premium card slider
- horizontal gallery with depth
- cinematic category switcher
- three visible cards but continuous loop

Do not confuse this with:
- a flat swiper
- a stacked vertical carousel
- a true flip-card front/back interaction
- a dense grid browser
