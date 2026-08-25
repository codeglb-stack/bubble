# Build prompt

Create a single-page cinematic WebGL experience called **BubbleBorough**: an original underwater cartoon reef town explored through a continuous scroll-driven camera path. The result should feel like an editorial adventure book moving through a live 3D sea-floor set, not a conventional landing page.

## Experience

- Use a fixed full-viewport Three.js canvas as the environmental layer.
- Build the reef town, pineapple-like home, tall stone tower home, round dome home, sandy path, coral props, portholes, pipes, bubbles, jellyfish, caustic light, and underwater haze procedurally.
- Drive one continuous camera path from page scroll. Each section should feel like a composed shot in the same world rather than a separate scene.
- Add soft bloom-like glow, water haze, surface rays, slow bubbles, drifting plankton, and a playful blue-green grade.
- Keep the palette deep ocean blue, teal, seafoam, coral pink, orange, warm window yellow, and bone white.

## Procedural Building Direction

- The hero must be anchored by three large landmark homes, not small background props.
- Center landmark: a tall pineapple-inspired orange home with diamond rind grooves, chunky blue porthole windows, a rounded blue metal door, pipe chimney, and a dense green leaf crown. It should be the tallest and warmest object in the frame.
- Left landmark: a blue-gray stone tower home with a carved monolith silhouette, rough porous stone material, brow slab, long nose block, side slabs, circular glass porthole eyes, and a small wooden arched door.
- Right landmark: a dark rust-brown dome home, squat and heavy, with a large arched black doorway, speckled shell/rock texture, small brass antenna, and coral at its base.
- Use large scale, rounded forms, bevel-like layering, repeated surface grooves, porthole rings, metal rivets, warm window glow, and sandy contact shadows so the homes feel intentionally designed rather than placeholder primitives.
- When local building artwork is available, it may be used as a foreground detail plate in the 3D space while procedural geometry provides volume and parallax behind it.

## Hero Composition

- The first viewport should contain all important UI elements: nav, chapter label, headline, supporting copy, oversized bottom wordmark, chapter chips, right vertical type, and preview card.
- Keep the landmark homes visible in the center third of the screen, with the wordmark crossing the lower foreground but not pushing controls below the viewport.
- On desktop, the camera should feel close enough that the homes fill the middle band of the frame, similar to a staged miniature set photographed with a wide lens.
- On mobile, remove the preview card and vertical type, reduce wordmark size, and keep the headline and chapter chips inside the first screen.

## Layout

- Structure the page as a hero, town approach, three landmark chapters, jelly meadow closing, and a compact footer.
- Use large left-aligned editorial headings, oversized background wordmark, small technical labels, chapter numbers, fine rules, and generous negative space.
- Layer local foreground artwork over the live 3D scene: coral, sea grass, jellyfish, bubbles, shell clusters, and sea-flower shapes.
- Foreground layers should add depth without replacing the live WebGL scene.
- Use local generated plates only for preview/card surfaces, not as the source of the 3D world.

## Motion

- Reveal headings and supporting elements as they enter the viewport.
- Use slow section transitions, eased camera interpolation, subtle pointer parallax, and continuous ambient motion.
- Let cards, chapter chips, foreground pieces, bubbles, jellyfish, and lights respond to the active section.
- Include reduced-motion behavior that preserves the reading experience.

## Interaction and quality

- Use a custom cursor only for fine pointer devices.
- Provide working anchor navigation, responsive mobile layout, semantic landmarks, and accessible labels.
- Keep runtime assets local and use relative paths so the site works under a static subpath.
- Avoid frameworks, build tooling, analytics, trackers, remote fonts, placeholder imagery, and direct copyrighted character likenesses.
- Verify desktop and mobile layouts, inspect the browser console, and test one complete scroll/navigation interaction before shipping.
