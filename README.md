# chrissi's Password Generator

A lightweight, client-side password generator with adjustable length and character options.

## What it does

Generates random passwords entirely in the browser using `crypto.getRandomValues()`.

## Features

- Adjustable length, 8 to 24 characters
- Toggle uppercase, lowercase, numbers, and symbols independently
- Exclude visually similar characters (l, 1, o, 0)
- Strength indicator based on the actual character pool and length

## How it works

Everything runs in the browser. Nothing is sent anywhere, nothing is logged, nothing is stored.

## Design

Font: Crimson Pro (SIL Open Font License), weight 500, 18px text and 1.25em heading.

Design tokens, mint theme. Light and dark follow the system.

| Token | Light | Dark |
| --- | --- | --- |
| background | `#f5fbf7` | `#0f1512` |
| accent | `#12241b` | `#e6f6ee` |
| body | `#40594a` | `#9db8aa` |
| sub | `#587265` | `#728a7d` |
| highlight | `#ddf1e6` | `#1f2f27` |
