# [Your Game Title]

>📝 **NOTE:** This is a template project from the [Godot Starter](https://github.com/TopScales/godot_starter) repository. To get more information on how to start working with the template, have a look into the corresponding [documentation](docs/starter/godot_starter).

>📝 **NOTE:** Make sure to keep only information that is relevant to your project. Remove all unnecessary documentation and notes (like this one).

Game description. A small paragraph about your game. Don't use bullet points here. Make it brief, highlighting the core idea of the game and the features that make it different or distinguishable.

>📝 **NOTE:** Add a showcase image. You can start with just a simple logo, or a screenshot of the game.

<p align="center">
  <img src="assets/logo/logo.png" />
</p>

*Presentation of your game in one sentence. You can relate the phrase with the picture above*

## 🛠️ Getting Started

To start working on this project, go through the next steps:

>📝 **NOTE:** Select one of the following options for editing the project.

[Easiest standard way]
- Get **Godot 4.5.1** editor from the official [Godot website](https://downloads.godotengine.org/?version=4.5.1&flavor=stable&slug=win64.exe.zip&platform=windows.64)
- Clone the project `git clone git@github.com:TopScales/godot_starter.git`
- Open the project using the editor

[Custom Editor Using VSCode]

- Clone the project `git clone git@github.com:TopScales/godot_starter.git`
- Update all submodules `git submodule update --init`
- Checkout the correct Godot editor branch for your project
- Copy the content of the `misc/vscode` folder and paste it in a new folder called `.vscode`
- Compile the editor by using one of the available tasks in VSCode. Press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>B</kbd> and select `Build Custom Editor` or `Build Custom Editor (DEBUG)`
- Run the editor from VScode. Go to `Run and Debug` in the activity bar of VSCode and run by pressing the play button.

## 🖼️ Overview

To keep the project organized, different types of files are stored in specific folders. The project follows the next file structure.

>📝 **NOTE:** Choose a file structure that works for your project and enforce the usage of such structure throughout development.

```{.yaml .no-copy}
root/
│
├── addons/             # Addons and tools used for the project
├── assets/
│   ├── icons/
│   │   ├── classes/    # Contains icons used for classes. Only for the editor
│   │   └── system/     # Game system icons
│   ├── meshes/         # Meshes of 3D objects
│   ├── materials/      # All materials included those of 3D objects
│   ├── textures/       # Textures and images
│   └── sounds/         # Sounds
├── data/               # Game data
├── docs/               # Documentation folder
├── godot/              # Includes the Godot source used for this project and other Godot modules
├── libs/               # GDExtension libraries
├── misc/               # Miscellaneous files, like vscode specific files
├── scenes/             # Game scenes and scripts
├── tests/              # Contains scenes and scripts to test different game modules
├── LICENSE             # License file
├── mkdocs.yml          # MkDocs configuration file
├── project.godot       # Godot project file
├── README.md           # Project README
└── version.tres        # Version file
```

### Scenes and Assets

Scenes and assets shouldn't be mixed in the same folders. They have each one their own folders. This approach makes it easy to reuse the same assets in multiple scenes and avoids file cluttering per folder.

### Documentation

Inside the `docs` folder, there's all the documentation related to the game and its development. Check the [index file](docs/index.md) for instruction on how to generate the documentation locally or where to check it online.

## 🤝 Guidelines

Please make sure to follow these guidelines while working on the project. It's important to have conventions on how files are named and a code style for all languages used during development.

Use *snake_case* names for all files and folders. Make sure to never use whitespaces in file names. This makes files names clear, with words being separated by underscores. In addition, it's cross platform friendly by avoiding case conflicts that could more easily occur when using capitalized names.

For GDScript, use the official [style guide](https://docs.godotengine.org/en/latest/tutorials/scripting/gdscript/gdscript_styleguide.html) convention. For C++ modules and libraries, use the same [style](https://contributing.godotengine.org/en/latest/engine/guidelines/code_style.html) as Godot's source code. This, of course, doesn't apply to third-party libraries which could have their own code style.

During development, constantly test the modules you're working on to ensure the quality of the game. When developing GDScript modules, always use [GUT](https://gut.readthedocs.io/en/v9.5.0/) unit tests. For C++ modules, make [test units](https://docs.godotengine.org/en/stable/engine_details/architecture/unit_testing.html) as explained in Godot's documentation.

## 🛎️ Support

List of lead developers

## 🚀 Deploying the game

Instructions on how to deploy for testing (is better to use links to other documents)

## 🪪 License

License
