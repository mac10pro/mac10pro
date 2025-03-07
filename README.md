## Hi there 👋
If you're looking to collaborate and add images to mac10.pro's image blog, related to gaming, development, software, programming, or other related concepts -- it's very simple.

1. First, fork this repo, and add a new `.md` file in `/_posts`. The naming convention needs to be `year-dd-mm-posttitle.md`. E.g. `2025-01-02-cool-react-project.md`
2. Second, upload an image in the `/images` directory.
3. Third, use this template in your `.md` file.
```
---
layout: post
title: "page title"
excerpt: "page excerpt"
date: 2025-01-01
image: "/images/EDIT-IMG-NAME.png"  # optional image
---

<img src="/images/EDIT-IMG-NAME.png">
```
4. Submit pull request.

---

Using Github Pages has its benefits. 
- For one, I can use Github actions to help me deploy based on if any changes were made. So updates are hands off, besides throwing an image, and post file up.
- Image size is important to me, but I feel if I want to make X posts a day for content, I'm going to be unable to optimize everything.
- ImgBot allows me to optimize as I go. Each day it will seek images, and optimize them automatically, and create a pull request for me to merge. It's very convenient for an image blog like this.
