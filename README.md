# Hunter ACM Website

This an initial draft of the new Hunter ACM website. Hunter.acm.org now redirects here.

**Please update your bios and optionally include a photo of yourself.** Your default bio and image are based on your GitHub bio and avatar. (@f0cus10, your default bio is from your LinkedIn). Your bio can be as long or as short as you want it to be, and can include images, gifs, emojis, etc. Tell us about yourself! (e.g. What are your interests? What is your position on the board? What do you bring to our community? What do you hope members get out of being part of Hunter ACM?) Have fun with it!

**If you prefer not to be featured on the website, feel free to remove your information.**

You're welcome to make your changes directly on the master branch when updating your bios.

Your bio is at `_posts/<date>-<yourname>.md`. Edit the file below the following snippet:
```
---
layout: post
title:  "<Your Name>"
author: board
categories: [ "Meet the Board" ]
image: assets/images/<yourname>.png
memberprofile: true
---
```

If you would like to be listed as an author, add your information to `_config.yml`.
Here is an example:
```
  suzenfylke:
    name: suzenfylke
    display_name: "Suzen Fylke"
    gravatar: 6f00367f46bd1774aa815c648fe089bb
    web: http://www.suzenfylke.com/
    description: "Sue is a senior majoring in CS. She makes language learning fun! With computers."
```

If you add yourself as an author in the configuration file, you may list yourself as an author on your bio page. Replace `board` with your author key, as in the following example:
```
---
layout: post
title:  "Suzen Fylke"
author: suzenfylke
categories: [ "Meet the Board" ]
image: assets/images/suzenfylke.png
memberprofile: true
---
```

## Contributing:

Contributing is currently limited to board members. This will change after the site is launched. If you're updating your bios or fixing typos / grammatical errors, feel free to make your changes and commit directly to master. For anything else, please submit an issue first. The active development branch is [dev](https://github.com/hunteracm/hunteracm.github.io/tree/dev) and all contributions, other than those previously specified, will only be accepted here. Pull requests must be reviewed before merging.

If you don't feel comfortable commiting directly to the master branch or working in the dev branch, you can create a new branch and work from there. Here's how to get started:

1. Clone this repo: `https://github.com/hunteracm/hunteracm.github.io.git`
2. Navigate to the correct directory: `cd hunteracm.github.io`
3. Download dependencies: `bundle`
4. Create a new branch: `git checkout -b <branch-name>` or however you like to create branches
5. Serve the site: `jekyll serve --watch`

This website is adapted from an existing theme. Check out [the original theme's repository](https://github.com/wowthemesnet/affiliates-jekyll-theme) to learn about how to download, edit, and serve the site. 

The jumbotron on the About page of this website features an image from Unsplash by [Stefan Stefancik](https://unsplash.com/@cikstefan).
