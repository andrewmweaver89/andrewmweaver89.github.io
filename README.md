### Installation
- If this is your first Jekyll blog, follow this <a href="https://jekyllrb.com/docs/installation/">helpful guide</a> to set up Jekyll
- Fork this repository, rename the fork as `your-username.github.io`. Your blog should immediately be live on `https://your-username.github.io`
- Clone your fork
- Delete everything in `_posts` directory. Delete the `tmp` directory
- Open `_config.yml` and set the variables
- Run `jekyll serve` and your blog should be live on `http://localhost:4000`. Make changes, test them locally, commit your changes and push to your fork. Your changes should be live in a couple of seconds


### Customization
- `_config.yml` Config variables
- `_/layouts/default.html` Default page with head and footer section
    - `_/layout/post.html` Page for `layout: post`, inherits `default`
    - `_/layout/page.html` Page for `layout: page`, inherits `default`

### License
GNU GENERAL PUBLIC LICENSE Version 3
