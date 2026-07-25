# Project key art — drop images here

Save one image per project into this folder, named **exactly** after the
project's `id` in `content/v1/projects.json`:

| File to save | Project |
|---|---|
| `the-unnamed.png` | The Unnamed |
| `tactical-villagers.png` | Tactical Villagers |
| `karma-system.png` | Karma System |
| `lucky-dirt.png` | Lucky Dirt |
| `the-unnamed-skins.png` | The Unnamed — Skins |

`.jpg` and `.webp` work too — the extension doesn't matter, the name does.

## What works best

**16:9, ideally 1280×720.** The card container is exactly 16:9, so art at that
ratio is shown whole with nothing cropped off.

Other ratios still work — they get centre-cropped to fit — so send what you
have rather than waiting until you've made something perfect. Just keep the
important part (title, character, logo) near the middle.

A few things worth knowing:

- **Keep text away from the edges.** On a narrow phone the card is roughly
  320px wide, so anything small gets unreadable and anything near the edge
  risks being clipped.
- **Under ~500 KB each.** These download over mobile data every time someone
  installs the app. 1280×720 as a JPG at 80% quality usually lands well under
  that.
- **Your CurseForge project icons are 400×400 squares** — usable, but they'll
  be cropped to a letterbox. Purpose-made wide art looks considerably better.

## What happens next

Once the files are here, tell me and I'll:

1. Check each one's real format and dimensions (your logo turned out to be a
   WebP named `.png`, so this is worth doing)
2. Add the `coverImage` URL to each project in `projects.json`

Then you upload this `covers` folder into the `ironveil-content` repo under
`v1/`, so the paths end up as `v1/covers/the-unnamed.png`.

Hosting them in the content repo means swapping artwork later never needs an
app rebuild — same as your text.

## Projects with no art yet

They fall back to the project's initial on a branded block. That's deliberate
and looks fine, so there's no rush to fill every slot at once.
