# How to host Swagger API documentation with GitHub Pages

This repository is a template for using the [Swagger UI](https://github.com/swagger-api/swagger-ui) to dynamically generate beautiful documentation for your API and host it for free with GitHub Pages.

The template will periodically auto-update the Swagger UI dependency and create a pull request. See the [GitHub Actions workflow here](.github/workflows/update-swagger.yml).

The example API specification used by this repository can be seen hosted at [https://asksmruti.github.io/survey-api/](https://asksmruti.github.io/survey-api/).

## Steps to use this template

1. Click the `Use this template` button above to create a new repository from this template.

2. Go to the settings for your repository at `https://github.com/{github-username}/{repository-name}/settings` and enable GitHub Pages.

    ![Headers](/screenshots/swagger-github-pages.png?raw=true)
    
3. Browse to the Swagger documentation at `https://{github-username}.github.io/{repository-name}/`.
