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

### Step 1: Installing Homebrew 🧙‍♀️
First, open a terminal and install Homebrew, a package manager that makes life easier on macOS:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Step 2: Installing Hugo 📦
With Homebrew installed, run this to install Hugo:

```bash
brew install hugo
```

### Step 3: Creating Your Site 🏗️
Let’s start building your site! This command will create a new Hugo project:

```bash
hugo new site my-awesome-blog
cd my-awesome-blog
```

### Step 4: Choosing a Theme 🎨
Hugo has tons of themes! I picked `hugo-coder`, but check out [themes.gohugo.io](https://themes.gohugo.io) to explore others.

To add `hugo-coder`, run:

```bash
git init
git submodule add https://github.com/luizdepra/hugo-coder themes/hugo-coder
```

Set the theme in `config.toml`:

```toml
theme = "hugo-coder"
```

### Step 5: Customize in `config.toml` 🎨
Edit `/blogVAR/config.toml` to personalize things like site title, author, and theme settings. This file is your site’s control center!

### Step 6: Adding Your First Post ✍️
Now let’s create your first blog post. Run this command:

```bash
hugo new posts/my-first-post.md
```

Open the file in `content/posts/` and start writing your post! Remember to delete `"draft: true"` to make the post visible.

### Step 7: Testing Locally 🚀
Run Hugo’s server to preview the blog:

```bash
hugo server
```

Visit `http://localhost:1313` in your browser to check out your blog before going live!

### Step 8: Preparing to Upload to GitHub 🌐
Once your blog looks good, let’s put it online. First, make sure everything’s staged correctly:

```bash
git status       # Check file changes
git add .        # Add all files
git commit -m "Initial commit"  # Commit with a message
```

### Step 9: Uploading to GitHub 🚀
Push your blog to a GitHub repository. If you’re deploying to GitHub Pages, you’ll want to follow [Hugo's GitHub Pages guide](https://gohugo.io/hosting-and-deployment/hosting-on-github/).

```bash
git push origin main
```

### Step 10: View Your Live Blog! 🎉
Set up GitHub Pages in your repo’s settings to go live!