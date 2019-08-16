# Contributing to the Hunter ACM Website

Thanks for helping us improve the Hunter ACM website! 🎉

Be sure to join the [Hunter ACM Slack](https://hunteracm.slack.com/) team. Say hello in `#introductions` and let us know what you'd like to work on in `#fixme`.

## Filing a Bug Report or Suggesting a New Feature
Fill out the provided issue template. The template is adapted from the [First Contributions](https://github.com/firstcontributions/first-contributions) project.

## Contributing Code
If you're a member of the Hunter ACM community, ask to join this organization.

### Installation

(First and foremost, [install Jekyll](https://jekyllrb.com/docs/installation/), if you don't already have it.)

1. Clone this repo: `git clone https://github.com/hunteracm/hunteracm.github.io.git`
2. Navigate to the correct directory: `cd hunteracm.github.io`
3. Download dependencies: `bundle`
4. Serve the site: `jekyll serve --watch`

### Making Changes
Make a comment on an issue, saying you're interested on working on it and briefly describe your solution. Make your changes in a new branch, and give your branch a descriptive name. Submit a pull request when you're satisfied with your changes. Don't merge your own pull request. Pull requests should be reviewed before they're merged.

---

## Updating Board Member Bios

This section only applies to current Hunter ACM board members. 

Please update your bios and optionally include a photo of yourself. Your bio can be as long or as short as you want it to be, and can include images, gifs, emojis, etc. Tell us about yourself! (e.g. What are your interests? What is your position on the board? What do you bring to our community? What do you hope members get out of being part of Hunter ACM?) Have fun with it!

You're welcome to make your changes directly on the master branch when updating your bios. Please make contributions using your own GitHub accounts and not the Hunter ACM Board account. 

Save your bio in the  `_posts` directory as `<date>-<yourname>.md`. Copy the following snippet into that file and edit it to include your name, a link to your photo, and an introduction.
```
---
layout: post
title:  "<Your Name>"
author: board
categories: [ "Meet the Board" ]
image: assets/images/<yourname>.png
memberprofile: true
---

Hello, world! My name is ...
```

If you would like to be listed as an author, add your information to `_config.yml`. Here is an example:
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
