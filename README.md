# Zhijian Chen’s personal website

[Visit the website](https://chen-zhijian.github.io/)

This is a small, responsive academic homepage featuring the Kobayashi chains and plurisubharmonic exhaustion research projects. It is a static GitHub Pages site: all page content and styling are in `index.html`. No Python, installation, or build step is needed to edit or preview it.

## Preview and edit locally

1. Double-click `index.html` to open it in your browser.
2. Open the same file in a text editor such as Notepad or Visual Studio Code.
3. Edit the visible text between the HTML tags. Each project is marked by a comment in the source; the colors and layout are in the `<style>` section near the top.
4. Save the file and refresh the browser to see the result.

The paper and overview links point to the PDFs in the two research repositories. Updating a PDF at the same repository path updates what readers reach from this website; you do not need to copy the PDFs into this repository.

## Upload the prepared changes with GitHub Desktop

The prepared repository folder includes its Git history and is already connected to `chen-zhijian/chen-zhijian.github.io`.

1. In GitHub Desktop, select **File → Add local repository**.
2. Choose the prepared `chen-zhijian.github.io` folder and select **Add repository**.
3. Check that the current repository is `chen-zhijian.github.io` and the current branch is `main`.
4. Review the changes to `index.html` and `README.md` in the **Changes** tab.
5. Enter a summary such as `Add research preprints to personal website`, then click **Commit to main**.
6. Click **Push origin**. If GitHub Desktop first asks you to fetch or pull newer changes, do that before pushing; review any resulting conflicts instead of discarding either version.
7. Open the repository’s **Actions** tab and wait for the GitHub Pages deployment to finish. Then open the website and refresh it.

These local edits have not been pushed automatically. If the Pages deployment is not configured, go to **Settings → Pages** and choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then click **Save**. No custom workflow is required for this HTML page. See [GitHub’s Pages publishing instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

If you use the ZIP backup instead of the prepared Git folder, first clone the existing website repository with GitHub Desktop (**File → Clone repository → URL**), then copy the ZIP’s `index.html` and `README.md` into that clone, replacing those two files. The ZIP contains the website files only, not the Git history.

## Research descriptions

The project titles, scope, and PSH coauthor credit were checked against the public manuscript sources on 23 October 2026. Both projects are presented as research drafts. The Kobayashi double-logarithmic estimate is specific to the obstruction family; the draft leaves its optimal rate open. The PSH draft does not resolve the surface regularization problem in general. The public Kobayashi source currently leaves author metadata unset, so this page does not add a manuscript byline.

- [Kobayashi chains repository](https://github.com/chen-zhijian/kobayashi-chains)
- [Plurisubharmonic exhaustion repository](https://github.com/chen-zhijian/psh-exhaustion)
