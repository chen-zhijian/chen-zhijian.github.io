# Zhijian Chen’s personal website

[Visit the website](https://chen-zhijian.github.io/)

This responsive academic homepage collects five mathematical research projects. It is a static GitHub Pages site: all page content and styling are in `index.html`. No installation or build step is needed to edit or preview it.

## Research repositories

- [Kobayashi chains](https://github.com/chen-zhijian/kobayashi-chains)
- [Plurisubharmonic exhaustions](https://github.com/chen-zhijian/psh-exhaustion)
- [Harmonic direct images](https://github.com/chen-zhijian/harmonic-direct-images) — with Zhuo Liu and Chenghao Qing
- [Le Potier isomorphisms](https://github.com/chen-zhijian/le-potier-isomorphisms) — with Zhuo Liu and Chenghao Qing
- [Nadel vanishing](https://github.com/chen-zhijian/nadel)

## Preview and edit locally

1. Open `index.html` in a browser.
2. Edit the same file in a text editor. Each project is marked by a comment; the colors and layout are in the `<style>` section near the top.
3. Refresh the browser and check the page at desktop and mobile widths.
4. Review, commit, and push the website changes to `main`, then check the GitHub Pages deployment and the live page.

## Keep the manuscripts and website in sync

The website links directly to manuscript PDFs in the research repositories. It does not keep separate PDF copies.

For harmonic direct images, Le Potier isomorphisms, and Nadel vanishing, the owner maintains the manuscripts in their original local LaTeX files. Automatic syncing is configured to check for changes every 15 minutes while the owner's computer and synchronization service are available. Successful runs publish each packaged source, rebuilt `papers/paper_v1.pdf`, and build manifest together. Failed builds leave the last published manuscript in place. The stable PDF links reach new revisions without copying PDFs into this website repository.

When one of these manuscripts changes, the maintenance agent reviews its title, author credits, summary, and scope notes in `index.html` against the revised source, and publishes website updates where needed. The website's update date is refreshed when its content changes. Compilation and consistency checks are not mathematical proof verification, and the sync process does not reconstruct or regenerate historical AI conversation or usage records.

Other contributors can follow the research repository's documented build procedure, inspect the PDF, run its verification script, and commit the source, PDF, and build manifest together. Coordinate manuscript revisions with the owner so the original source and repository remain consistent. Update and push this website repository if the corresponding title, author credit, summary, scope, or link path changes, then check the live page and its paper link. A local source edit is not published until the corresponding repository is pushed.

For the Kobayashi and plurisubharmonic exhaustion projects, preserve the existing PDF paths linked in `index.html` and follow their repository instructions.

## Research descriptions

The existing Kobayashi and plurisubharmonic exhaustion descriptions retain the scope recorded on 23 October 2026. The three additional descriptions and their author credits were checked against the supplied manuscript sources on 24 October 2026.

- The Kobayashi double-logarithmic estimate is specific to its obstruction family; the optimal approximation rate is left open. Its source leaves author metadata unset, so the website does not add a manuscript byline.
- The plurisubharmonic exhaustion draft does not resolve the general surface regularization problem.
- The harmonic direct-image manuscript retains its infinitesimal-triviality, cohomology, and harmonic-variation hypotheses and attributes its extensions to established curvature and estimate methods.
- The Le Potier manuscript distinguishes weighted canonical results under semipositivity assumptions from unweighted differential-form results for locally free sheaves.
- The Nadel note derives vanishing from stated analytic inputs and retains the positivity requirements near the singular locus.

The site presents research drafts and notes. Development and review records are linked where available; it does not claim that every project has a complete AI interaction history or a proof-assistant formalization.
