# Ayush Portfolio

A personal website built with Jekyll and hosted on GitHub Pages.

## Table of Contents
- [Overview](#overview)
- [Local Development](#local-development)
- [Customization](#customization)
- [Deployment](#deployment)
- [Directory Structure](#directory-structure)

## Overview

This repository contains the source code for my personal portfolio website, showcasing my resume, publications, and blog posts. The site is built with Jekyll and designed to be hosted on GitHub Pages.

## Local Development

### Prerequisites
- Ruby version 2.5.0 or higher
- RubyGems
- GCC and Make

### Installation

1. Install Jekyll and Bundler:
   ```
   gem install jekyll bundler
   ```

2. Clone this repository:
   ```
   git clone https://github.com/yourusername/ayush-portfolio.git
   cd ayush-portfolio
   ```

3. Install dependencies:
   ```
   bundle install
   ```

4. Run the site locally:
   ```
   bundle exec jekyll serve
   ```

5. Open your browser and navigate to `http://localhost:4000` to see the site.

## Customization

### Site Configuration
Edit the `_config.yml` file to update site settings:
- Change the title, description, and URL
- Update social media links
- Modify navigation settings

### Content
- Update `index.md` with your personal information
- Edit `resume.md` with your education and work experience
- Populate `publications.md` with your research papers and talks
- Add blog posts in the `_posts` directory using the format `YYYY-MM-DD-title.md`

### Assets
- Place images in the `assets/images` directory
- Add your resume PDF in the `assets` directory

## Deployment

### GitHub Pages

1. Push your repository to GitHub:
   ```
   git push origin main
   ```

2. Go to your repository settings on GitHub
3. Navigate to the "Pages" section
4. Set the source branch to "main" (or "master")
5. Your site will be available at `https://yourusername.github.io/ayush-portfolio`

## Directory Structure

```
ayush-portfolio/
├── _config.yml            # Site configuration
├── _posts/                # Blog posts
├── assets/                # Static files
│   └── images/            # Image files
├── index.md               # Home page
├── resume.md              # Resume page
├── publications.md        # Publications page
├── blog.md                # Blog listing page
├── Gemfile                # Ruby dependencies
└── README.md              # Project documentation
``` 