# sequeless.github.io

Source for [sequeless.org](https://sequeless.org), built with Jekyll and served by GitHub Pages
from the `main` branch.

## Local preview

```sh
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Custom domain

The `CNAME` file sets the custom domain to `sequeless.org`. DNS uses root (`@`) records only:

| Host | Type | Value |
|------|------|-------|
| `@` | A | 185.199.108.153 |
| `@` | A | 185.199.109.153 |
| `@` | A | 185.199.110.153 |
| `@` | A | 185.199.111.153 |
| `@` | AAAA | 2606:50c0:8000::153 |
| `@` | AAAA | 2606:50c0:8001::153 |
| `@` | AAAA | 2606:50c0:8002::153 |
| `@` | AAAA | 2606:50c0:8003::153 |
