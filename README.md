# Borozdov Velvet

A theme from the Borozdov collection. Two faces — dark **Library**, a velvet reading room
after midnight, and light **Atrium**, the same room in the morning. Matte black surfaces,
an italic serif headline, monospace labels and one cyan spark for what you act on.

![Borozdov Velvet in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/velvet/main/screenshots/dark.png)

![Borozdov Velvet in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/velvet/main/screenshots/light.png)

## Principles

- **A vast dark room.** True black behind matte, paper-thin surfaces; a hairline edge
  is all the depth there is.
- **Three voices.** Velvet Serif Italic at dramatic size for the title and the big headings;
  the platform's sans for the text; a monospace, in capitals, for everything that reads as
  metadata — tags, table headers, callout labels, property names, the two smallest headings,
  the status bar.
- **One cyan spark.** Cyan marks links, the caret, a checked task and a toggle. The main
  button is white on black, never a colour.
- **One teal surface.** The plain note callout rests on the room's single teal card;
  every other callout is matte with a label in its type's colour.

## Features

- Dark and light modes, following Settings → Appearance → Base color scheme
- Pull quotes in the italic serif, a touch larger, behind a cyan rule
- Tags as monospace stamps in a thin steel frame
- Code and tables in matte cards with a hairline edge
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces; the cyan is deepened for text on Atrium
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory:** Settings → Appearance → Themes → Manage, search for
**Borozdov Velvet**, then **Install and use**.

**By hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/velvet/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Velvet/`, then choose Borozdov Velvet under
Settings → Appearance → Themes.

## Font

Velvet Serif is embedded in `theme.css` as base64 WOFF2 under the SIL Open Font License
1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt). It is a Latin and Cyrillic subset of Playfair
Display Italic (© 2010–2012 Claus Eggers Sørensen), renamed because a modified copy may not
use the original's Reserved Font Name. One style, headlines and quotes only. The monospace
is your platform's own (DM Mono or JetBrains Mono if installed, otherwise SF Mono, Menlo or
Consolas).

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: тёмный «Библиотека» — бархатная
читальня после полуночи, и светлый «Атриум» — та же комната утром. Матовые чёрные
поверхности, курсивные заголовки с засечками (Velvet Serif), моноширинные подписи и одна
циановая искра для того, что вы делаете. Устанавливается из каталога: Настройки → Оформление
→ Темы → Настроить → Borozdov Velvet → Установить и применить.
