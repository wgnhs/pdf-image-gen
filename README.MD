# pdf-image-gen
Simple web app for generating a thumbnail image from a PDF document. Used to generate thumbnails displayed in the [WGNHS publications catalog](https://wgnhs.wisc.edu/catalog).

Live app: https://wgnhs.github.io/pdf-image-gen/

# Development
This project requires [NodeJS 8+](https://nodejs.org/) installed on your development system. We recommend using the latest LTS version.

## Pre-requisites

- Git and Git Bash (if using Windows)

## 
1. Clone this repository to your computer

        git clone https://github.com/wgnhs/pdf-image-gen.git

2. Move into the directory that contains the repo you just cloned

        cd pdf-image-gen

2. Checkout a new feature branch using Git

        git checkout -b my-feature-branch

3. Open index.html in the code editor of your choice, make desired changes and save.

4. Add, commit and push the changes using Git.

        git add index.html
        git commit -m "Updates to make this app even better"
        git push origin my-feature-branch

4. Sign into Github and navigate to this repository https://github.com/wgnhs/pdf-image-gen
5. Click Pull requests then New pull requests (or go to https://github.com/wgnhs/pdf-image-gen/compare)
6. Leave `base:master`, set compare to your working branch, ex `compare:my-feature-branch` and click Create pull request
7. Add any additional comments in the Description box click Create pull request
8. Click Merge pull request, then click Confirm merge
9. After the pull request is successfully merged, the [built-in Github pages build deployment action](https://github.com/wgnhs/pdf-image-gen/actions/workflows/pages/pages-build-deployment) will be triggered. This action builds the code and publishes it https://wgnhs.github.io/pdf-image-gen. Progress of this action also appears https://github.com/wgnhs/pdf-image-gen/actions . 
