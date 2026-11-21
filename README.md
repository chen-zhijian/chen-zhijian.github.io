# Zhijian Chen’s personal website

[Visit the website](https://chen-zhijian.github.io/)

This responsive academic homepage collects seven mathematical research projects, including a survey and problem collection. It is a static GitHub Pages site: all page content and styling are in `index.html`. No installation or build step is needed to edit or preview it.

## Research repositories

- [Kobayashi chains](https://github.com/chen-zhijian/kobayashi-chains)
- [Plurisubharmonic exhaustions](https://github.com/chen-zhijian/psh-exhaustion) — with Bo Xiao
- [Surface regularization](https://github.com/chen-zhijian/surface-regularization) — with Bo Xiao
- [Direct-image descent](https://github.com/chen-zhijian/direct-image-descent) — with Zhuo Liu and Chenghao Qing
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
| Surface regularization | [papers/surface-regularization.pdf](papers/surface-regularization.pdf) |
| Direct-image descent | [papers/direct-image-descent.pdf](papers/direct-image-descent.pdf) |
| Le Potier isomorphisms | [papers/le-potier-isomorphisms.pdf](papers/le-potier-isomorphisms.pdf) |
| Nadel vanishing | [papers/nadel.pdf](papers/nadel.pdf) |
| Complex variables problem collection | [papers/scv-problem-list.pdf](papers/scv-problem-list.pdf) |

When a manuscript PDF is updated in its research repository, replace the corresponding website copy with that published PDF and refresh its source/hash record in the manifest. Check that the copy matches the source, commit and push the website changes, and verify the direct PDF link after GitHub Pages deploys. Keep the website paths above stable. The website copies do not update merely because a research repository changes.

For Le Potier isomorphisms and Nadel vanishing, the owner maintains the manuscripts in their original local LaTeX files. Automatic syncing is configured to check for changes every 15 minutes while the owner's computer and synchronization service are available. Successful runs publish each packaged source, rebuilt `papers/paper_v1.pdf`, and build manifest together. Failed builds leave the last published manuscript in place. The stable research-repository links reach new revisions. The separate website PDF copies must also be refreshed using the procedure above; the existing manuscript synchronization does not establish automatic synchronization of these website copies.

The direct-image project was renamed from `harmonic-direct-images` to `direct-image-descent` on 30 October 2026. Its current manuscript is `papers/paper_v2.pdf`, built from `papers/src/direct_image_descent.tex`; the original `papers/paper_v1.pdf` and `papers/src/main.tex` remain historical v1 files. The homepage uses the new repository and the website copy at `papers/direct-image-descent.pdf`. Keep `papers/harmonic-direct-images.pdf` as an identical copy of the current PDF for existing links, and update both files and their manifest records together. The previously documented 15-minute workflow targeted v1; do not assume it has been retargeted to the new source, repository name, or PDF path. Follow the current repository build and verification instructions for subsequent v2 updates.

When one of these manuscripts changes, the maintenance agent reviews its title, author credits, summary, and scope notes in `index.html` against the revised source, and publishes website updates where needed. The website's update date is refreshed when its content changes. Compilation and consistency checks are not mathematical proof verification, and the sync process does not reconstruct or regenerate historical AI conversation or usage records.

Other contributors can follow the research repository's documented build procedure, inspect the PDF, run its verification script, and commit the source, PDF, and build manifest together. Coordinate manuscript revisions with the owner so the original source and repository remain consistent. Refresh and publish the website PDF copy when the manuscript PDF changes, and update the project entry if the corresponding title, author credit, summary, scope, or link path changes. Then check the live page, its research-repository link, and its direct PDF link. A local source edit is not published until the corresponding repository is pushed.

For the Kobayashi project, preserve the existing research-repository PDF path used by **Read paper**. The title and **Read paper** links for **Regularity of plurisubharmonic exhaustions and related problems** point to `papers/paper_v6.pdf` in the research repository. The current source is `papers/src/main.tex`. The website serves the same PDF at `papers/psh-exhaustion.pdf`. The research repository also keeps the five earlier PDFs, through `papers/paper_v5.pdf` dated 8 November 2026. Follow the respective repository instructions and refresh the website copies listed above.

For the complex variables problem collection, keep the current survey at `papers/scv-problem-list.pdf` and its source at `papers/src/scv-problem-list.tex` in the [research repository](https://github.com/chen-zhijian/scv-problem-list). The website keeps **Read survey** and **Problem statistics** linked to that repository, while **PDF** opens the website copy at `papers/scv-problem-list.pdf`. When the survey changes, update its source, PDF, and statistics together, refresh the website PDF copy and manifest, then review the page count, total number of problems, and status counts on this homepage.

## Research descriptions

The Kobayashi description retains the scope recorded on 23 October 2026.

The plurisubharmonic exhaustion entry describes the 45-page version 6 dated 13 November 2026. Chen and Xiao answer Nakano’s smoothing question negatively in dimensions at least three. In dimension two, they prove that a continuous plurisubharmonic exhaustion implies the existence of a smooth one on the complement of the support of a nonzero effective Weil divisor in a connected normal compact Kähler surface. This also holds on every normal quasi-projective surface. Proposition 5.7 gives a reduced, irreducible, nonnormal quasi-projective surface with a continuous plurisubharmonic exhaustion on which every real-valued ambient $C^1$ plurisubharmonic function is constant. Version 6 drops version 5’s separate subsections on numerical existence criteria and square-zero curves.

For a holomorphic vector bundle $E$ over a compact complex manifold, a $C^r$ or locally Hölder plurisubharmonic exhaustion of the total space of $E^*$ exists exactly when the line bundle $\mathcal O(1)$ on the projective bundle of lines in $E^*$ admits a semipositive Hermitian metric of the same regularity. For arbitrary plurisubharmonic exhaustions, the condition is the existence of a metric with locally bounded plurisubharmonic weights. The line-bundle theorem also treats real analytic regularity and establishes the seminegative converse discussed by Ohsawa.

Building on Vîjîitu’s work, version 6 proves holomorphic convexity for reduced complex spaces with a possibly discontinuous plurisubharmonic exhaustion and a holomorphic map to a Stein space such that each irreducible component of every reduced fiber is compact or Stein. The corollaries give a higher-dimensional analogue of Ohsawa’s criterion and extend Vîjîitu’s rank criterion to arbitrary plurisubharmonic exhaustions. For the original and modified Grauert examples, the authors answer Tosatti’s bounded-potential question, as reported by Zhang, and strengthen Koike’s obstruction to $C^1$ regularity. Keep the repository PDF, website PDF, page count, and checksum record synchronized.

The direct-image descent entry and its coauthor credits were checked against the v2 source dated 30 October 2026; its title, summary, scope, repository links, and website PDF copies were synchronized with that revision. The Le Potier and Nadel descriptions and their author credits were checked against the supplied manuscript sources on 24 October 2026. The complex variables survey description was checked against the revised TeX and PDF dated 27 October 2026. The Suita inequality attribution places Błocki (online 2012; print 2013) first for bounded planar domains, followed by Guan–Zhou (2012) for open Riemann surfaces. A cited remark explains Błocki's capacity-dependent extension estimate, its planar Suita application, and the sharpened estimates and auxiliary weights used in his proof. The same revision compares the survey with bibliography sources [1]–[4], selectively restores omitted subquestions and broader formulations, records historical prize attributions, and adds precise source citations and five references. The restored material remains within the existing numbered entries.

- The Kobayashi double-logarithmic estimate is specific to its obstruction family; the optimal approximation rate is left open. Its source leaves author metadata unset, so the website does not add a manuscript byline.
- Chen and Xiao’s separate companion preprint proposes regularization on every connected normal complex surface, with smoothness in local ambient embeddings. Its Remark 6.2 discusses the cuspidal obstruction from Proposition 5.7 of the plurisubharmonic exhaustion paper. The proposed proof awaits independent mathematical review. [Read version 2, dated 20 November 2026](https://github.com/chen-zhijian/surface-regularization/blob/main/papers/paper_v2.pdf).
- The direct-image descent manuscript treats prescribed metrics and two extremal product bidegree ranges. Its singular product statements retain multiplier ideals and minimum weighted fiberwise norms. Non-product descent for arbitrary singular semipositive line metrics is restricted to top adjoint degree. The smooth adjoint metric is identified with the Mourougane–Takayama metric, and counterexamples exclude unrestricted degreewise descent. Smooth dual Nakano positivity under infinitesimal triviality remains a complementary result with its stated cohomology hypotheses.
- The Le Potier manuscript distinguishes weighted canonical results under semipositivity assumptions from unweighted differential-form results for locally free sheaves.
- The Nadel note derives vanishing from stated analytic inputs and retains the positivity requirements near the singular locus.
- The complex variables survey has 39 pages, 161 references, and 139 numbered problems in seven subject areas: 36 closed problems, 52 with partial results, and 51 wide-open problems. Counts follow the manuscript's current classifications and treat each numbered Problem as one entry, including entries that combine several source questions. The 25 October literature audit added Oka, logarithmic plurigenera, Griffiths-positivity, and Fano-curve material; the companion Iitaka paper supplies the abundance paper's assumption, and their combined claim is distinguished from independent verification. The full formulation of Problem 6.8 remains open, so the category totals are unchanged.

The site presents research drafts, notes, and surveys. Development and review records are linked where available; it does not claim that every project has a complete AI interaction history or a proof-assistant formalization.
