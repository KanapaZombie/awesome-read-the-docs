<!--lint ignore awesome-git-repo-age-->
<!--lint disable double-link-->

<!-- title -->

# Awesome Read the Docs Projects [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![lint](https://github.com/readthedocs-examples/awesome-read-the-docs/actions/workflows/lint.yaml/badge.svg)](https://github.com/readthedocs-examples/awesome-read-the-docs/actions/workflows/lint.yaml)

<!-- subtitle -->

> A curated list of awesome documentation projects, useful to learn from and for bootstrapping new documentation projects.
> Plus cool real-life usages of Read the Docs.

<!-- image -->

<a href="https://docs.readthedocs.io/en/stable/tutorial/index.html" target="_blank" rel="noopener noreferrer">
  <img src="./illustration.png" />
</a>

<!-- description -->

Read the Docs is a fully open-source platform that builds and publishes documentation.
Read more on [readthedocs.org](https://readthedocs.org/) and [readthedocs.com](https://readthedocs.com/) (Read the Docs for Business).

## Foreword

Many new and exciting documentation projects have emerged in *science and academia*, taking the world of documentation beyond just software projects.
To capture the latest development and trends, we are compiling a list of inspirational uses of documentation technology, especially outside of the traditional field of software documentation.

In addition to showing awesome and real-life Read the Docs projects, a number of [Example Projects](#example-projects) are being built to help people learn and get started.

We hope that this will inspire people writing documentation, developing new documentation projects or updating existing ones.
All projects mentioned here are **open source**, meaning that you can find their source code and understand how it's done.

The list is a work in progress, please feel invited to [contribute](#contributing)!

<!-- TOC -->
<!--lint disable awesome-toc-->
## Contents
<!--lint enable awesome-toc-->

- [Sphinx projects](#sphinx-projects)
- [MkDocs projects](#mkdocs-projects)
- [API Reference](#api-reference)
- [Science projects](#science-projects)
- [Example projects](#example-projects)
- [Tag cloud](#tag-cloud)

<!-- CONTENT -->


## Sphinx projects

- [Scrapy](https://docs.scrapy.org/) - Embeds a lot of reference snippets and uses `sphinx-hoverxref` for quick reference tooltips. Lots of inspiration to be found in content organization. **#sphinx**.
- [setuptools](https://setuptools.pypa.io/) - Lots of features, using the Furo theme. [Twitter thread](https://twitter.com/readthedocs/status/1546527820150718469) with some examples. **#sphinx** **#themes**.
- [sphinxcontrib-needs](https://sphinxcontrib-needs.readthedocs.io/) - Documentation of `sphinxcontrib-needs`. **#sphinx** **#themes**.
- [sphinx-immaterial](https://sphinx-immaterial.readthedocs.io/) - Documentation of `sphinx-immaterial`, a Material theme for Sphinx, based on Material for MkDocs. **#sphinx** **#themes**.
- [Uberspace](https://manual.uberspace.de/) - Customized sidebar and footer, adding project's branding through custom CSS and HTML to `sphinx_rtd_theme`. Latest version and release date on front page. **#sphinx** **#themes** **#custom-theme**.
- [Wagtail](https://docs.wagtail.org/) - Wagtail is a Django-based CMS with a global community. The documentation spans multiple stakeholders (editors and developers), has it's own beautiful theme and is largely structured around Diátaxis ideals. The [Release Notes](https://docs.wagtail.org/en/stable/releases/index.html) and [Contribution guide](https://docs.wagtail.org/en/stable/contributing/index.html) are remarkable. Wagtail's documentation uses a minimal set of Sphinx extensions. **#sphinx** **#themes** **#diataxis**.
- [Weblate](https://docs.weblate.org/) - Weblate is a translation platform with a large documentation project with many translations and customized Read the Docs theme. Documentation aimed at all segments: users, administrators and developers. Also features an extensive Changelog. **#sphinx** **#themes** **#translation**.

## MkDocs projects

- [Argo CD](https://argo-cd.readthedocs.io/) - Material for MkDocs theme with custom colors and a nice version drop down. Animated product demo and carefully designed sidebar presenting targeted guides for Operators, Users and Developers. **#mkdocs** **#themes** **#large-project**.
- [Nautobot](https://docs.nautobot.com/) - Extensive usage of the subprojects feature to organize numerous documentation projects under the same custom domain / landing page. Each subproject has its own release cycle. Features are showcased in [this twitter thread](https://twitter.com/readthedocs/status/1595010133796462593). **#mkdocs** **#themes** **#large-project**.

## API Reference

- [disnake](https://docs.disnake.dev/) - This projects very rich Python API reference uses custom extension for quick overview tables of attributes and methods + `sphinx-hoverxref` for tooltips with API reference + source link references for GitHub source code, see also [Twitter thread](https://twitter.com/readthedocs/status/1541830875037503489) with some examples. **#apidocs** **#sphinx** **#themes**

## Science projects

- [AiiDA demonstration](https://aiida-qe-demo.readthedocs.io/) - A hardware demo/tutorial written with lots of examples and illustrations. [Behind the scenes](https://github.com/chrisjsewell/aiida-qe-demo), Conda is used by installing mambaforge and storing the setup in `environment.yml`.  **#sphinx** **#jupyter-notebook**
- [Crest Ocean System](https://crest.readthedocs.io/) - Uses sphinx-hoverxref and Executable Book. Video tutorials in text. Lots of embeds, Trello, YouTube and more. **#sphinx** **#themes**
- [jupyter-book](https://jupyterbook.org/) - Jupyter-book automatically creates Sphinx projects from projects that are friendly to Jupyter Notebook users. **#jupyter-notebook** **#sphinx** **#diataxis**.
- [jupyter-sphinx](https://jupyter-sphinx.readthedocs.io/) - Directly executes and renders Jupyter Notebooks in documentation projects. **#jupyter-notebook** **#sphinx**.
- [jupyter-tutorial](https://jupyter-tutorial.readthedocs.io/) - Uses a set of extensions for Sphinx, for instance direct rendering of `.ipynb` files with `nbsphinx`. **#jupyter-notebook** **#sphinx**.
- [msticpy](https://msticpy.readthedocs.io/) - MSTIC Jupyter and Python Security Tools, msticpy is a library for InfoSec investigation and hunting in Jupyter Notebooks. **#jupyter-notebook** **#sphinx**.
- [nbsphinx](https://nbsphinx.readthedocs.io/) - Banner and buttons to view interactive versions of currently displayed `*.ipynb` files using the Binder service. Notice also the awesome PDF version. **#jupyter-notebook** **#sphinx**.
- [poliastro](https://docs.poliastro.space/) - An extensive science project, demonstrating rich use of math formulas, interactive plotting in 3d, ``sphinx-hoverxref``, custom 404s and a nice copy button on code examples. Notice how well the navigation reflects the [Diátaxis framework](https://diataxis.fr/)  **#sphinx** **#diataxis**.
- [SunPy](https://docs.sunpy.org/) - A large documentation project for an open-source package for solar physics. Embeds the main website's menu and uses a custom theme. Extensive changelog and release notes. **#custom-theme**, **sphinx**, **#apidocs**.
- [TorchIO](https://torchio.readthedocs.io/) - An open-source Python library targeting 3D medical images in deep learning. Combines API documentation with usage examples, uses "single version" for a singular "rolling release" documentation. [Screenshots in this Twitter thread](https://twitter.com/readthedocs/status/1570339818806120450). **#themes**, **sphinx**.
- [TomoBank](https://tomobank.readthedocs.io/) - A big list of tomographic datasets and phantoms, featuring especially tables and images and maintained by science community. **#sphinx**.

<!-- END CONTENT -->

## Example projects

- [Basic Sphinx example](https://github.com/readthedocs-examples/example-sphinx-basic) - Basic example of using Sphinx on Read the Docs. **#sphinx**.
- [Basic MkDocs example](https://github.com/readthedocs-examples/example-mkdocs-basic) - Basic example of using MkDocs on Read the Docs. **#mkdocs**.
- [Jupyter Book example](https://github.com/readthedocs-examples/example-jupyter-book) - Using Jupyter Book on Read the Docs with popular extensions. **#jupyter-notebook** **#sphinx**.

## Tag cloud

The categories in this list are intersecting at the following tags:

**#sphinx**, **#mkdocs**, **#themes**, **#custom-theme**, **#jupyter-notebook**, **#diataxis**, **#large-project**, **#apidocs**, **#translation**

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/readthedocs-examples/awesome-read-the-docs/graphs/contributors)!
