# Jekyll Website – Lab 01

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

This site is meant as a hands-on introduction to deploying personal or academic
websites.

## Running Locally

To launch the website locally, follow these steps:

1. Clone the Repository  

    Choose a local path where you want to clone the project, for example:

    ```bash
    cd ~/projects
    git clone https://github.com/RahulSandhu/jekyll-website.git
    cd jekyll-website
    ```

2. Install Bundler (if not already installed)

    ```bash
    gem install bundler
    ```

3. Install Required Gems  

    Set a local install path for gems inside the project:

    ```bash
    bundle config set --local path 'vendor/bundle'
    bundle install
    ```

4. Run the Website Locally

    Launch the Jekyll:

    ```bash
    bundle exec jekyll serve -H 0.0.0.0
    ```

5. Access the Site

    Open a browser and go to:

    ```bash
    firefox http://localhost:4000
    ```
