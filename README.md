# ravenhelm-ai-published (GitHub, public)

Canonical published markdown corpus for ravenhelm.ai. Written only by Bragi promotion PRs from the private drafts repository (`nate/web-estate-drafts`, folder `ravenhelm-ai/`).

## Layout

```text
ravenhelm-ai/
  signals/
    <slug>.md
  media/
```

## Contract

Every entry carries frontmatter: `title`, `date`, `kind`, `description`, `publish_eligible: true`, and optionally `slug`, `substack_url`, `canonical_url`, `og_image`, `links`, `distribution`. Promotion is a pull request opened by Bifröst; merging to `main` is the ratification act. Production for the property is a `content-v*` tag on this repository.

## Editorial CI

See `.github/workflows/editorial-gates.yml`, which runs on pull requests to `main`.
