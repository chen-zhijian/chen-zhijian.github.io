# Zhijian Chen’s personal website

[Visit the website](https://chen-zhijian.github.io/)

This responsive academic homepage collects six mathematical research projects, including a survey and problem collection. It is a static GitHub Pages site: all page content and styling are in `index.html`. No installation or build step is needed to edit or preview it.

## Research repositories

- [Kobayashi chains](https://github.com/chen-zhijian/kobayashi-chains)
- [Plurisubharmonic exhaustions](https://github.com/chen-zhijian/psh-exhaustion) — with Bo Xiao
- [Harmonic direct images](https://github.com/chen-zhijian/harmonic-direct-images) — with Zhuo Liu and Chenghao Qing
- [Le Potier isomorphisms](https://github.com/chen-zhijian/le-potier-isomorphisms) — with Zhuo Liu and Chenghao Qing
- [Nadel vanishing](https://github.com/chen-zhijian/nadel)
- [Some problems in complex variables](https://github.com/chen-zhijian/scv-problem-list) — survey by Zhijian Chen

## Preview and edit locally

1. Open `index.html` in a browser.
2. Edit the same file in a text editor. Each project is marked by a comment; the colors and layout are in the `<style>` section near the top.
3. Refresh the browser and check the page at desktop and mobile widths.
4. Review, commit, and push the website changes to `main`, then check the GitHub Pages deployment and the live page.

## Keep the manuscripts and website in sync

Each project has a **Read paper** (or **Read survey**) link to its manuscript in the research repository, a **Repository** link, and a **PDF** link that opens a copy hosted on this website. The research repositories remain the source of the manuscripts. Website PDF copies are stored under `papers/`; `papers/manifest.json` records their source files and hashes.

| Project | Website PDF |
| --- | --- |
| Kobayashi chains | [papers/kobayashi-chains.pdf](papers/kobayashi-chains.pdf) |
| Plurisubharmonic exhaustions | [papers/psh-exhaustion.pdf](papers/psh-exhaustion.pdf) |
| Harmonic direct images | [papers/harmonic-direct-images.pdf](papers/harmonic-direct-images.pdf) |
| Le Potier isomorphisms | [papers/le-potier-isomorphisms.pdf](papers/le-potier-isomorphisms.pdf) |
| Nadel vanishing | [papers/nadel.pdf](papers/nadel.pdf) |
| Complex variables problem collection | [papers/scv-problem-list.pdf](papers/scv-problem-list.pdf) |

When a manuscript PDF is updated in its research repository, replace the corresponding website copy with that published PDF and refresh its source/hash record in the manifest. Check that the copy matches the source, commit and push the website changes, and verify the direct PDF link after GitHub Pages deploys. Keep the website paths above stable. The website copies do not update merely because a research repository changes.

For harmonic direct images, Le Potier isomorphisms, and Nadel vanishing, the owner maintains the manuscripts in their original local LaTeX files. Automatic syncing is configured to check for changes every 15 minutes while the owner's computer and synchronization service are available. Successful runs publish each packaged source, rebuilt `papers/paper_v1.pdf`, and build manifest together. Failed builds leave the last published manuscript in place. The stable research-repository links reach new revisions. The separate website PDF copies must also be refreshed using the procedure above; the existing manuscript synchronization does not establish automatic synchronization of these website copies.

When one of these manuscripts changes, the maintenance agent reviews its title, author credits, summary, and scope notes in `index.html` against the revised source, and publishes website updates where needed. The website's update date is refreshed when its content changes. Compilation and consistency checks are not mathematical proof verification, and the sync process does not reconstruct or regenerate historical AI conversation or usage records.

Other contributors can follow the research repository's documented build procedure, inspect the PDF, run its verification script, and commit the source, PDF, and build manifest together. Coordinate manuscript revisions with the owner so the original source and repository remain consistent. Refresh and publish the website PDF copy when the manuscript PDF changes, and update the project entry if the corresponding title, author credit, summary, scope, or link path changes. Then check the live page, its research-repository link, and its direct PDF link. A local source edit is not published until the corresponding repository is pushed.

For the Kobayashi and plurisubharmonic exhaustion projects, preserve the existing research-repository PDF paths used by **Read paper**, follow their repository instructions, and refresh the website copies listed above.

For the complex variables problem collection, keep the current survey at `papers/scv-problem-list.pdf` and its source at `papers/src/scv-problem-list.tex` in the [research repository](https://github.com/chen-zhijian/scv-problem-list). The website keeps **Read survey** and **Problem statistics** linked to that repository, while **PDF** opens the website copy at `papers/scv-problem-list.pdf`. When the survey changes, update its source, PDF, and statistics together, refresh the website PDF copy and manifest, then review the page count, total number of problems, and status counts on this homepage.

## Research descriptions

The existing Kobayashi and plurisubharmonic exhaustion descriptions retain the scope recorded on 23 October 2026. The harmonic direct-image, Le Potier, and Nadel descriptions and their author credits were checked against the supplied manuscript sources on 24 October 2026. The complex variables survey description was checked against the revised TeX and PDF dated 27 October 2026. The Suita inequality attribution distinguishes Błocki's bounded planar case from Guan–Zhou's open Riemann surface case and includes their 2012 reference.

- The Kobayashi double-logarithmic estimate is specific to its obstruction family; the optimal approximation rate is left open. Its source leaves author metadata unset, so the website does not add a manuscript byline.
- The plurisubharmonic exhaustion draft does not resolve the general surface regularization problem.
- The harmonic direct-image manuscript retains its infinitesimal-triviality, cohomology, and harmonic-variation hypotheses and attributes its extensions to established curvature and estimate methods.
- The Le Potier manuscript distinguishes weighted canonical results under semipositivity assumptions from unweighted differential-form results for locally free sheaves.
- The Nadel note derives vanishing from stated analytic inputs and retains the positivity requirements near the singular locus.
- The complex variables survey has 37 pages and 139 numbered problems in seven subject areas: 36 closed problems, 52 with partial results, and 51 wide-open problems. Counts follow the manuscript's current classifications and treat each numbered Problem as one entry, including entries that combine several source questions. The 25 October literature audit added Oka, logarithmic plurigenera, Griffiths-positivity, and Fano-curve material; the companion Iitaka paper supplies the abundance paper's assumption, and their combined claim is distinguished from independent verification. The full formulation of Problem 6.8 remains open, so the category totals are unchanged.

The site presents research drafts, notes, and surveys. Development and review records are linked where available; it does not claim that every project has a complete AI interaction history or a proof-assistant formalization.
