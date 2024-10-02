# LaTeX Math Homework Template

This repository contains a LaTeX template designed for math homework assignments. It provides a clean, professional layout with pre-defined environments for problems, solutions, remarks, and proofs.

## Features

- Custom title page with course information
- Pre-defined environments for problems and solutions
- Remark environment for additional notes
- Proof environment
- Custom vector and unit vector commands
- Built-in support for equations, figures, and footnotes
- Customizable page layout

## Requirements

- A LaTeX distribution (e.g., TeX Live, MiKTeX)
- A LaTeX editor (e.g., TeXstudio, Overleaf, VS Code with LaTeX Workshop)

## Usage

1. Clone this repository or download the `Template.tex` file.
2. Open the template in your LaTeX editor.
3. Modify the `\SheetTitle` command with your assignment details:
   ```latex
   \SheetTitle{Problem Set Title}{Course Name}{Author Name}{Professor Name}
   ```
4. Add your problems and solutions using the pre-defined environments:
   ```latex
   \begin{p}
     Problem statement here.
   \end{p}

   \begin{solution}
     Solution goes here.
   \end{solution}
   ```
5. Compile the document to generate your PDF.

## Customization

- Modify the preamble to add or remove packages as needed.
- Adjust the page margins in the `\usepackage[letterpaper,margin=1in,bottom=0.7in]{geometry}` line.
- Change the colors defined in the preamble (`bluee`, `redd`, `greenn`) to match your preferences.

## Environment Descriptions

- `p`: Use for stating problems
- `solution`: Use for writing solutions (includes a box and proof environment)
- `remark`: Use for adding remarks or notes
- `proof`: Standard proof environment

## Contributing

Feel free to fork this repository and submit pull requests with improvements or additional features.

## License

This template is provided under the [MIT License](LICENSE). Feel free to use, modify, and distribute it as you see fit.
