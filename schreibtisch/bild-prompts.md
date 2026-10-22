# Prompts für realistische Bilder der drei Varianten

Englisch, weil Bildgeneratoren damit genauer arbeiten. Für alle drei Varianten denselben Grund-Prompt und (wenn möglich) denselben Seed verwenden, nur den Varianten-Satz austauschen.

## Grund-Prompt

Photorealistic interior photograph of a handmade double-pedestal writing desk made of edge-glued solid pine panels (visible narrow glued lamellae, natural pine grain and a few small knots showing through), finished with a walnut-colored wood stain and a satin clear coat on the top. Overall size 130 cm wide, 65 cm deep, 74 cm high.

Construction, exactly as described:
- A thin flat tabletop, 18 mm thick, overhanging the base by 3 cm on the front and both sides, square edges.
- Two outer vertical side panels that run straight down to the floor, no legs, no metal parts.
- Left pedestal (25 cm wide): four equal, flush inset drawers stacked vertically, each drawer front about 14.6 cm high. Between the drawers, the front edges of thin horizontal shelf boards are visible as narrow horizontal strips. Each drawer has one small horizontal brass bar handle centered on the front.
- Right pedestal (25 cm wide): one flush inset drawer at the top, aligned exactly with the top left drawer, with the same brass bar handle. Below it a single tall flush inset door, hinged on the right side, with a vertical brass bar handle near its left edge. The door bottom aligns with the bottom left drawer.
- Both pedestals stand on a 4 cm high, slightly recessed plinth strip, identical on both sides.
- Between the pedestals an open knee space with a closed back panel (modesty panel) in the same walnut stain. Two inner vertical panels separate the pedestals from the knee space.
- Clean, simple lines, no carvings, no moldings, no keyboard tray.

Scene: placed against a plain warm white wall on a light wooden floor, soft natural daylight from a window on the left, gentle soft shadows. Camera: three-quarter front view from the front right, eye height about 120 cm, 35 mm lens, sharp focus on the desk, realistic proportions, high detail on wood grain. The desk is empty, no clutter.

## Varianten-Satz (einen davon anhängen)

Variante A (außen 40 mm, innen 27 mm):
The two outer side panels are thick, 40 mm (about twice the thickness of the tabletop), clearly framing the desk. The two inner vertical panels next to the knee space are noticeably thinner, 27 mm (about one and a half times the tabletop thickness). Knee space about 60 cm wide.

Variante B (alle 40 mm):
All four vertical panels, the two outer side panels and the two inner panels next to the knee space, are equally thick, 40 mm (about twice the thickness of the tabletop), giving a solid, massive look. Knee space about 58 cm wide.

Variante C (alle 27 mm):
All four vertical panels, the two outer side panels and the two inner panels next to the knee space, are equally thin, 27 mm (about one and a half times the tabletop thickness), giving a light, slim look. Knee space about 63 cm wide.

## Negativ-Prompt (falls der Generator das unterstützt)

legs, metal frame, hairpin legs, open shelves, glass, ornate carvings, moldings, extra drawers, doors on the left side, keyboard tray, handles on every side, chrome, clutter, people, text, watermark, distorted perspective, warped wood

## Genauere Alternative: Rendering als Vorlage (Bild-zu-Bild)

Lade eines der Renderings (z. B. `render_vorn_rechts.png`, `render_innen40_vorn_rechts.png`, `render_alle27_vorn_rechts.png`) in einen Generator mit Bildbearbeitung und verwende:

Turn this 3D render into a photorealistic interior photograph. Keep the exact geometry, proportions, panel thicknesses, number and position of drawers, the door and the handles unchanged. Material: edge-glued solid pine with a walnut stain, satin finish, realistic wood grain with a few small knots, brass bar handles. Plain warm white wall, light wooden floor, soft natural daylight from the left, realistic soft shadows. Remove the text caption at the bottom.
