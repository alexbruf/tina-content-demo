---
title: Getting Started with TinaCMS on Cloudflare
date: '2026-03-26T00:00:00.000Z'
---

## What is this?

This demo shows TinaCMS self-hosted on Cloudflare Workers, using:

- **D1** for the content index
- **GitHub** as the content source
- **Clerk** for authentication

## How it works

Content lives in this GitHub repo. The TinaCMS worker indexes it into D1, and serves it via GraphQL.
