# School Taster Day Lock Website

A lightweight, touch-friendly single-page website designed for GitHub Pages and iPads.

## Included behaviour
- 7 combination-lock stages in the correct sequence.
- Default light-blue screen with stage prompt.
- Green success state for 2 seconds, then moves to the next password.
- Red failure state with a shake animation for 2 seconds, then resets to the default screen.
- Final completion state stays green, removes the locks with an animation, and shows **System restored!** plus **Congratulations!**
- Responsive layout for tablets and smaller screens.

## GitHub Pages upload
1. Create a new GitHub repository.
2. Upload `index.html` to the root of the repository.
3. In GitHub, open **Settings → Pages**.
4. Set the source to **Deploy from a branch**.
5. Choose your main branch and the **/(root)** folder.
6. Save and wait for GitHub Pages to publish the site.

## Optional edits
- Passwords are stored near the top of the `<script>` section in the `codes` array.
- Colours are defined in the CSS variables at the top of the `<style>` section.