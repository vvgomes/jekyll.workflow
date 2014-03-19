# jekyll.workflow
## master ⇝ gh-pages

An simplified way to deploy a jekyll site to gh-pages.

### Getting started
* Download the deploy script.

```bash
curl https://raw.github.com/vvgomes/jekyll.workflow/master/deploy > deploy
```

* Exclude the deploy script from your live site.

```yaml
exclude: [deploy]
```

