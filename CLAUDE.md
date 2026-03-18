# Personal Career Site

GitHub Pages site using Jekyll with the Cayman theme.

## Content Principles

- **This is a public career site, not a dev talk or self-assessment.** State what you do and what you've done. Don't reflect on how you think about yourself.
- **Show, don't claim.** Describe work by its scope and impact, not by labeling yourself ("early adopter", "deep expertise"). Let the reader draw conclusions.
- **No martyrdom framing.** Don't position yourself as someone who "takes on work others avoid" or does "thankless tasks." Frame contributions positively — you drive alignment, you build culture — without the implication that others don't.
- **Lean over thorough.** A few well-chosen details beat a comprehensive list. If it reads like a performance review, cut it.
- **Not a LinkedIn post.** Avoid superlatives, buzzwords, and self-congratulatory adjectives. The tone should be direct and understated — someone describing what they actually do, in their own voice.
- **Vague on unrealized work.** Don't get specific about projects that haven't shipped or delivered proven impact yet. Frame them by the type of problem, not the solution.
- **AI framing:** Position AI work as a capability applied to real engineering problems at platform scale — not as "using AI tools" (table stakes) and not tied to any single project. The signal is: this person understands how AI changes the way platform teams operate.

## LinkedIn Mirror

The bottom of `index.md` contains a LinkedIn-specific version of the profile inside an HTML comment block (`<!-- ... -->`). It won't render on the site but lives in the same file for easy reference.

**When updating the site content, always update the LinkedIn section to match.** The LinkedIn version differs in structure (bullet points for scannability) but the substance and tone should stay consistent.

**LinkedIn section formatting rules:**
- No mid-sentence line breaks. Each paragraph must be a single line so copy-paste works without backspacing.
- No em dashes. Use commas or rewrite.
- No en dashes in date ranges. Use plain hyphens (2018-Present, not 2018–Present).
- No special characters that don't paste cleanly into LinkedIn.

## Writing Style

- No em dashes or en dashes anywhere on the site (not just LinkedIn). Use commas, periods, or rewrite.
- No special unicode characters. Use plain hyphens for date ranges (2018-Present).

## Tech Stack

- Jekyll 4 with `pages-themes/cayman@v0.2.0` remote theme
- Custom CSS in `assets/css/style.scss`
- Content in `index.md` (experience entries use HTML divs with `markdown="1"` for card layout)
- Company/university logos in `assets/img/`
- Deployed via GitHub Pages

## Local Development

Requires Homebrew Ruby (`/opt/homebrew/opt/ruby/bin/`):

```
/opt/homebrew/opt/ruby/bin/bundle exec jekyll serve
```

Site available at http://localhost:4000. Auto-regenerates on file changes.

## Repo Note

This is under `~/Development/personal/` — do NOT add `Co-Authored-By` trailers to commits.
