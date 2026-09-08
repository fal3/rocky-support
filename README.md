# Rocky support and landing page

Static HTML and image assets for **Rocky: Falling Sand Puzzle**.

- Public page: https://fal3.github.io/rocky-support/
- Product line: **Drop blocks. Melt sand. Find your flow.**
- Source repository: https://github.com/fal3/rocky-support
- HTML entry points: `index.html` and `privacy.html`

## Existing publication path

Commit the reviewed static files and assets to `main`, then push `main` to `origin`.
GitHub's existing generated **pages build and deployment** workflow publishes the
site. No package installation, custom build system, new hosting service, or new
GitHub Actions workflow is required.

After publication, verify that the Pages workflow completed for the pushed commit
and check the public page, images, and metadata. A clean local checkout or an
`origin/main` tracking reference alone is not proof of a successful deployment.
The repository's Pages workflow was verified read-only on September 8, 2026.

## Updating screenshots and copy

Use captures from actual Rocky gameplay. Update image dimensions and alt text to
match the files; keep key metadata, the main heading, and player-facing copy
consistent. `assets/og-rocky.jpg` supplies the social preview. The September 8, 2026 images
are genuine iPhone gameplay captures; the social preview is a crop of the same
Endless run. Web resizing and JPEG compression do not alter game content.

`privacy.html` describes the shipped app's current practices. Do not describe
inactive analytics as active collection. Update the policy and other disclosures
before a release changes those practices.

For a local preview, run `python3 -m http.server 8765` from this directory and open
`http://localhost:8765/`. This does not publish anything.
