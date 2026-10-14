# CraftoGamerz GitHub profile refresh

## Files

- `README.md` — replace the README in `CraftoGamerz/CraftoGamerz` with this file.
- `assets/profile-banner.gif` — a 48-frame, continuously looping neural-network header animation.
- `assets/profile-banner.svg` and `assets/profile-footer.svg` — editable vector source/fallback graphics used by the profile design.
- `.github/workflows/snake.yml` — automatically generates the animated contribution-snake SVGs; the README section is always visible, not collapsed.

## Install

1. Open https://github.com/CraftoGamerz/CraftoGamerz.
2. Replace its root `README.md` with this package's `README.md`.
3. Add the `assets` folder to the repository root, preserving `profile-banner.gif`, `profile-banner.svg` and `profile-footer.svg`.
4. Add `.github/workflows/snake.yml` at that exact path, or replace the existing snake workflow with this one.
5. Commit and push to `main`.
6. The snake workflow runs automatically after you push the README/workflow. In **Settings → Actions → General**, make sure GitHub Actions is enabled and the workflow token can write repository contents. If the snake still does not appear, open **Actions → Generate contribution snake → Run workflow** and wait for a successful run; it publishes `github-snake.svg` and `github-snake-dark.svg` to the `output` branch.

## Notes

- The profile-view counter, commit/streak cards, activity graph, language-rank card, trophy wall, random joke API and fake progress bars were removed.
- The featured project descriptions link to public repositories and are based on their current READMEs. Forked/less-documented repositories are not presented as headline projects.
- GitHub profile READMEs do not support arbitrary JavaScript or custom CSS. This version uses supported Markdown/HTML, collapsible `<details>` sections, Mermaid diagrams, GIF/SVG artwork, badges and clickable links for interaction.
- The typing animation, skill icons and badges load from external services. The looping header GIF and both vector graphics are hosted in your own profile repository, so the neural-network animation does not depend on a third-party banner generator.
