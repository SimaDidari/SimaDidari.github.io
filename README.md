# SimaDidari.github.io

Personal research portfolio for Sima Didari, built with Jekyll and hosted on GitHub Pages.

## Structure

| File | Purpose |
| --- | --- |
| `index.md` | Front page: bio, News (current-year publications), research tabs, experience, education, patents, awards |
| `robotics.html` | Robotics and Physical AI research area + related publications |
| `genai.html` | Generative AI & LLMs research area + related publications |
| `computer-vision.html` | Computer Vision research area + related publications |
| `optimization.html` | Redirect to `robotics.html` (old URL kept alive) |
| `_layouts/default.html` | Site shell: styles, nav, theme toggle, tab behavior |

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

## Publish

Push to `main`; GitHub Pages builds and deploys automatically.
