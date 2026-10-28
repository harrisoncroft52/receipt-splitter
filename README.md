# Bill Splitter

Split a shared bill with friends. Enter who's splitting, add the items (type them or paste a receipt), then tap **Divide** and mark who shares each item. The app works out who pays whom with the fewest payments.

Prefer something more fun? Tap **Game Mode** to deal the items out as cards around a table. Swipe a card onto the players who used it (as many as you like), then tap **Confirm**. Swipe a player onto the card to say who paid, shown with a coin. Watch out for boss battles.

## Features

- 2 to 6 people, each with their own colour and avatar (tap an avatar to change its look)
- One person paid, or several bills paid by different people
- Cost field accepts sums like `3*1.15`
- Paste a receipt (on iPhone, copy the text from a photo with Live Text) and it's sorted into items, with unsure lines flagged
- On Settle up, a small "(scroll ↔)" hint shows when the items table is wider than the screen (the Paid by column is off to the right on a phone)
- Tax / tip %, spread in proportion to what each person owes
- Money is worked out in whole cents, so everything adds up exactly
- Game Mode: skippable intro, round table with avatars, boss battles, and every player's hand shown at the end
  - **Who used it:** swipe the card onto one or more players, then **Confirm** (or tap names, or use **Split between…**)
  - **Who paid:** drag a player onto the card (coin icon and coin sound), or use the **Who paid?** button
  - A **?** button at the top explains how it works, and the text at the bottom reminds you
  - **Undo** puts back both who used the card and who paid
- Settings (⚙︎): sound effects and music on/off with volumes, boss every game, and reduce motion
- A small demo receipt (3 items) to try it out
- Saves your bill in the browser, no account or server

## Run it

It's a single file with no build step. Open `index.html` in a browser.

## Add it to an iPhone home screen

Open the GitHub Pages link in Safari, tap **Share → Add to Home Screen**.

## Game Mode keys (desktop)

Arrow keys / Q E Z C add a player, 1–6 toggle a player, A or 0 for everyone, **Enter** to confirm, **P** who paid, **S** split between, **K** skip, **U** undo, **?** help, Esc to leave.

## Testing

- Add `#selftest` to the end of the address to see the built-in checks.
- Add `#boss` to force a boss battle in Game Mode (or turn on **Boss every game** in ⚙︎).

## Credits

Fonts are from Google Fonts (SIL Open Font License). All sounds and music are generated in code with the Web Audio API, and the avatars are drawn in code, so there are no third-party audio or image files.
