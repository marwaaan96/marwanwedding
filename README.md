# Lifetime Contract Invitation

This project contains a one-page wedding invitation for Marwan and Nourhan, designed as a premium lifetime contract.

## Preview

1. Open `index.html` in any modern browser.
2. Review the desktop layout first.
3. Reduce the browser width to confirm the mobile layout stacks cleanly.

## Replace the photo placeholder

1. Add your final image to `assets/`, for example `assets/couple-photo.jpg`.
2. In `index.html`, replace this block:

```html
<div class="photo-frame-inner">
    <p class="photo-label">Reserved for the final couple photo</p>
    <p class="photo-names">Marwan x Nourhan</p>
</div>
```

with this:

```html
<img class="photo-image" src="assets/couple-photo.jpg" alt="Marwan and Nourhan">
```

## Export to PDF

1. Open `index.html` in the browser.
2. Press `Ctrl+P`.
3. Set destination to `Save as PDF`.
4. Enable `Background graphics`.
5. Keep margins at default or minimum, then save.

## Included files

- `index.html` for the invitation structure and text.
- `styles.css` for the luxury contract styling, mobile behavior, and print output.
- `assets/` for the final couple photo.