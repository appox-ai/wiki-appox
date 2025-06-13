# AppOX's Wiki

## Description

This repository contains the source code for the AppOX's Wiki built with Jekyll.

## How to run

1. Clone the repository
```bash
git clone https://github.com/appox-ai/wiki-appox.git
```

2. ⚠️ Install Jekyll on your local machine if it is not already installed. You can find the installation instructions here: https://jekyllrb.com/docs/installation/

3. Run Jekyll
```bash
bundle exec jekyll serve
```

4. Open the wiki in your browser using the url http://localhost:3000

## How to contribute

1. Create a new branch
```bash
git checkout -b my-contribution
```

2. Create a new file in the _posts directory
```bash
touch _posts/2025-06-13-my-contribution.md
```
Bear in mind that the filename should be in the format YYYY-MM-DD-title.md

Add content to the file avoiding include sesitive or private information. The file should be in markdown format. The file should start with the following front matter:

```markdown
---
layout: post
title: My contribution
author: Your name
---

*Write your content here*

```

3. Commit your changes
```bash
git add .
git commit -m "Add my contribution"
```

4. Push your changes
```bash
git push origin my-contribution
```

5. Open a pull request

6. Wait for the AppOX's team to accept your contribution

7. When the AppOX's team accept your contribution, it will be published on the AppOX server and available on the AppOX's wiki website.

## How to update

1. Pull the latest changes
```bash
git pull origin main
```

2. Run Jekyll
```bash
bundle exec jekyll serve
```

3. Open the wiki in your browser using the url http://localhost:3000
