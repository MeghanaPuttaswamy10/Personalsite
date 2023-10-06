---
title: "Building My Own Website: A Simple Guide with Netlify + Hugo!"
date: 2023-01-03T23:29:21+05:30
draft: false
#github_link: "https://github.com/gurusabarish/hugo-profile"
author: "Meghana Puttaswamy"
tags:
  - Netlify
  - Hugo
  - blogging
  - Hugo-profile
image: /images/myblog.PNG
description: ""
toc:
---

Hey there! So, you want to build your own website? Awesome! I was once in your shoes, feeling a bit overwhelmed by all the techy stuff. But hey, I've got good news – it's not that hard, especially with the help of two buddies: Netlify and Hugo. Let's dive into this adventure together!

---

**Step 1: Get Hugo Installed – The Foundation:**

First things first, let's get Hugo installed on your computer. It's like the engine that powers your website. Follow these simple steps:

- Go to the [Hugo releases page](https://github.com/gohugoio/hugo/releases).
- Download the version that matches your computer (Windows, Mac, or Linux).
- Install it by following the instructions – pretty much like installing any other software.

---

**Step 2: Create Your Website – Your Digital Canvas:**

Now that Hugo is ready, let's create your website:

- Open your computer's command prompt or terminal.
- Type `hugo new site your-website-name`. This creates a new folder with your website's basic structure.
- Choose a theme – it's like picking the look and feel of your site. You can find themes on the [Hugo Themes website](https://themes.gohugo.io/).
- Add your chosen theme to your site with a command like `git submodule add https://github.com/theme-author/theme-name.git themes/theme-name`.
- Customize your site by tweaking the `config.toml` file in your website's folder. Just change the site title and description to start with.

---

**Step 3: Set Up Git – Guarding Your Progress:**

Git is like a superhero for your code, saving your progress and helping you collaborate. Here's what you need to do:

- In your terminal, navigate to your website's folder.
- Type `git init` to start tracking changes.
- Add all your files with `git add .`.
- Commit your changes with `git commit -m "Initial commit"`.

---

**Step 4: Netlify – The Magic Deploy Button:**

Time to make your website live with Netlify:

- Go to [Netlify](https://www.netlify.com/) and sign up if you haven't.
- Click on "New site from Git."
- Connect your Git repository by following the instructions.
- Set the build command as `hugo` and the publish directory as `public`.
- Click on "Deploy site" – that's the magic button!

---

**Step 5: Custom Domain (Optional) – Your Website's Personal Touch:**

Want your own fancy domain? Here's how:

- In Netlify, go to "Site settings" > "Domain settings."
- Add your custom domain and follow the instructions to configure DNS settings. Sounds complicated, but it's just copy-pasting a couple of things.

---

**Step 6: Continuous Deployment – Always Up to Date:**

Make sure your site is always fresh with the latest changes:

- In Netlify, go to "Settings" > "Build & deploy."
- Enable continuous deployment. Now, every time you push changes to your Git repository, Netlify will automatically update your website.

---

**Step 7: The Big Reveal – Your Website is Live:**

Visit the URL provided by Netlify, and there it is – your website, live and kicking! No need to be nervous; you've just become a web developer.

---

So, there you have it – a simple guide to building and deploying your own website using Netlify and Hugo. It's like putting together a digital puzzle, and you've just created a masterpiece! Cheers to your new website and all the adventures it will bring. Happy coding!