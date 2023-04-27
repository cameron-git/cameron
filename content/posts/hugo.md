---
title: "Static Websites with Hugo"
date: 2023-04-27T22:32:31+01:00
weight: 10
---

A brief tutorial on how to make a static site with Hugo (Just like this one)

## Instructions

1. Install [Hugo](https://gohugo.io/installation/)  
Windows:  
```sh
winget install Hugo.Hugo.Extended
```
2. Create a new site  
```sh
hugo new site my-site-name
cd my-site-name
git init
```

3. Add a [theme](https://themes.gohugo.io/)
```sh
git clone https://github.com/hugo-sid/hugo-blog-awesome.git themes/hugo-blog-awesome
echo "theme = 'hugo-blog-awesome'" >> config.toml
```

4. Add [content](https://gohugo.io/getting-started/quick-start/#add-content) and [configure](https://gohugo.io/getting-started/configuration/) the site

5. Host with github pages
   1. Publish local repo on GitHub
   2. https://github.com/{username}/{repo-name}/settings/pages  
Change source to "GitHub Actions" and select Hugo


