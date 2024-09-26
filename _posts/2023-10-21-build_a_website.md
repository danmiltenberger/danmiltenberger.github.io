---
layout: post
title: "Build a personal website for free"
date: 2023-10-21
---

## Fast Read:
1. Github is like google docs for programmers, it makes it easy to track changes and collaborate on projects
2. Github will host a website with their program called Github pages. For a public project, this is free
3. Using a program called Jekyll and a theme called Chirpy, I built this website.
4. Test Jekyll by running it from the terminal, then push the changes to github

## Goal
For me, my goal was to have a static site as quickly and conveniently as possible. I wanted to have a home page, a contact page, and a blog. To cut to the chase - if you want a website quickly and conveniently, pay for it. If you want a simple website for free, check out github pages. 

## Method
Start by creating a "repository" on github. A repository is like a folder on your computer, but it can do a couple extra cool things. Create a repository with the format username.github.io, where username is, ya know, your username. Github recommends using a website formatter called Jekyll and I'm inclined to agree! 
Set up jekyll using their guide here: https://jekyllrb.com/docs/
You can run the website from your computer (and not github servers) by using the command `jekyll serve` in your terminal. Open up a browser and go to your local host, the web address is http://localhost:4000/

## Themes
I used a custom theme called chirpy. It adds a search bar, tags, categories, and a cool home page. I use absolutely zero of those features at time of writing. If those features sound cool, you can check out the repository here: https://github.com/cotes2020/jekyll-theme-chirpy or more directly clone a starter repository from here: https://github.com/cotes2020/chirpy-starter 

## Review
Your website is a repository (github folder) hosted by github servers. Make changes on your computer and then "push" these changes to github. If you want to see the changes without waiting for github to refresh, run the website from your computer using jekyll and view it in your browser. I had bad luck with files loading properly in the local browser but not on Github. Check your case sensitivity (I lost at least two hours because of Avatar.PNG not avatar.png) and where your images are being saved. 

