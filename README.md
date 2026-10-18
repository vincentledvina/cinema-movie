# CINEMA-MOVIE

Source for the CINEMA-MOVIE GitHub site: https://vincentledvina.github.io/cinema-movie

MOVIE (Multi-platform Observations from Volunteers: Ionospheric Experiments) is the citizen science component of NASA's CINEMA (Cross-scale INvestigation of Earth's Magnetotail and Aurora) mission. This site carries the material that changes: campaigns, observing and submission instructions, and results. It was built from HamSCI's working group template, https://github.com/hamsci/hamsci-wg.

## Editing

Pages are Markdown files in `docs/`. The order of the header links is set by `header_pages` in `docs/_config.yml`. Every push to `main` rebuilds the site through the GitHub Actions workflow in `.github/workflows/pages.yml`.

To list datasets and publications on the Results page, add BibTeX entries to `docs/_bibliography/datasets.bib` or `docs/_bibliography/publications.bib`, and put `{% bibliography -f datasets.bib %}` (or `publications.bib`) back under the matching heading in `docs/6_results.md`.

## License

Site content is licensed under Creative Commons Attribution 4.0 International (CC BY 4.0). See LICENSE.txt.
