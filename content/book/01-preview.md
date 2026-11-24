---
title: Preview the Site
description: Clone the repository and open a local home page in three commands.
book_kind: chapter
book_number: 1
weight: 10
---

OINK Starter is a Hugo Module site. Git downloads the source, Go resolves the pinned theme, and Hugo builds everything.

## Prerequisites {#prerequisites}

Install Git, Go 1.27.4 or newer, and Hugo 0.169.0 or newer (any edition; no Sass compiler is required).

## Three commands {#three-commands}

```bash
git clone https://github.com/pgsty/oink-starter.git
cd oink-starter
hugo server
```

Open <http://localhost:1313/>. Chinese is under `/zh/`; French is under `/fr/`.

## Verify live reload {#first-proof}

Change one sentence in `data/home/en.yaml` and confirm that the browser reloads. You now have a working editing loop.
