# My Game Documentation

>📝 **NOTE:** Different approaches exist for having useful documentation at hand. The best one will depend on the characteristics, the size and preferences of the development team. One approach is to have all the documentation in this `docs` folder with a thoughtful file structure. You can also keep the documentation in the [wiki pages](https://docs.github.com/en/communities/documenting-your-project-with-wikis/about-wikis) of your game's GitHub repository. It is also possible to follow a mixed approach, where internal documents that are only relevant to the team are written in the wiki, while documents that can be of interest to external people are located in the `docs` folder. And of course there is always the possibility to have all documentation in an external space, completely independent of the game's repository.

Keeping up-to-date documentation is critically important in video game development, because the process can be highly collaborative, complex, and often subject to change. Documentation, especially the Game Design Document (GDD), acts as the central, single source of truth that guides the entire team.

Having clear and accessible documentation from the beginning of the project is crucial to have a shared understanding of the goals and expectation of the game. This will allow for new team members to get on-board faster and to better understand the project's vision.

The current documentation makes use of [Material](https://squidfunk.github.io/mkdocs-material/) for [MkDocs](https://www.mkdocs.org/). Make sure that all team members are familiar with how documents are created using this framework.

## How to use the docs



### Installation

To get started, make sure that Python is installed in your system. It is preferred to install Material framework in a virtual environment:

```shell
python -m venv venv
.\venv\Scripts\activate.bat
pip install mkdocs-material
```

### Local Documentation



mkdocs serve

Settings add

"yaml.schemas": {
        "https://squidfunk.github.io/mkdocs-material/schema.json": "mkdocs.yml"
    },
    "yaml.customTags": [
        "!ENV scalar",
        "!ENV sequence",
        "!relative scalar",
        "tag:yaml.org,2002:python/name:material.extensions.emoji.to_svg",
        "tag:yaml.org,2002:python/name:material.extensions.emoji.twemoji",
        "tag:yaml.org,2002:python/name:pymdownx.superfences.fence_code_format"
    ]


For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
