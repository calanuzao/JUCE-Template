# Audio Plugin Template

## Features

- **Clear Project Structure**: Get started quickly with a well-organized repository structure.
- **Latest C++ Standards**: Utilize modern C++ features with support for C++23 standard.
- **Effortless Dependency Management**: Easily integrate third-party C++ libraries using the CPM package manager, alongside JUCE.
- **Safety First**: Ensure code safety with the highest warning level and "treat warnings as errors" settings.
- **Ready-to-Use Unit Testing**: Start testing your audio plugin with GoogleTest right away.

## Additional Benefits

- **Continuous Integration**: Enable continuous integration with GitHub Actions, automatically building and testing on each push and pull request.
- **Automatic Code Formatting**: Never worry about code formatting inconsistencies with automatic clang-format on every commit.

## Usage

1. **Create Your Own Repo**: Click "Use this template" on GitHub to create your own repository based on this template.
2. **Clone Locally**: Clone the newly created repository to your local machine.

## Run CMake Workflow

```bash
$ cmake -S . -B build
$ cmake --build build

Note: The first run may take longer as dependencies (CPM, JUCE, and googletest) are downloaded.

## Enable Clang-Format

```bash
pre-commit install

(Install pre-commit with pip if necessary: pip install pre-commit).

Don't forget to replace "YourPluginName" with your actual plugin name throughout the project.
