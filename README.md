# Game Console Barcodes
 
Recreated barcode and serial-label graphics for retro video game consoles, provided as editable source files so anyone can print their own replacements.
 
Original console labels fade, tear, get peeled off, or go missing entirely during a restoration. These are clean vector and layered recreations built to match the originals as closely as possible, so a refurbished console can be finished properly instead of left bare or wearing a bad scan.
 
Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — free to use, modify, print, and sell with attribution.
 
---
 
## What's here
 
Each console has its own folder containing:
 
| File type | Purpose |
|---|---|
| `.psd` | Adobe Photoshop — layered raster source |
| `.eps` | Encapsulated PostScript — vector, opens in Illustrator, Affinity Designer, Inkscape, CorelDRAW |
| `.af` | Affinity native source — the primary working files |
| Comparison image | Side-by-side of the recreation against an original label, for verification |
 
## Software
 
Everything here was created in **[Affinity](https://www.affinity.studio/)**, and it's what I'd recommend using. Affinity is now published by Canva and is free — you download it, sign in with a free Canva account to activate the license, and that's it. No purchase, no subscription, no card. Only the optional Canva AI features sit behind a paid plan, and nothing in this repository needs them. Once activated you can work offline indefinitely. It's available for Windows and macOS, with an iPad version in progress.
 
The `.af` files are the primary sources — they're the ones I actually work in, and they carry the full layer structure. **Note that `.af` is the format used by the current unified Affinity app, and Affinity V1 and V2 cannot open it.** If you're on an older Affinity version, use the `.eps` instead; the current app opens V1 and V2 files fine, so it's a one-way compatibility break.
 
The `.psd` and `.eps` exports are there so nobody is forced into a particular application — Photoshop, Illustrator, Inkscape, CorelDRAW, and GIMP will all handle one or the other. Fidelity is best in the `.af` files, though, since exports flatten or approximate some effects.
 
## Consoles and styles
 
| Console | Styles included | Notes |
|---|---|---|
| [Nintendo 64](Nintendo%2064) | 1 | Single label style |
| [Nintendo GameCube](Nintendo%20GameCube) | 2 | Two NTSC label styles |
| [Sega Dreamcast](Sega%20Dreamcast) | 3 | Two NTSC styles and one PAL style |
 
More consoles are welcome — see [Contributing](#contributing).
 
## Fonts
 
Font files are **not** distributed with this repository. Most of the typefaces used here are commercially licensed, and their license terms permit use but not redistribution — so they're listed below instead, with the filenames I have installed, to make them easier to identify and track down.
 
| Font | Used for | Name as installed | Where to get it |
|---|---|---|---|
| Univers 55 | Label body text | `Univers 55` | Commercial. Monotype / Linotype release, sold through Monotype and MyFonts; may also be available through a Monotype or Adobe font subscription. |
| OCR B STD | Machine-readable numerals | `OCR B STD` | Commercial. Adobe's digital cut of OCR-B — available through Adobe Fonts with a Creative Cloud subscription, or purchasable from Adobe and Monotype. |
| OCR B | Machine-readable numerals | `OCR B` | A separate cut from OCR B STD. Free versions of OCR-B exist alongside commercial ones — check the terms on whichever file you obtain. |
| IDAutomationC39S | Code 39 barcode rendering | `IDAutomationC39S` | IDAutomation, at idautomation.com. Licensed per user; a limited free demo version is also offered. |
| Code 39 | Code 39 barcode rendering | `Code 39` | The Code 39 symbology itself is an open, royalty-free standard, but each font implementation carries its own license. Several free Code 39 fonts are available. |
| Source Sans Pro | Supporting text | `Source Sans Pro` | Free and open — SIL Open Font License 1.1. Download from the Adobe Fonts GitHub releases or Google Fonts. Now maintained upstream as Source Sans 3. |
 
Names are given as they appear installed on the machine these designs were built on. Vendors and versions vary, so treat them as a search starting point rather than an exact match.
 
**If you only want to print, you may not need any of these.** The vector `.eps` files carry the type as artwork, so they render correctly without the fonts installed. You'll only need the real fonts if you intend to edit text.
 
**If you substitute:** these are reproductions, so font substitution meaningfully changes the result. A near-match will look approximately right on screen and visibly wrong next to an original label. Working from the `.eps` and editing around the existing type generally beats rebuilding a design with a stand-in typeface.
 
## Printing
 
These are reproductions of physical labels, so scale accuracy matters more than anything else:
 
- **Print at 100%.** Turn off "fit to page," "scale to fit," and any driver-side auto-scaling. A label printed at 97% will look right on screen and wrong on the console.
- **Check against the comparison image** in each folder before committing to a full sheet.
- **Test on plain paper first**, hold it against the console, and confirm dimensions with calipers or a steel rule before printing on label stock.
- Results vary considerably by printer, stock, and finish. Matte or satin adhesive label stock generally reads closest to the originals; glossy photo paper tends to look too modern.
### Label sheets
 
I don't print custom barcode labels — that's why these files are here rather than a storefront.
 
I do sell blank **pre-cut label sheets** and a matching layout template, sized to the Gamer Ghosts label sets, for anyone who'd rather not cut their own. Sheets and template are available at:
 
**https://shop.gamerghosts.com/products/gg-barcodesheet**
 
They're entirely optional. Nothing in this repository depends on them, and the designs print fine on ordinary label stock you cut yourself.
 
## Contributing
 
Corrections and additions are genuinely wanted. Useful contributions include:
 
- **New consoles or new regional variants** — source files in at least one editable format, plus a comparison image against an original.
- **Corrections** — if a dimension, color, font, or glyph is off, open an issue or a pull request. Please include a photo of the original you're comparing against.
- **Format additions** — an SVG or AI export of an existing design, or a cleaner vector trace.
When adding a console, please match the existing structure: one folder per console, source files inside, and a comparison image alongside. Please don't commit font files. If your design uses a typeface not already listed above, add it to the table in your pull request instead.
 
If you only have a photo of a variant that isn't represented here, that's still worth opening an issue for — a good flat, square-on photo of an original label with a scale reference is the hardest part of building one of these.
 
## License
 
Everything in this repository is released under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
 
**In plain terms, you may:**
 
- Use these files for any purpose, personal or commercial
- Edit, remix, and adapt them however you like
- Print them and sell the printed labels, or sell consoles restored with them
- Redistribute the files themselves
**The only condition is attribution.** If you share the files, share a modified version, or sell prints made from them, credit the source and link back here. Something like:
 
> Barcode artwork by Gamer Ghosts — https://github.com/GamerGhosts/game-console-barcodes — licensed under CC BY 4.0. Modified from the original.
 
Include the "modified" note only if you changed something. For a printed label, credit belongs somewhere reasonable for the medium — a product listing, packaging insert, or documentation — not microprinted on the label itself.
 
The license covers copyright only. It grants no trademark or patent rights, and it comes with no warranty of any kind. See [`LICENSE`](LICENSE) for the full legal text. The CC BY grant applies to the artwork and source files in this repository; the fonts listed above are third-party works under their own separate terms and are not covered by it.
 
## Not affiliated
 
This project is not affiliated with, endorsed by, or connected to Nintendo, Sega, or any other console manufacturer. All console names, product names, and marks are the property of their respective owners and are used here descriptively, to identify which hardware each label belongs to.
 
These files are recreations intended for restoration and replacement of missing or damaged labels on hardware you already own. They are not represented as authentic manufacturer labels, and they should not be used to pass off hardware as something it isn't.
