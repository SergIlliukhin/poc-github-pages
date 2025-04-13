# Jekyll GitHub Pages Site

A simple static website built with Jekyll and deployed with GitHub Pages.

## Structure

- `_pages/`: Contains static pages like About and Contact
- `_posts/`: Contains blog posts
- `_config.yml`: Jekyll configuration file
- `Gemfile`: Ruby dependencies

## Local Development

### Prerequisites
- Ruby
- Bundler

### Setup
1. Clone this repository
2. Install dependencies:
```
bundle install
```
3. Run the local server:
```
bundle exec jekyll serve
```
4. Visit `http://localhost:4000` in your browser

## Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the main branch. GitHub Pages will automatically build and deploy your site when you push changes to your repository.

## Adding Content

### Adding a new page
1. Create a new markdown file in the `_pages` directory
2. Add front matter with title and layout:
```
---
title: Your Page Title
layout: page
---
```
3. Add your content

### Adding a new post
1. Create a new markdown file in the `_posts` directory with the naming convention `YYYY-MM-DD-title.md`
2. Add front matter with title, date, and layout:
```
---
title: Your Post Title
date: YYYY-MM-DD
layout: post
---
```
3. Add your content 