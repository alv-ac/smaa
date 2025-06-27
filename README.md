# README SMAA Test Site

This page contains instructions for maintaining the SMAA site.

## Installation history

To install this site, I followed these steps:

- Created a repository on GitHub
- Cloned it to my computer
- Installed Jekyll on my computer (I used macOS Sequoia & Homebrew)
- Followed the instructions on this page: https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll
    - In particular: https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll
    - I chose to put all files in the root folder / and the main branch for simplicity
- Made edits to '_config.yml'
- Made edits to about.markdown
    - I noticed that changes appeared immediately when viewing the page locally (by running ``bundle exec jekyll serve`` on the terminal. When pushing onto GitHub, it took about a minute for the change to be reflected on remote.
- Removed blog functionality
- Added more pages
    - The nice thing about Jekyll is that it notices new pages (files ending in .markdown) and turns them into HTML pages and adds them to the navbar.
- 
