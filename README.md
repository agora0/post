---
layout: page
title:  BLOG⓪
permalink: /readme/
comments_repo: agorahub/blog0
comments_id: 1
---

{% include comments.html %}

{% include archives.html %}

Read blog on demand.

| Source  | Importer   | Update |
| :-----  | :-------   | :----- |
| INITIUM | RSSINITIUM | Daily  |
| MATTERS | RSSMATTERS | Daily  |
| STAND   | RSSSTAND   | Daily  |
| VOCUS   | RSSVOCUS   | Daily  |

## Test and Deploy

```
$ gem install bundler jekyll
$ vim _config.yml # Configure to test or deploy.

$ bundle exec jekyll serve
# => Now browse to http://localhost:4000

$ JEKYLL_ENV=production bundle exec jekyll build
# Copy the compiled codes from _site/ to html server.
```

## List of Features

- [x] Batch and Automate - Check out the [issue comment](https://github.com/agorahub/news0/issues/1#issuecomment-597540617)
- [x] Comment and Review - Check out the [issue comment](https://github.com/agorahub/blog0/issues/3#issuecomment-726799802)

## Disclaimer

The information and opinions within this website are for information purposes only. They are not intended to constitute legal or other professional advice, and should not be relied on or treated as a substitute for specific advice relevant to particular circumstances. We accept no responsibility for any errors, omissions or misleading statements on this website, or for any loss which may arise from reliance on materials contained on this website. Certain parts of this site may link to external Internet sites, and other external Internet sites may link to this website. We are not responsible for the content of any external Internet sites.

