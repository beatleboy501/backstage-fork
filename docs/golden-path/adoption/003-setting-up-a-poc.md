---
id: setting-up-a-poc
sidebar_label: 003 - Setting up a PoC
title: Setting up a PoC
description: How to set up a proof of concept Backstage instance for your organization
---

If you're non-technical, this section should be completed by your technical partner.

Follow [our golden path for creating an app](../create-app/index.md). Once you have that set up, we recommend adding a few `catalog-info.yaml` files to a few repos/projects you own and setting up [the GitHub catalog provider](../../integrations/github/discovery.md).

At this stage, you likely want to just get the instance running on your local machine. We'll go over preparing your instance for production at the end of chapter 2.

You may be tempted to update the theme or add that one plugin your organization _needs_, but hold strong. We'll get there in chapter 3.

## How big should a PoC be?

A PoC is meant to answer one question: does Backstage help with the problem you described to leadership? It should be big enough to answer that question with real usage, and small enough that you can build it in a few weeks.

As a rule of thumb:

- **Teams:** Include 2-3 friendly teams that feel the problem you're trying to solve. One team can feel like a special case, while more than a handful makes it hard to get feedback.
- **Components:** Catalog the 10-30 components those teams own, rather than everything in your organization. Use the catalog for the things they interact with the most, such as their services and the APIs they depend on.
- **Duration:** Run it for 4-8 weeks. That is long enough for people to return after the initial excitement fades, and short enough to keep momentum.
- **Scope:** Solve one problem end to end, for example creating a new service from a template or finding the owner of a service. Resist adding more until that works well.

When the PoC wraps up, show leadership what you found:

- A short demo of the real instance, using the teams' own components.
- The baseline and current numbers for the [metrics](./002-leadership-buy-in.md#example-metrics) you picked.
- A few quotes from the developers who used it.
- What you would do next, and what it would cost.
