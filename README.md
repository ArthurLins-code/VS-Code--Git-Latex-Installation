# VS Code, Git, and LaTeX Installation Guide

A complete, step-by-step setup manual for Windows users who want to build a working environment for editing R scripts, writing LaTeX documents, and using Git and GitHub — all from Visual Studio Code. Written for academic researchers with **zero command-line experience**, the guide assumes only that you already have R and RStudio installed and walks you through everything else.

---

## What You Will Set Up

1. **Git for Windows** — the version-control engine.
2. **A GitHub account** — your cloud home for repositories.
3. **GitHub Desktop** — a visual interface for Git.
4. **Visual Studio Code** — your editor.
5. **MiKTeX** — the LaTeX distribution that compiles `.tex` files into PDFs.
6. **Strawberry Perl** *(optional)* — only needed for the `latexmk` build tool.
7. **VS Code extensions** — support for R, LaTeX, Git, Markdown, and spell-checking.

Each section is self-contained, so you can jump directly to the tool you need.

## Prerequisites

- Windows 10 or Windows 11 (64-bit).
- R and RStudio already installed.
- About 60 to 90 minutes (mostly waiting for downloads).

## How to Read the Guide

- **On GitHub:** open [`vscode_git_latex_setup_guide.md`](vscode_git_latex_setup_guide.md).
- **Offline or printed:** download [`vscode_git_latex_setup_guide.pdf`](vscode_git_latex_setup_guide.pdf) — a typeset PDF with a numbered table of contents.

## Tips from the Author

A few practical shortcuts and observations to save you time as you work through the guide:

- **If you already have a GitHub account**, you don't need to make a new one (obviously) — just skip Section 3.
- **Install the VS Code extensions from inside VS Code**, not via the marketplace links the guide shows. They aren't strictly marked as mandatory in the text, but they're easy to find — a quick Google search will show you where the Extensions panel lives.
- **The two extensions that matter most** are **8.2 LaTeX Workshop** (a strong stand-in for Overleaf) and **8.3 GitLens** (great for tracking changes to a file through Git and GitHub). That said, I recommend installing all of them — I haven't personally used the last three, but they look interesting.
- **You don't have to run the workflows in Section 9.** They're just good examples to come back to later; Workflow 9.2 (compiling a LaTeX document in VS Code) is the one I'd actually recommend trying.
- **I haven't fully reviewed Section 10 (Troubleshooting)**, but it should help if you run into errors.
