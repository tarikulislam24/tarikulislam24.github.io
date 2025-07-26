# Personal Academic and Professional Portfolio

This is a personal portfolio website built with Jekyll and hosted on GitHub Pages. It is designed to showcase academic achievements, research projects, and professional skills.

## About the Project

This portfolio is based on the popular [AcademicPages template](https://github.com/academicpages/academic-pages.github.io) and is customized to meet the needs of a student in the field of computer science. It includes the following sections:

*   **Home:** A brief introduction and news section.
*   **Research:** A summary of research interests and projects.
*   **Publications:** A list of publications and technical reports.
*   **Projects:** A showcase of academic and personal projects.
*   **Courses:** A list of relevant coursework and skills.
*   **CV:** A downloadable version of your resume/CV.

## Getting Started

To get started with this portfolio, you will need to have the following software installed on your machine:

*   [Ruby](https://www.ruby-lang.org/en/)
*   [Jekyll](https://jekyllrb.com/)
*   [Bundler](https://bundler.io/)

### Prerequisites

Before you begin, make sure you have a GitHub account and have created a new repository for your portfolio. The repository should be named `yourusername.github.io`, where `yourusername` is your GitHub username.

### Installation

1.  Clone this repository to your local machine:

    ```
    git clone https://github.com/yourusername/yourusername.github.io.git
    ```

2.  Navigate to the project directory:

    ```
    cd yourusername.github.io
    ```

3.  Install the required gems:

    ```
    bundle install
    ```

## Usage

To run the website locally, use the following command:

```
bundle exec jekyll serve
```

This will start a local server at `http://localhost:4000`. You can now view your portfolio in your web browser.

### Customization

To customize your portfolio, you will need to edit the following files:

*   `_config.yml`: This file contains the main configuration for your website, including your name, email, and social media links.
*   `_pages/`: This directory contains the individual pages of your website. You can edit the content of these pages to reflect your own experience and interests.
*   `assets/pdf/CV.pdf`: This is a placeholder for your CV. You should replace this file with your own CV in PDF format.

## Deployment

To deploy your portfolio to GitHub Pages, simply push your changes to the `main` branch of your repository:

```
git add .
git commit -m "Update portfolio"
git push origin main
```

Your website will be live at `https://yourusername.github.io` within a few minutes.
