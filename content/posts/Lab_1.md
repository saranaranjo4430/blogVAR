+++ 
date = 2024-09-17T11:00:55+02:00
title = "Lab 1"
description = "Site web"
authors = ["Sara Naranjo"]
tags = [
    "Cognition",
    "Perception",
    "Affordance",
    "Gestalt Laws",
    "Dark Design Patterns"
    ]
categories = []
externalLink = ""
series = []
+++


## Step 1: Installing the Magic Wand – Homebrew 🧙‍♂️
Alright, first things first, we need Homebrew. Open your terminal and type in this command to get it up and running:
```markdown
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Step 2: Summon Hugo via Homebrew 🛠️
Now let’s install Hugo. Just type:
```markdown
brew install hugo
```
And bam! Hugo’s in.

## Step 3: Start a New Hugo Project 🏗️
This is where things get fun. Let’s create the actual site:
```markdown
hugo new site my-awesome-blog
cd my-awesome-blog
```

## Step 4: Finding Your Theme 🎨
## Step 5: Write a Post! ✍️
## Step 6: Test the Blog Locally 🚀
## Step 7: Deploy to the World 🌐 

kuyylkuygb.khñoi

Absolutely! Let’s dive into how I built my blog with Hugo, starting with the basics but making it as smooth as possible.

---

### Step 1: Installing the Magic Wand – Homebrew 🧙‍♂️
Alright, first things first, we need Homebrew. Open your terminal and type in this command to get it up and running:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Step 2: Summon Hugo via Homebrew 🛠️
Now let’s install Hugo. Just type:

```bash
brew install hugo
```

And bam! Hugo’s in.

### Step 3: Start a New Hugo Project 🏗️
This is where things get fun. Let’s create the actual site:

```bash
hugo new site my-awesome-blog
cd my-awesome-blog
```

### Step 4: Finding Your Theme 🎨
Hugo has a bunch of themes, but I went with `hugo-coder`. To add it, run:

```bash
git init
git submodule add https://github.com/luizdepra/hugo-coder themes/hugo-coder
```

Then, in `config.toml`, set `theme = "hugo-coder"`.

### Step 5: Write a Post! ✍️
Add your first post by running:

```bash
hugo new posts/my-first-post.md
```

Pop over to the `content/posts` folder, open the file, and start writing. (Don’t forget to delete “draft: true” to make it visible!)

### Step 6: Test the Blog Locally 🚀
Ready for the big reveal? Run:

```bash
hugo server
```

Then visit `http://localhost:1313` in your browser to see your blog live!

### Step 7: Deploy to the World 🌐
Finally, push it to GitHub Pages, following the steps [here](https://gohugo.io/hosting-and-deployment/hosting-on-github/).

---

And there you have it! You’re now officially a Hugo blogger.