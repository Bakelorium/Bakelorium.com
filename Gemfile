source "https://rubygems.org"

# Pinned to whatever Jekyll + plugin versions GitHub Pages actually runs,
# so a local `bundle exec jekyll build` matches what Pages builds. See
# .claude/rules/infra.md for the temp-GitHub-Pages / eventual S3+CloudFront
# hosting decision.
gem "github-pages", group: :jekyll_plugins

# Not a Pages dependency -- Ruby >= 3 dropped webrick from the standard
# library, and `jekyll serve` needs it for local dev.
gem "webrick", "~> 1.8"
