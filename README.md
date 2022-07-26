# README

[![ci](https://github.com/H-Kwon/h-kwon.github.io/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/H-Kwon/h-kwon.github.io/actions/workflows/ci.yml)
[![pages-build-deployment](https://github.com/H-Kwon/h-kwon.github.io/actions/workflows/pages/pages-build-deployment/badge.svg?branch=main)](https://github.com/H-Kwon/h-kwon.github.io/actions/workflows/pages/pages-build-deployment)

This is to publish Hyeokjin's "README" web pages in order to introduce himself on the Internet.

All the pages are generated by [mkdocs-material].

## Initialization

Create an independent Python environment

```
$ python -m venv .venv
$ . .venv/bin/activate
(.venv) $ pip install --upgrade pip
```

This will automatically install compatible versions of all dependencies: MkDocs, Markdown, Pygments and Python Markdown Extensions. Material for MkDocs always strives to support the latest versions, so there's no need to install those packages separately.

```
(.venv) $ pip install mkdocs-material
```

To create a site, go to the directory where you want your project to be located and enter:
```
(.venv) $ mkdocs new .
.
├─ docs/
│  └─ index.md
└─ mkdocs.yml
```

## Tests

```
(.venv) $ mkdocs serve
```

## References

[mkdocs-material](https://squidfunk.github.io/mkdocs-material/) - Write your documentation in Markdown and create a professional static site in minutes – searchable, customizable, for all devices.
[Dillinger](https://dillinger.io/) - The last markdown editor
[Vercel](https://vercel.com/docs/concepts/git/vercel-for-gitlab) - Vercel for GitLab

## Files

```
.
├── docs
│   ├── assets
│   │   ├── images
│   │   │   ├── ...png 
│   │   │   ├── ...jpg
│   ├── index.md
│   └── stylesheets
│       └── extra.css
├── mkdocs.yml
└── README.md
```

[.mdlrc]: Configuration file of markdownlint
[.yamllint]: Configuration file of yamllint
README.md: The file you are reading right now


[//]: # (These are reference links used in the body of this note)

  [mkdocs-material]: <https://squidfunk.github.io/mkdocs-material/>
  [.yamllint]: <https://yamllint.readthedocs.io/en/stable/configuration.html>
  [.mdlrc]: <https://github.com/markdownlint/markdownlint/blob/master/docs/configuration.md>
