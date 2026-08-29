---
layout: default
title: Binsparse — Sparse data, clearly specified
body_class: home
---

# Sparse data, clearly specified

Binsparse is an open, portable binary storage format for sparse matrices and
tensors. It lets tools exchange structured sparse data without inventing another
file format.

{% if site.data.versions.latest_stable %}
[Read version {{ site.data.versions.latest_stable }}]({{ '/versions/' | append: site.data.versions.latest_stable | append: '/' | relative_url }})
{% else %}
[Read the current draft]({{ '/versions/draft/' | relative_url }})
{% endif %}

[View the specification on GitHub](https://github.com/Binsparse/binsparse-specification)

## Portable

Binsparse provides a shared on-disk representation designed for interchange
across languages and tools.

## Versioned

Immutable specification releases are available alongside the latest working
draft.

## Open

The specification and its development process are public and community-driven.

## Specification

- [Current draft]({{ '/versions/draft/' | relative_url }})
- [All versions]({{ '/versions/' | relative_url }})
