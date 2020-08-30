# MkDocs Material Template

Documentation project template with MkDocs Material.

## Installation

Use the package manager `pip` with `Python 3` virtual environment to install dependencies.

```shell
pip install -r requirements.txt
```

## Usage

Once the development dependencies are installed, `MkDocs` can be used to generate the website content.

```shell
mkdocs build
```

> INFO - Cleaning site directory\
> INFO - Building documentation to directory\
> INFO - Documentation built in 0.67 seconds

The website can also be served locally for development purposes. Following command will create a static web server on the local machine. And the website changes can be seen in real time.

```shell
mkdocs serve
```

> INFO - Building documentation...\
> INFO - Cleaning site directory\
> INFO - Documentation built in 0.45 seconds\
> INFO - Serving on http://127.0.0.1:8000

In line with Continuous Integration and Continuous Deployment (CI/CD) principles, every commit to `master` branch is automatically build and deployed to GitHub Pages on `gh-pages` branch with the help of [GitHub Actions](https://github.com/features/actions). For this action to work move `deploy.yml` to `.github/workflows` folder. Non-publishing commits can be made by including `[no ci]` in the commit message.

Please visit [gh-pages branch](https://github.com/MX-Layer/MX-Layer.github.io/tree/gh-pages) in order to see the final product.

## Acknowledgment

The documentation website is generated by [MkDocs](https://www.mkdocs.org) and published on [GitHub Pages](https://pages.github.com). As a theme [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) is used with extensions and plugins. UML Diagram support is provided by [PlantUML](https://plantuml.com).

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)

Copyright &copy; 2020 Ihsan TOPALOGLU
