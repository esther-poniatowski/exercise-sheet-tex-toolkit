# exercise-sheet-tex-toolkit

## Overview

Utility package designed to streamline the creation of exercise sheets in LaTeX. 
By automating common formatting tasks, this toolkit allows users to focus on content creation.


## Features

This package provides a set of macros and styles that are relevant in the content of educational resources:
- **Mcros**: Simplify common exercise sheet elements (e.g. questions numbering, exercise titles, problem statements).
- **Styles**: Ensure a consistent layout for exercise sheets through customizable style options


## Installation

To use `exercise-sheet-tex-toolkit` in a LaTeX project:

1. Add the repository as a submodule in a designated directory (e.g. `./include/`):

```bash
git submodule add https://github.com/username/exercise-sheet-tex-toolkit.git include/exercise-sheet-tex-toolkit
```

2. (Optinal) Add the path to the toolkit directory to LaTeX search path. Options include:
- Updating the TEXINPUTS environment variable.
- Modifying the local project configuration file (e.g., `.latexmkrc`).
- Adding any other custom method relevant to the setup (e.g., tools in LaTeX Workshop extention, if using VS Code).

## Usage

1. In a LaTeX document, import the package:

- If the package directory is in the LaTeX search path:
```latex
\usepackage{exercise-sheet-tex-toolkit}
```

- Otherwise, specify the relative path:
```latex
\usepackage{./include/exercise-sheet-tex-toolkit/exercise-sheet-tex-toolkit}
```

2. Utilize the provided macros and styles in the document. Refer to the package documentation for detailed usage instructions and examples.


## Versioning

Stable releases are tagged on the `main` branch.

To select a specific version compatible with a project, check out the corresponding tag:

```bash
cd include/exercise-sheet-tex-toolkit
git checkout v1.2.3
```

> [!NOTE]
> The project follows a Git flow versioning strategy.
