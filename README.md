# Wish2Shelf: Wish Cabinet (心愿柜) prototype

Clickable prototype for the Chi-Forest (元气森林) smart cabinet "Machine Managing Competition".

Students scan the QR sticker on a cabinet and wish for a missing product, first by category and then by brand. If the product isn't listed, they can type its name or upload a photo of the label. A product unlocks at **10 wishes**. Operators see demand by location, restock the product, and every wisher gets a message.

## Try it

- **Live:** open the GitHub Pages link for this repo on your phone.
- **Offline:** download `index.html` and open it in any browser.

Use the bar at the top to switch between the **Student app** and the **Operator console**, and between **EN** and **中文**.

Demo links:
- `#tc07`: the student page for cabinet TC-07 (Library 1F). Hot Soy Milk is at 9/10, so one wish unlocks it.
- `#operator`: the operator console (all locations → campus → cabinet).

## Notes

- This is a single HTML file with no build step and no backend. Data is kept in memory and resets when you reload.
- All numbers, locations and brand names are placeholders for the demo.
- The "AI restock assistant" uses simple rules for now.
