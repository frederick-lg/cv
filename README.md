# Curriculum Vitae

## Overview

This repo stores all the files required to create my CV. The software used
to create the CV is LaTeX, a document preparation system.

These files are a copy of the project found
[here](https://www.overleaf.com/project/5d1f69917d0f5a527bcfbc10). I have
adapted some functions, styles and of course the content to create my own CV.

## Usage

### Setup

**Mac**

1. Download and install [Brew](https://brew.sh/).
2. Using Brew, execute the following command to install the required LaTeX compiler:

> **NOTE**: You may be required to enter your machine password here, do it and
hit enter to proceed with installation.

```
brew cask install mactex
```

3. Open a new terminal and verify the installation:
```
╰─ which latex
/Library/TeX/texbin/latex
```

### Generating the PDF

Simply execute the following commands:

```
# Navigate to the cv directory
cd cv

# Execute the build
lualatex cv.tex
```

> **NOTE**: Hold the return key to ignore all prompts that come up during the
build (not sure there's a flag to auto-approve prompts). You'll know when you're
at the first prompt when you see a `?` and the log output stops.

Once complete there should be a few new files in the directory and the penultimate
console output should read something like - `Output written on cv.pdf (2 pages, 26999 bytes)`.

Done!
