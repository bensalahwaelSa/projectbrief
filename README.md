# Marketing Brief Builder

A standalone marketing intake website with editable Samsung PowerPoint export.
Includes project description, agency responsibilities, campaign strategy, KPI
planning, inspiration links and media, and separate internal budget fields.

## Update the existing projectbrief site

Repository: https://github.com/bensalahwaelsa/projectbrief
Website: https://bensalahwaelsa.github.io/projectbrief/

Replace the existing `index.html` with this package's `index.html` and commit
to the branch used by GitHub Pages. The current update adds stronger slide
highlights, Measure of success / KPI objective in the form and deck, excludes
Objective category and proposal/presentation milestones from the PPTX, and
adds an End of Document closing slide. The Samsung corporate layout uses spacious
slides with one strong focal point. Supporting content and long answers can add
detail slides before the final closing slide, preserving the full brief.

## Publish with GitHub Pages

1. Create a GitHub repository, for example `marketing-brief-builder`.
2. Extract the download ZIP on your computer.
3. In the repository, use **Add file > Upload files** and upload `index.html`,
   `README.md` and `.nojekyll` to the repository root. Commit the files to `main`.
   Upload the extracted files, rather than the ZIP itself.
4. Open **Settings > Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the **main** branch and **/(root)** folder, then **Save**.
7. When publishing finishes, use **Visit site** on the Pages settings screen.

The usual project-site address is:
`https://YOUR-USERNAME.github.io/marketing-brief-builder/`

GitHub Free supports Pages from public repositories. Private-repository support
depends on the account plan. The Pages settings screen shows the published URL.

Official GitHub instructions:
- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Files

- `index.html`: the complete application, styles, scripts and Samsung template.
- `.nojekyll`: publishes these files directly without a Jekyll build.
- `README.md`: these instructions.

No installation, build command, API key, database or backend is required.
PowerPoint and ZIP downloads are generated in the visitor's browser.

## Data and visibility

The hosted application includes the Samsung template assets, which are accessible
to site visitors along with the application code. GitHub Pages sites are generally
public, including sites published from private repositories unless access control
is explicitly available and configured for the site.

Brief answers, internal budgets and selected media are processed in the browser.
The app does not send them to GitHub or an application server. Browser draft
storage is local to the site address and browser. A draft from the offline HTML
does not transfer automatically: use Save private draft in the old copy and
Load draft in the hosted site. Reselect media files after loading the draft.

The private JSON draft includes the budget. Keep draft backups and generated
agency files outside the website repository. This package contains application
files only, with no filled campaign brief, private draft or test export.

## Updating the website

Replace `index.html` in the repository with the updated standalone builder,
keeping the name `index.html`, and commit the change. GitHub Pages republishes
from the selected branch. Visitors can refresh to load the latest version.
