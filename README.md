# radsilent.github.io

Personal site for Matthew Collaro, systems engineer. Plain static HTML, no build
step — edit the files and push.

## Live URLs

| Page | URL |
|---|---|
| **Home** | **https://radsilent.github.io/** |
| Sitemap | https://radsilent.github.io/sitemap.xml |
| Robots | https://radsilent.github.io/robots.txt |

### Articles

| Article | URL |
|---|---|
| Continuous verification | https://radsilent.github.io/articles/continuous-verification.html |
| Engineering knowledge graphs | https://radsilent.github.io/articles/engineering-knowledge-graphs.html |
| MBSE adoption | https://radsilent.github.io/articles/mbse-adoption.html |
| MBSE tool integration | https://radsilent.github.io/articles/mbse-tool-integration.html |
| Model-based interface control | https://radsilent.github.io/articles/model-based-interface-control.html |
| Model-based safety analysis | https://radsilent.github.io/articles/model-based-safety-analysis.html |
| Requirements decomposition and allocation | https://radsilent.github.io/articles/requirements-decomposition-and-allocation.html |
| Traceability as a byproduct | https://radsilent.github.io/articles/traceability-as-a-byproduct.html |

Companion site: https://radsilent.github.io/matthew-collaro/ (repo
[matthew-collaro](https://github.com/radsilent/matthew-collaro)).

## Deploy

```bash
git push origin main
```

GitHub Pages serves `main` at the repo root. **The repo must stay public** — on a
free plan Pages is disabled the moment it goes private, and the site 404s.

## Content rule

Two former employers are excluded from anything published here by standing
instruction. Personal phone and personal email are likewise never published —
contact routes through the company site.

The release-gate grep pattern is kept in local notes rather than in this repo,
since spelling the excluded terms here would publish them. Run it against the
working tree before every push; it must return nothing.
