# Contributing to Awesome UI/UX Tools

First off, **thank you** for taking the time to contribute! 🎉

This document outlines the process for contributing to this list. Following these guidelines helps maintainers review and merge your submissions efficiently, and keeps the list consistent for everyone.

---

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [What We're Looking For](#what-were-looking-for)
- [What We're NOT Looking For](#what-were-not-looking-for)
- [Format Guidelines](#format-guidelines)
- [How to Contribute](#how-to-contribute)
- [Pull Request Process](#pull-request-process)
- [Reporting Issues](#reporting-issues)
- [Suggesting New Categories](#suggesting-new-categories)

---

## Code of Conduct

By participating in this project, you agree to maintain a respectful and inclusive environment. Be kind, assume good intent, and help us build something useful for the entire design community.

---

## What We're Looking For

We accept submissions that meet **all** of the following criteria:

- ✅ **Relevant** — The tool is specifically useful for UI/UX design workflows
- ✅ **Active** — The tool is maintained and accessible (updated within the last 12 months)
- ✅ **Established** — The tool has real users and is not a personal side project or early-stage experiment
- ✅ **Accessible** — Available to designers globally (not region-locked without VPN)
- ✅ **Honest pricing** — The pricing column reflects the actual free/paid tier reality
- ✅ **Not a duplicate** — The tool doesn't already exist in the list

---

## What We're NOT Looking For

We'll decline submissions that are:

- ❌ Personal portfolios or very early-stage products with no user base
- ❌ Tools requiring login just to view basic information
- ❌ Outdated tools (no meaningful updates in 12+ months)
- ❌ Overly niche tools that serve a very small audience
- ❌ Duplicate entries already covered by an existing tool in the list
- ❌ Affiliate or sponsored submissions without disclosure
- ❌ Products that are purely marketing/landing-page-oriented with no real functionality

---

## Format Guidelines

### Table Entry Format

Each tool should follow this Markdown table row format:

```markdown
| [Tool Name](https://tool-url.com) | Clear, factual one-line description | Platform (if applicable) | Free / Paid / Free + Pro |
```

**Rules:**
- **Tool Name**: Use the official product name exactly as branded. Link goes to the tool's homepage, not a deep link.
- **Description**: One sentence, factual, no superlatives ("best", "amazing", "ultimate"). Describe what it *does*, not how great it is.
- **Platform** (where applicable): `Web`, `macOS`, `Windows`, `iOS`, `Android`, `Linux`, or combinations like `Web, Desktop`
- **Pricing**: Use consistent labels:
  - `Free` — completely free with no paid tier
  - `Free / Paid` — free tier exists but paid tier available
  - `Paid` — requires purchase or subscription
  - `One-time` — one-time license fee
  - `Free / Self-hosted` — open source, self-hostable option

### Description Style Guide

| ✅ Do | ❌ Don't |
|-------|---------|
| "Converts Figma designs to React components" | "The best way to turn your designs into code" |
| "Open-source color palette generator" | "Amazing color tool you'll love!" |
| "WCAG contrast checker with real-time feedback" | "Helps you with accessibility" |
| Factual, functional language | Marketing language or superlatives |
| One sentence, under ~100 characters | Multi-sentence descriptions |

### Category Placement

Place the tool in the **most relevant single category**. If a tool fits multiple categories, choose the primary use case. Do not list the same tool in multiple sections.

---

## How to Contribute

### Option 1: Pull Request (Preferred)

1. **Fork** this repository by clicking the Fork button in the top right
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/YOUR-USERNAME/awesome-design-tools.git
   cd awesome-design-tools
   ```
3. **Create a branch** with a descriptive name:
   ```bash
   git checkout -b add-toolname
   ```
4. **Edit** `README.md` and add your tool in the correct category, following the [format guidelines](#format-guidelines)
5. **Commit** your changes:
   ```bash
   git commit -m "Add [Tool Name] to [Category Name]"
   ```
6. **Push** to your fork:
   ```bash
   git push origin add-toolname
   ```
7. **Open a Pull Request** against the `main` branch of this repository

### Option 2: Open an Issue

If you're not comfortable with Pull Requests, open an issue using the **[Tool Request](https://github.com/aasavchauhan/awesome-design-tools/issues/new?template=tool-request.md)** template and fill in all required fields.

---

## Pull Request Process

### PR Title Format

Use this format for your PR title:

```
Add [Tool Name] to [Category]
```

Examples:
- `Add Penpot to Design Tools`
- `Add Phosphor Icons to Illustrations & Icons`
- `Fix broken link for Zeplin`

### PR Checklist

Before submitting, confirm:

- [ ] I've read the [format guidelines](#format-guidelines)
- [ ] The tool is not already in the list
- [ ] The tool URL is working and links to the official homepage
- [ ] The description is factual and follows the style guide
- [ ] Pricing is accurate and up-to-date
- [ ] The tool is placed in the correct category
- [ ] My addition maintains the alphabetical or logical order within the section

### Review Process

- Maintainers will review PRs within **7 days**
- We may ask for edits to the description, pricing, or placement
- Once approved, your PR will be merged and you'll be credited via GitHub's contributor graph

---

## Reporting Issues

Use the **[Bug Report](https://github.com/aasavchauhan/awesome-design-tools/issues/new?template=bug-report.md)** issue template to report:

- Broken or dead links
- Incorrect pricing information
- Tools that have shut down or become abandoned
- Duplicate entries
- Formatting inconsistencies

---

## Suggesting New Categories

If you believe an entirely new category is needed (not just a new tool):

1. Open an issue with the title: `Propose new category: [Category Name]`
2. Describe:
   - What the category would cover
   - At least **5 tools** that would populate it
   - Why no existing category fits these tools
3. Maintainers will discuss and vote before adding

---

## Questions?

Open a [Discussion](https://github.com/aasavchauhan/awesome-design-tools/discussions) — we're happy to help before you put effort into a PR.

---

*Thank you for helping keep this list awesome!* 🙌
