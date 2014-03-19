jekyll.workflow
===

A simplified way to deploy a [Jekyll][jekyll-url] site to [Github Pages][gh-pages-url].

### How
* Download the deploy script:

```bash
curl https://raw.github.com/vvgomes/jekyll.workflow/master/deploy > deploy
```

* Exclude the deploy script in your _config.yml:
```yaml
exclude: [deploy]
```

* Run the deploy script:
```bash
./deploy
```

[jekyll-url]: http://jekyllrb.com/
[gh-pages-url]: http://pages.github.com/

