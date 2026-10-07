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
