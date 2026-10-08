# Czaruś — Empik banner

- Asset: `czarus-empik-v1.webp`, 1280 × 200 px (6.4:1), rendered at 320 × 50 dp.
- Generated with the built-in `imagegen` tool; exported from the central strip to WebP.
- Cover reference: https://cloud-cdn.virtualo.pl/covers/large/1124422.jpg
- Book information: https://virtualo.pl/ebook/czarus-chlopiec-ktorego-mysli-biegna-szybciej-niz-nozki-ksiazka-o-adhd-i-i682541/
- Destination: the Empik product URL in `../ads-config.json` (search tracking omitted).
- Configuration version 4 pauses house ads (0% impressions) and enables AdMob for all ad requests. The campaign asset and item are retained for later reactivation. Builds must support house ads and have remote ads enabled.
- The app fetches configuration from `main` at startup; publishing requires both the asset and configuration on `main`. Offline devices may continue using cached configuration until a successful fetch.

## Generation prompt

Create a 3:1 landscape image used as a production template for a very thin 6.4:1 banner. IMPORTANT geometrical requirement: TOP 27% and BOTTOM 27% must be entirely EMPTY plain cream paper, no artwork, no letters. All ad content must fit inside CENTER 46% horizontal band, about 330 pixels tall on 2172x724 canvas. Reduce text height substantially to obey this. At left a SMALL smiling blond boy head in mustard sweater and tiny 'REKLAMA' beside it, all within that center band. Center two lines, each only 100px high: 'Poznaj Czarusia' and 'Książka o ADHD i emocjach'. Right a compact teal CTA badge 250px tall inside center band with 'Sprawdź' then 'w Empiku'. Use entire WIDTH edge to edge but ONLY central 46% HEIGHT. Reference image provides warm cream handmade paper collage, navy type, teal mustard colors and recognizable boy. No objects in top or bottom 27%, no stars or butterflies above band. Do not enlarge text to fill canvas: this design must look like a very thin banner surrounded by blank space. Exact Polish spelling. This band will be extracted by a standard asset export to 1280x200.
