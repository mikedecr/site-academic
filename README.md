# My Hugo/Blogdown Website

<https://mikedecr.netlify.app/>

[![Netlify Status](https://api.netlify.com/api/v1/badges/0a441739-df3f-4ebd-9ff6-b96855a2308d/deploy-status)](https://app.netlify.com/sites/mikedecr/deploys)


## To do:

- Netlify.toml
- delete shitty blog posts
- Color theme
- Site title on home page
    - April Hill's website has a function that detects current page and then throttles title appearance?
- remove contact info
- footer is lame
- paper PDFs on research page (static/papers)
- author blurb at the bottom of a post is weird, contains "role" (remove this) and "bio"

### Resolved:

- fix math
    - we are rendering to markdown (takes more advantage of theme components)
    - "unprotect" the markdown (theme loads mathjax)
    - need to double escape line breaks

