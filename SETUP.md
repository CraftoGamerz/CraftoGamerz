# CraftoGamerz GitHub profile refresh

## Files

- `README.md` — replace the README in `CraftoGamerz/CraftoGamerz` with this file.
- `assets/profile-banner.svg` and `assets/profile-footer.svg` — custom vector graphics used by the README.
- `.github/workflows/snake.yml` — optional workflow that generates the contribution-snake SVGs for the collapsible easter egg.

## Install

1. Open https://github.com/CraftoGamerz/CraftoGamerz.
2. Replace its root `README.md` with this package's `README.md`.
3. Add the `assets` folder to the repository root, preserving both SVG filenames.
4. Add `.github/workflows/snake.yml` at that exact path, or replace the existing snake workflow with this one.
5. Commit and push to `main`.
6. To enable the hidden snake easter egg, open the repository's **Settings → Actions → General** and ensure the workflow token is allowed to write repository contents. Then use **Actions → Generate contribution snake → Run workflow**. The image should appear after the run succeeds and publishes the `output` branch.

## Notes

- The profile-view counter, commit/streak cards, activity graph, language-rank card, trophy wall, random joke API and fake progress bars were removed.
- The featured project descriptions link to public repositories and are based on their current READMEs. Forked/less-documented repositories are not presented as headline projects.
- GitHub profile READMEs do not support arbitrary JavaScript or custom CSS. This version uses supported Markdown/HTML, collapsible `<details>` sections, Mermaid diagrams, GIF/SVG artwork, badges and clickable links for interaction.
- The typing animation, skill icons and badges load from external services. The two custom vector graphics are hosted in your own profile repository, so they do not depend on a third-party banner generator.
