---
layout: default
title: Upstreaming Dashboard
---

<header class="page-header">
  <h1>{{ site.title }}</h1>
</header>

This project will typically want to contribute some files into `Mathlib` itself. These files, which we can call 'upstreaming candidates', exist in this repository while they are being developed. This dashboard shows upstreaming candidates that look ready to ingest into `Mathlib`, and also files in the project that look "easy to unlock" for upstreaming.

For the dashboard to be correct, the repository must follow the same directory and filename structure as Mathlib for their upstreaming candidates. Namely, the upstream candidate `A/B/C.lean`, should exist in `Mathlib/A/B/C.lean`.

The dashboard highlights any open PRs to the Mathlib repository containing the corresponding files.

{% include _upstreaming_dashboard/dashboard.md %}
