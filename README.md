# Kamaji ROI Calculator

Interactive calculator for estimating the cost savings of running Kubernetes
control planes with [Kamaji](https://kamaji.clastix.io).

**Live:** https://clastix.github.io/kamaji-roi-calculator/

## Local preview

`index.html` is fully self-contained — open it directly in a browser, or serve it:

```sh
python3 -m http.server 8000
```

## Deployment

Pushing to `master` publishes the site via GitHub Pages (Deploy from a branch,
`master` / root). No build step.

## License

Apache License 2.0 — see [LICENSE](LICENSE).
