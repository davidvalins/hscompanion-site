# H&S Companion website

Static GitHub Pages website for H&S Companion. The site highlights the current
iPad experience, including responsive Stage Manager layouts, safety records,
signatures, reporting and optional Microsoft 365 workflows.

## Preview locally

From the app source directory:

```sh
python3 -m http.server 8000 --directory docs
```

Then open `http://localhost:8000`.

## Publish

This directory is its own Git repository and publishes from the `main` branch of
[`davidvalins/hscompanion-site`](https://github.com/davidvalins/hscompanion-site).
After committing changes, push `main` to update the GitHub Pages deployment.

The project URL is:

```text
https://davidvalins.github.io/hscompanion-site/
```
