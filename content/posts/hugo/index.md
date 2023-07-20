---
title: "How to create a Hugo Website"
date: 2023-07-08T08:06:25+06:00
description: How to create a Hugo Website
menu:
  sidebar:
    name: How to create a Hugo Website
    identifier: hugo
    weight: 50
hero: boat.jpg
---

## How to create a Hugo Website

Hugo is a fast, open-source static website generator with many contributors and themes available to suit various needs. Hugo is a fantastic resource for blogs, portfolios and documentation sites. Hugo is a great tool to keep web hosting costs low as Hugo sites may be hosted on github pages, netlifier and others. As there are various themes available it is also relatively simple to configure a website with minimal coding and command line experience.

Markdown is can be used to add content to pages in Hugo. 


## Getting Started 

There are two Hugo editions to choose from, standard and extended. Hugo recommends to install the extended edition to avail of the following features: 

- Encode to the WebP format when processing images. You can decode WebP images with either edition.
- Transpile Sass to CSS using the embedded LibSass transpiler. The extended edition is not required to use the Dart Sass transpiler.

Hugo also recommends to install Git for the following features: 

- Build Hugo from source
- Use the Hugo Modules feature
- Install a theme as a Git submodule
- Access commit information from a local Git repository
- Host your site with services such as CloudCannon, Cloudflare Pages, GitHub Pages, GitLab Pages, and Netlify

## Install Hugo on Windows 

To install Hugo on Windows a package manager is recommended. Chocolatey is a free and open source package manager for Windows which will install the extended edition of Hugo:
```
choco install hugo-extended
```

## Choose a Hugo Theme 

View a full list of available Hugo themes here https://themes.gohugo.io/ .


## Create a New Hugo Site

Open your command prompt, on Windows Hugo recommends to install Git Bash. 

Navigate to the folder in which to create the new project. 

```
cd Desktop 
```

Execute the Hugo new site command: 

```
hugo new site new-hugo-website
```