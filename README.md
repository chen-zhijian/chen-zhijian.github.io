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

For harmonic direct images, Le Potier isomorphisms, and Nadel vanishing:

1. Update the manuscript source in the relevant research repository.
2. Run that repository’s documented build script and inspect the resulting `papers/paper_v1.pdf`. This path is the stable current-manuscript link, even when the manuscript is revised.
3. Commit and push both the updated source and PDF to the research repository’s `main` branch.
4. Check the paper link on the live website. The existing link reaches the updated PDF at the same path; no website edit is needed for a PDF-only revision.

For the Kobayashi and plurisubharmonic exhaustion projects, preserve the existing PDF paths linked in `index.html` and follow their repository instructions.

Titles, author credits, summaries, scope notes, and the website’s update date are maintained manually in `index.html`. Update and push this website repository whenever those details change, or when a manuscript path changes. A local source edit is not published until the corresponding repository is pushed.

## Research descriptions

The existing Kobayashi and plurisubharmonic exhaustion descriptions retain the scope recorded on 23 October 2026. The three additional descriptions and their author credits were checked against the supplied manuscript sources on 24 October 2026.

- The Kobayashi double-logarithmic estimate is specific to its obstruction family; the optimal approximation rate is left open. Its source leaves author metadata unset, so the website does not add a manuscript byline.
- The plurisubharmonic exhaustion draft does not resolve the general surface regularization problem.
- The harmonic direct-image manuscript retains its infinitesimal-triviality, cohomology, and harmonic-variation hypotheses and attributes its extensions to established curvature and estimate methods.
- The Le Potier manuscript distinguishes weighted canonical results under semipositivity assumptions from unweighted differential-form results for locally free sheaves.
- The Nadel note derives vanishing from stated analytic inputs and retains the positivity requirements near the singular locus.

The site presents research drafts and notes. Development and review records are linked where available; it does not claim that every project has a complete AI interaction history or a proof-assistant formalization.
