# Eric de Morgoli — Strategic Advisory

Professional website built with Jekyll and deployed to GitHub Pages.

## Local Development

```bash
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000`.

## Deployment

Push to `main` branch. GitHub Pages builds and deploys automatically.

## Custom Domain

To switch from `edemorgoli.github.io` to `blog.demorgoli.com`:

1. Add a `CNAME` file containing `blog.demorgoli.com`
2. Configure DNS: CNAME record pointing to `edemorgoli.github.io`
3. Enable HTTPS in GitHub Pages settings
