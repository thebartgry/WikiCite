# WikiCite_nl

lightweight, browser-based tool that converts a DOI into citations for nl_WP.

Live version:  
👉 https://thebartgry.github.io/WikiCite/

---

## What it does

- accepts a DOI
- fetches metadata from **Crossref**
- Outputs reference template, Dutch parameter names (`auteur`, `jaar`, `titel`, etc.)

Example output:

```wiki
<ref name="leebe">{{Citeer journal | auteur = Leebens-Mack M, Barker M, Carpenter E | jaar = 2019 | titel = … | journal = Nature | volume = 574 | issue = 7780 | pages = 679–685 | doi = 10.1038/… | pmid = 31645766 | taal = en }}</ref>
