+++
title = "Initial Netlify Experience"
date = "2024-10-14"
description = "My initial experience with Netlify & Hugo."
tags = [
    "Hugo",
    "Netlify",
    "Github",
    "Static Site",
]
+++

# Netlify & Hugo

I liked the look/function of [Bear Blog](https://bearblog.dev/), but wanted to be able to write in markdown and liked the idea of using GitHub to manage/host the files. I had had difficulties with GitHub Pages in the past, so I thought I would try out Netlify after I learned about it.

It took a bit of time to trouble shoot things as I was trying to get [hugo-bearblog](https://github.com/janraasch/hugo-bearblog) to work with the Netlify + Hugo Quickstart template. That was a deadend no matter how many different aveneues I attempted. Eventually I just created an empty GitHub repo via the web interface, cloned it to my local machine, initialized a hugo site in the git directory, added hugo-bearblog as a git submodule, and copied over the contents of the example site.

I pushed that back to the git repo and Netlify quickly built and hosted the website. After confirming it workd, I swapped the example content for a barebones version of my own. I plan to expand on most parts of the website ASAP, but need to take a break as I have spent a decent amount of time getting this to build on Netlify.