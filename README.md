# FallingParkour Development Log
FallingParkour development log. Project found here [https://github.com/nicholas-maltbie/FallingParkour](https://github.com/nicholas-maltbie/FallingParkour)

# Viewing the Website

This is a blog website and can be viewed at [https://nicholas-maltbie.github.io/FallingParkourDevLog](https://nicholas-maltbie.github.io/FallingParkourDevLog)

# Setup Website

In order to develop and work on repository, install Jekyll
using Ruby following [these instructions](https://jekyllrb.com/docs/installation/)

## Requirements
* [Ruby](https://www.ruby-lang.org/en/downloads/) version 2.5.0 or above
* [Ruby Gems](https://rubygems.org/pages/download)

## Installation
Ensure jekyll is installed
```bash
gem install jekyll bundler
```

Download and view the website
```bash
# Clone the repository
cd ~/projects
git clone git@github.com:nicholas-maltbie/FallingParkourDevLog.git

# See current website with command
cd ~/projects/FallingParkourDevLog
bundle install
bundler exec jekyll serve

# View website at localhost:4000/FallingParkourDevLog

```

## Build

To build the website as a static website use the command
```bash
bundler exec jekyll build
# Will output website to ./_build
```
