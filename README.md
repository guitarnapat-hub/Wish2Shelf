# Wish2Shelf: Wish Cabinet (心愿柜) prototype

Clickable prototype for the Chi-Forest (元气森林) smart cabinet "Machine Managing Competition".

Students scan the QR sticker on a cabinet and wish for a missing product, first by category and then by brand. If the product isn't listed, they can type its name or upload a photo of the label. A product unlocks at **10 wishes**. Operators see demand by location, restock the product, and every wisher gets a message.

## Try it

- **Live:** open the GitHub Pages link for this repo. On a computer it shows inside a phone frame; on a phone it opens full screen.
- **Offline:** download `index.html` and `app.html` into the same folder and open `index.html`, or just open `app.html` on its own.

On a computer, use the buttons above the phone to switch between the **Student app** and the **Operator console**, or reset the demo. Switch between **EN** and **中文** in the app's header.

## Files

- `index.html`: the phone-frame page. On screens narrower than 600px it sends you straight to `app.html`.
- `app.html`: the prototype itself.

Demo links:
- `#tc07`: the student page for cabinet TC-07 (Library 1F). Hot Soy Milk is at 9/10, so one wish unlocks it.
- `#operator`: the operator console (all locations → campus → cabinet).

## Notes

- There is no build step and no backend. Data is kept in memory and resets when you reload.
- All numbers, locations and brand names are placeholders for the demo.
- The "AI restock assistant" uses simple rules for now.
