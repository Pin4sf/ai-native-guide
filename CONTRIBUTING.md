# Contributing to AI Native Guide

We welcome contributions from everyone! Here are three ways to contribute.

## Quick Fix (30 seconds)

Every guide has a **"Suggest Edit"** link at the bottom. Click it to open GitHub's web editor. Fix a typo, add a tip, update outdated info — submit a PR right from your browser.

## Write a Guide

1. Fork this repository
2. Create a new `.mdx` file in `src/content/guides/`
3. Use the template below for your frontmatter
4. Write your guide using standard markdown
5. Submit a pull request — Vercel will generate a preview URL automatically

### Guide Template

```mdx
---
title: "Your Guide Title"
description: "1-2 sentence description of what the reader will learn."
author: "Your Name"
tags: ["tag1", "tag2", "tag3"]
difficulty: "beginner"  # beginner | intermediate | advanced
publishedDate: 2026-03-25
---

## Overview

What does this guide cover? 1-2 sentences.

## Prerequisites

What should the reader know or have installed?

## The Guide

Main content goes here. Use:
- Code blocks with language tags (```bash, ```json, etc.)
- Tables for comparisons
- Short paragraphs (2-3 sentences max)
- Practical, actionable advice

## Key Takeaways

- Bullet point 1
- Bullet point 2
- Bullet point 3
```

### Existing Tags

Use existing tags when possible: `rtk`, `token-optimization`, `context-management`, `claude-code`, `optimization`, `configuration`, `getting-started`, `productivity`

## Request a Topic

Open a [GitHub Issue](https://github.com/Pin4sf/ai-native-guide/issues/new) describing what you'd like covered. The community can pick it up.

## Development

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Style Guide

- **Be practical** — every section should have actionable takeaways
- **Use tables** for comparisons and reference data
- **Keep paragraphs short** — 2-3 sentences max
- **Include code examples** with proper language tags
- **Use imperative tone** — "Install RTK" not "You should install RTK"
