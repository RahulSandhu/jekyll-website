# Lab 01 - Deploying Your Personal Website

This website is part of the laboratory class for the subject **High-Performance
and Distributed Computing**, which is included in the **Health Data Science**
master's program.

## Repository Contents

This repository contains the source code for a static personal website built
using **Jekyll**. It includes:

- Basic page structure with `_posts/`, `pages/`, and layout templates
- Sample blog post entries
- Configuration file: `_config.yml`
- Custom static assets like `favicon.ico` and styles
- Auto-generated site output in the `_site/` folder (excluded via `.gitignore`)
- Gem dependencies defined in `Gemfile`

## Running Locally

To launch the website locally, follow these steps:

1. Clone the Repository  

    ```bash
    git clone https://github.com/RahulSandhu/jekyll-website.git
    cd jekyll-website
    ```

2. Install Bundler (if not already installed)

    ```bash
    gem install bundler
    ```

3. Install Required Gems  

    ```bash
    bundle config set --local path 'vendor/bundle'
    bundle install
    ```

4. Run the Website Locally

    ```bash
    bundle exec jekyll serve -H 0.0.0.0
    ```

5. Access the Site

    ```bash
    firefox http://localhost:4000
    ```
