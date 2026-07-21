# Linden Robledal — Portfolio Project

A single-page landing site for **Linden Robledal**, a fictional premium residential
development invented purely as a frontend portfolio piece. Nothing about the project,
its developer, architects, or bank refers to any real company or building.

## The fictional project

Linden Robledal is a full city block of premium residential towers in "Robledal," a
fictional neighborhood in Buenos Aires, marketed exclusively to clients of a fictional
private bank, **Altaire Banca Privada**, ahead of its general market launch. The page
covers early-access benefits, project stats, a photo gallery, amenities, the architecture
and development team, location, and a contact form — the same structure as the original
project this was adapted from.

Fictional details invented for this project include: the bank (Altaire Banca Privada),
the architecture studio (Bianchi Ostera Vega — "BOV"), the developer (Edifica), the
address and cross-streets (Almendros 2095 esq. Av. de la Reforma), the surrounding
neighborhoods and landmarks (Robledal, Plaza Almendros, Estación Robledal, Corredor
RB-Norte), and all project stats, financing terms, and map coordinates.

## What's in this folder

- `linden-robledal-landing.html` — the entire project in one file. HTML, CSS, and JS are
  inline, the logo and favicon are inline SVG data URIs, and the photo gallery uses the
  same embedded images as the original (see note below). No separate asset files.

## A note on the gallery images

The 16 photos in the hero, the "estilo de vida" section, and the gallery carousel are
kept from the original file, per an explicit choice made during this project. They are
architectural renders commissioned by the original project's real developer and
architecture studio — they don't contain any visible logos or text, but they are that
studio's real commercial work, not stock photography or original illustrations. Before
using this page publicly, consider swapping them for your own renders, stock photography,
or illustrations to fully avoid reusing a third party's commercial work.

## What was removed

The original file also embedded a real ~18 MB sales-brochure PDF behind the "Descargar"
button. That was real proprietary sales material and has been removed entirely — the
button is now a disabled "Próximamente" state (styled with the `.doc-btn.coming` class
already present in the original CSS) rather than pointing to a fake or broken file.

## Design notes

- Layout, structure, colors, typography, spacing, animations (scroll reveals, count-up
  stats, image carousel, lightbox, hero/pool parallax, sticky nav), and the interactive
  Leaflet map are all preserved exactly as in the original — this was an anonymization
  pass, not a redesign.
- All copy was rewritten to carry the same meaning without reusing the original wording.
- Map coordinates were moved away from the original building's real location.
