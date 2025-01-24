# Images for Crossmaps Project


## Submoduling Instructions

Run these commands from inside the target repo (i.e. the one you want
these images to be available in)

To add the contents of the latest commit of the default branch of this
repo as the folder `images/`:

``` zsh
git submodule add <repo-url.git> images
```

Updating contents to match the latest commit:

``` zsh
git submodule update --remote --merge
```

to match remote:

``` zsh
git submodule update --remote --rebase
```

## Useful ImageMagick Commands

Crop & transparent background:

``` zsh
convert filename.png -trim -transparent white filename.png
```

For details see:
<https://www.cynthiahqy.com/posts/imagemagick-basic-trim/>

## Setup pre-commit hook

To make sure this README renders every time you add a new commit, move
the file `pre-commit` to `.git/hooks/` and make the script executable:
`chmod +x .git/hooks/pre-commit`

## Images

Make sure to render README.qmd again after adding new images

## Illustrations

## Plots

## Screenshots
