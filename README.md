# Reach vs Frequency

How many people does your budget actually reach, and how often? Enter the audience size, budget and CPM, and see reach at 1+ and N+ exposures, how much of your spend lands on people already past "enough", and what the same money does on a bigger or smaller audience.

Open `index.html` in any browser. No build step and no dependencies.

- **Inputs:** audience, budget, CPM, your own "enough" exposure count, and how evenly delivery lands (Poisson, or a negative binomial with shape 2 or 0.7).
- **Verdict:** `over-frequency`, `spread thin` or `balanced`. The cut-offs (40% past enough, under 50% reaching enough with under 20% past) are this tool's choice and are listed on the page.
- **Shows:** impressions, average frequency, reach at 1+ and N+, impressions past enough, cost per person reached, and a table at 0.25x to 4x the audience with the money fixed.
- **Share:** a paper-ground PNG card, and the URL hash carries your numbers.

A model, not delivery data. Platform auctions and caps change who sees what, so check the result against the platform's own reach and frequency report.

## License

Code is MIT licensed ([LICENSE](LICENSE)). The bundled fonts (Bricolage Grotesque, Archivo) are SIL OFL 1.1, with licenses in `fonts/`. The ben.j.ads wordmark and footnote mark in `logo/` are Ben Johnston's brand assets and are not covered by the MIT license.
