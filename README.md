# jekyll.workflow
## master ⇝ gh-pages

A simplified way to deploy a jekyll site to gh-pages.

### How
1. Download the deploy script:

```bash
curl https://raw.github.com/vvgomes/jekyll.workflow/master/deploy > deploy
```

2. Exclude the deploy script from your live site.

```yaml
exclude: [deploy]
```

3. Run the deploy script:

```bash
./deploy
```

