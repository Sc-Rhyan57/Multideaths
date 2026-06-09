# Summary of updates  — Multideaths


# Update 09-06-2026

## What has changed?

- Fixed tag filtering system
- Ranking now resets from #1 when filtering
- New alphabetical tie-breaking system

## News

### Update banner
The site now displays a popup when there's new content. You're seeing it now!

---

## **Changes made to the page**

### Correct filtered ranking
When activating a filter by tag (e.g., `LEGIT`), the filtered players are **reordered and renumbered from #1**. Previously, the filter showed the global rank (#6, #12...), now it shows #1, #2, #3 within the category.

### Alphabetical tiebreaker
Players with the same number of deaths are sorted alphabetically by name (A → Z). This eliminates the bug where the site repeatedly notified that one player had overtaken another when...

### New player animation
When the scoreboard updates and detects players that weren't there before, they enter the screen with a sliding animation from the left.

### separate layoutId
The visual conflict that caused glitches in the cards was corrected by separating the `layoutId` of the top 3 (`top3-card-`) and the list (`list-card-`), which previously shared the same identifier and caused animation issues.

### Page does not reset on automatic refresh.
The automatic refresh every 30 seconds no longer resets the current page in the pagination or closes the profile being viewed.

### Mobile responsiveness
All components have been set with `sm:` breakpoints to function correctly on small screens without breaking the layout.


![Vem vem vem comer minha xota](https://raw.githubusercontent.com/Msdoors/Msdoors.gg/refs/heads/main/imagens/web/nyan-cat.gif)
``multideaths by rhyan57 ;D``
