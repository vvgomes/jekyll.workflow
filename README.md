jekyll.workflow
===

A simplified way to deploy a [Jekyll][jekyll-url] site to [Github Pages][gh-pages-url].

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

[jekyll-url]: http://jekyllrb.com/
[gh-pages-url]: http://pages.github.com/

