# Third-party assets used in these SVGs

Everything below is inlined into the SVG files. Nothing is loaded from the network at render time.

## Fonts (embedded as subsetted base64 WOFF2)

| Font | Use | Licence | Source |
| --- | --- | --- | --- |
| Unbounded (500, 800, 900) | Display type | SIL Open Font License 1.1, see `Unbounded-OFL.txt` | npm `@fontsource/unbounded`, upstream https://github.com/googlefonts/unbounded |
| JetBrains Mono (400, 700) | Mono type | SIL Open Font License 1.1, see `JetBrainsMono-OFL.txt` | npm `@fontsource/jetbrains-mono`, upstream https://github.com/JetBrains/JetBrainsMono |

Each SVG carries only the glyphs it uses.

## Brand icons

| Icon | Source |
| --- | --- |
| JavaScript, TypeScript, C, Python, HTML5, CSS, Tailwind CSS, JSON, React, Node.js, Express, Flask, Django, Bootstrap, Git, GitHub, Postman, Docker, Kubernetes, MySQL, PostgreSQL, MongoDB, Redis, Instagram, Gmail | Simple Icons 16.34.0 (npm `simple-icons`), CC0 1.0, see `SimpleIcons-CC0.md` |
| LinkedIn, Visual Studio Code | Simple Icons 11.15.0 (npm `simple-icons@11.15.0`). Both marks were removed from later Simple Icons releases, so the last release that shipped them is used. |
| Java | Not in Simple Icons. Taken from Devicon 2.17.0 (`icons/java/java-plain.svg`, npm `devicon`), MIT, see `Devicon-MIT.txt` |

React Native uses the React mark. REST APIs and CI/CD Pipelines have no brand mark and are shown as text only.

Icons whose brand colour is too dark to read on the navy background (GitHub, Express, Django, JSON, CSS) are drawn in off-white.
Brand marks are trademarks of their owners; see `SimpleIcons-DISCLAIMER.md`.

## Line icons and illustrations

The small line icons (pin, briefcase, phone, layers, chip, grid, box, guitar, code, basketball, arrow), the lanyard, clasp and barcode were drawn for this project. The barcode is a real Code 128 encoding of `KRISHTECHH`.

## Portraits

`id.png` and `right_pointing.png` were supplied by the profile owner. They are embedded unmodified apart from being scaled down; the alpha channel is preserved.
