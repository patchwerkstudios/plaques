# Patchwerk Plaques — upload these files

Everything in this folder is the live site. Drag the **whole folder contents** into the
GitHub repo — the 22 plaque pages, `index.html`, and the `videos` folder.

Nothing else from the Plaques directory is needed. The session-report scans and the
Patchwerk logo are already embedded inside each page, so there is no images folder.
`videos/` must keep its name and stay beside the HTML or the four pages with clips break.

## Upload

1. github.com → your `plaques` repo → **Add file → Upload files**
2. Drag in all 23 `.html` files **and** the `videos` folder
3. **Commit changes**
4. Settings → Pages → Source *Deploy from a branch*, Branch *main*, folder */ (root)*

Give it a minute, then the collection is at `https://USERNAME.github.io/plaques/`

## URLs for the NFC tags

Program each sticker with its page URL. Base is `https://USERNAME.github.io/plaques/`

| Plaque | Artist | File |
|---|---|---|
| Collection home | — | `index.html` |
| Better Dayz | 2Pac | `2pac-better-dayz.html` |
| Dangerously in Love | Beyoncé | `beyonce-dangerously-in-love.html` |
| The Git Up | Blanco Brown | `blanco-brown-the-git-up.html` |
| The Adventures of Bobby Ray | B.o.B | `bob-adventures-of-bobby-ray.html` |
| The Sound of Revenge | Chamillionaire | `chamillionaire-sound-of-revenge.html` |
| Down for Life | D4L | `d4l-down-for-life.html` |
| Elevators (Me & You) | OutKast | `elevators.html` |
| Let's Get It: Thug Motivation 101 | Young Jeezy | `jeezy-thug-motivation-101.html` |
| Evolver | John Legend | `john-legend-evolver.html` |
| Back for the First Time | Ludacris | `ludacris-back-for-the-first-time.html` |
| Fever | Megan Thee Stallion | `megan-thee-stallion-fever.html` |
| Under Construction | Missy Elliott | `missy-elliott-under-construction.html` |
| My Turn | Lil Baby | `my-turn.html` |
| Untitled | Nas | `nas-untitled.html` |
| No Hands | Waka Flocka Flame feat. Roscoe Dash & Wale | `no-hands-song.html` |
| Pick Up the Phone | Travis Scott & Young Thug ft. Quavo | `pick-up-the-phone.html` |
| So So Def Bass All-Stars | Various Artists &middot; So So Def Recordings | `so-so-def-bass-all-stars.html` |
| Trap Muzik | T.I. | `ti-trap-muzik.html` |
| Rodeo | Travis Scott | `travis-scott-rodeo.html` |
| Flockaveli | Waka Flocka Flame | `waka-flocka-no-hands.html` |
| Just Whitney | Whitney Houston | `whitney-houston-just-whitney.html` |
| My Krazy Life | YG | `yg-my-krazy-life.html` |

## Videos in this upload (5)

- `videos/bob-b-rich-2022.mp4`
- `videos/jeezy-drink-champs.mp4`
- `videos/jeezy-haircut-coach-k.mp4`
- `videos/so-so-def-bass-all-stars.mp4`
- `videos/waka-no-hands.mp4`

Two more are referenced but not included, because the files aren't on the drive —
`videos/outkast-elevators.mp4` and `videos/werking-on-elevators.mp4`. Until those are
added, the Elevators page shows a dashed placeholder where each clip goes, rather than a
broken player. Drop them into `videos/` and re-upload and they'll appear.

## Changing a page later

Edit the JSON in `Plaques/content/`, run `python3 build_plaques.py`, then re-upload the
changed `.html`. **The NFC stickers never need reprogramming** — they store a URL, not
the page.
