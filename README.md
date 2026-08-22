# 友人 (Eugene) — Japanese CVVC UTAU Voicebank

Official repository for **友人 (Eugene)**, a Japanese CVVC UTAU voicebank by **Ilya Minin (Eli)**.

> A warm, intimate voice with a slightly uncanny edge — built from preserved fragments, reconstructed phonemes, and extensive post-production.

## Quick Links

- [Official Website](https://eliasadams.github.io/eugene-utau/)
- [Download](https://github.com/ELIASADAMS/eugene-utau/releases)
- [BowlRoll](https://bowlroll.net/file/354839)
- [UTAU Wiki](https://utau.fandom.com/wiki/%E5%8F%8B%E4%BA%BA)
- [Documentation](docs/README.md)
- [Official Manual](docs/MANUAL.md)
- [Technical Specifications](docs/VOICEBANK.md)
- [Usage Guide](docs/USAGE.md)
- [Character](docs/CHARACTER.md)
- [Media Archive](docs/MEDIA.md)
- [Future Revisions](docs/RELEASES.md)
- [Terms of Use](TERMS.md)
- [Machine-readable Metadata](voicebank.json)
- [Changelog](changelog.html)

## Voicebank Specifications

| Property | Official value |
|---|---|
| Name | 友人 (Eugene) |
| Engine | UTAU / OpenUtau |
| Language | Japanese |
| Recording method | CVVC |
| Encoding | Romaji-encoded, CVVC aliased |
| Pitches | C3 / G3 / C4 |
| Range | G#3–D3 |
| Optimum BPM | 70–120 |
| Genres | Dark pop / Industrial / Experimental |
| Primary recommendation | TIPS |
| Other recommendations | Moresampler / WORLDLINE-R / wavtool4vcv |

See [docs/VOICEBANK.md](docs/VOICEBANK.md) for the complete technical specification and expression notes from the official manual.

## About

友人 (Eugene) is a Japanese UTAU CVVC voicebank with a warm, intimate tone and a slightly uncanny edge. The voice was created from a carefully preserved collection of remnants, rebuilt phonemes, and heavily post-produced material, giving the feeling of someone speaking back through layers of memory.

The voice is gentle and expressive, with a natural softness in sustained phrases. It works especially well for melancholic songs, slow emotional lines, and lyrical arrangements.

## Installation

1. Download the latest release from [GitHub Releases](https://github.com/ELIASADAMS/eugene-utau/releases) or the [BowlRoll distribution](https://bowlroll.net/file/354839).
2. Extract the voicebank archive.
3. Install it into your UTAU `voice` directory, or import it into OpenUtau according to your normal voicebank workflow.

## Usage

For the recommended setup, start with **TIPS**. Moresampler, WORLDLINE-R, and wavtool4vcv are also supported recommendations from the official manual.

The bank is intended for expressive Japanese vocal synthesis and performs especially well in dark pop, industrial, and experimental material.

See [docs/USAGE.md](docs/USAGE.md) for the growing practical guide.

## Character

友人 (Eugene) is a non-binary character who uses he/him pronouns. The official character profile describes him as a quiet presence associated with unfinished things, memory, disappearance, and the feeling of someone returning from somewhere that cannot be named.

See [docs/CHARACTER.md](docs/CHARACTER.md) for the character archive and [docs/MEDIA.md](docs/MEDIA.md) for official works featuring the voice.

## Terms of Use

The official terms are maintained in [TERMS.md](TERMS.md). **Please use that document as the canonical version rather than copying or modifying the rules elsewhere.**

## Credits

- **Creator:** Ilya Minin (Eli)
- **Voice Provider:** Possum Eugene
- **Illustrator:** Ilya Minin (Eli)
- **OTO / Technical:** eikton

## Repository Structure

- `docs/` — canonical documentation and future archive
- `assets/` — organized home for future character/promotional assets
- `voicebank.json` — machine-readable metadata
- `TERMS.md` — canonical terms
- `index.html`, `info.html`, `download.html`, `changelog.html`, `contact.html` — GitHub Pages site
- `sample.wav`, `solfege.wav` — current audio samples

The existing root-level web/assets are intentionally preserved for now so the live site remains stable. A later asset migration can move them into `assets/` together with all site path updates.

## Contact

- **Ilya Minin (Eli):** https://t.me/ilyaminineli
- **eikton:** https://t.me/e1kton

## Source of Truth

The supplied official character/voicebank manual is the authoritative source for released-bank metadata, technical specifications, credits, and terms. Repository pages should link to canonical documentation instead of maintaining competing values.
