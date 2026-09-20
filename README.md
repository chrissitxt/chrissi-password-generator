# chrissi's password generator

a lightweight, client-side password generator with adjustable length and character options.

## what it does

generates random passwords entirely in the browser using `crypto.getRandomValues()`.

## features

- adjustable length, 8 to 24 characters
- toggle uppercase, lowercase, numbers, and symbols independently
- exclude visually similar characters (l, 1, o, 0)
- strength indicator based on the actual character pool and length

## how it works

everything runs in the browser. nothing is sent anywhere, nothing is logged, nothing is stored.
