---
layout: default
title: PokeAPI User Guide
permalink: /writing-samples/pokeapi/
---

# PokeAPI User Guide

This guide introduces PokeAPI using a simple, interactive example. No coding experience is required.

## Try It Yourself

{% include pokeapi-widget.html %}

---

## What This Demonstrates

The widget above is making a live request to a public API every time you search. Here's what's happening behind the scenes:

- **A GET request** is sent to PokeAPI's server, asking for data about the Pokémon you typed in.
- The API responds with **JSON** — a structured data format that's easy for both computers and humans to read.
- The widget reads that JSON and **displays the relevant details** — name, type, abilities, and an image — right on the page.

No database, no backend, no login required. That's the power of a well-designed public API.
