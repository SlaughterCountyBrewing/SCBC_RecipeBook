<div align="center">

  <img src="../assets/media/scb_logo.png" alt="logo" width="200" height="auto" />
    <h1><a href="https://github.com/SlaughterCountyBrewing/SCBC_RecipeBook">SlaughterCountyBrewing/SCBC_RecipeBook</a></h1>
  <h3>Technical Repository Notes</h3>
  
  
<!-- Badges -->
<p>
  <a href="https://github.com/SlaughterCountyBrewing/SCBC_RecipeBook/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/SlaughterCountyBrewing/SCBC_RecipeBook" alt="contributors" />
  </a>
  <a href="">
    <img src="https://img.shields.io/github/last-commit/SlaughterCountyBrewing/SCBC_RecipeBook" alt="last update" />
  </a>
  <a href="https://github.com/SlaughterCountyBrewing/SCBC_RecipeBook/network/members">
    <img src="https://img.shields.io/github/forks/SlaughterCountyBrewing/SCBC_RecipeBook" alt="forks" />
  </a>
  <a href="https://github.com/SlaughterCountyBrewing/SCBC_RecipeBook/stargazers">
    <img src="https://img.shields.io/github/stars/SlaughterCountyBrewing/SCBC_RecipeBook" alt="stars" />
  </a>
  <a href="https://github.com/SlaughterCountyBrewing/SCBC_RecipeBook/issues/">
    <img src="https://img.shields.io/github/issues/SlaughterCountyBrewing/SCBC_RecipeBook" alt="open issues" />
  </a>
  <a href="https://github.com/SlaughterCountyBrewing/SCBC_RecipeBook/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/SlaughterCountyBrewing/SCBC_RecipeBook.svg" alt="license" />
  </a>
  <a href="https://discord.gg/gQH4mXWQRT">
    <!--<img src="https://img.shields.io/discord/704680098577514527?style=flat-square&label=%F0%9F%92%AC%20discord&color=00ACD7">-->
    <img src="https://img.shields.io/discord/1052011377415438346?style=flat-square&label=discord&color=00ACD7">
  </a>
</p>
   
<h4>
    <a href="https://github.com/SlaughterCountyBrewing/SCBC_RecipeBook/blob/main/README.md">Documentation</a>
  <span> · </span>
    <a href="https://github.com/SlaughterCountyBrewing/SCBC_RecipeBook/issues/new?labels=bug&title=%5BBUG%5D">Report Bug</a>
  <span> · </span>
    <a href="https://github.com/SlaughterCountyBrewing/SCBC_RecipeBook/issues/new?labels=enhancement&title=%5BFEATURE+REQUEST%5D">Request Feature</a>
  </h4>
</div>

**SCBC_Recipebook** was initialized using the [ScooterGitTemplate](https://github.com/ScottKirvan/ScooterGitTemplate), so it automatically includes the structure, functions, and automations outlined below.


Branches
--------
`main` is the [deployed](https://slaughtercountybrewing.github.io/SCBC_RecipeBook/) branch.  The repo doesn't currently contain any other historic or dev branches.

Base Repo Layout
-----------
```
SCBS_RecipeBook
├───_layouts
├───.github
│   ├───release-please
│   └───workflows
├───assets
│   ├───css
│   └───media
└───notes
```
The `_layouts` and `assets/css` folders help support the look of the repo when rended to GitHub Pages (Deployment Workflow). 
You can see an example of this repo processed using Jekyll and published at [SlaughterCountyBrewing.github.io](https://slaughtercountybrewing.github.io/SCBC_RecipeBook/).  You have to enable **Pages** in your repo's settings.  Details [here](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll).

The css file creates a page that is styled similar to GitHub's [Dark High Contrast](https://github.blog/changelog/2021-08-25-dark-high-contrast-theme-ga/) theme.

The files in the `.github` folder implement and customizes a github action that runs [Release-Please](https://github.com/googleapis/release-please), which helps with releases, version numbering, and updating the [CHANGELOG](notes/CHANGELOG.md).

>[!NOTE]
> Release-Please uses [Semantic Versioning](https://semver.org/) (version: MAJOR.MINOR.PATCH). Changes to version numbers are triggered by specific keywords in your commit messages:
> - `feat:` (new feature) will bump the MINOR version number.
> - `fix:` (bug fixes) will bump the PATCH number.
> - `feat!:` `fix!:` or any `xxx!:` (major and breaking changes) will bump the MAJOR version number.



Contributions / Contact
-----------------------
- Please [file an issue](https://github.com/SlaughterCountyBrewing/SCBC_RecipeBook/issues/new), or [grab a fork](https://github.com/SlaughterCountyBrewing/SCBC_RecipeBook/fork), hack away, and submit a [pull request](https://github.com/SlaughterCountyBrewing/SCBC_RecipeBook/pulls).
- Contact me at [linkedin.com/in/scottkirvan/](https://www.linkedin.com/in/scottkirvan/)
- You can also contact me at my [discord](https://discord.gg/TSKHvVFYxB) server, I'm cptvideo.

Credits
-------
**Copyright (c) (2025):** [Scott Kirvan](https://github.com/ScottKirvan)  - All rights reserved   
*SCBC_Recipebook is licensed under the [MIT License](LICENSE.md).*  

Project Link:  [SCBC_Recipebook](https://github.com/SlaughterCountyBrewing/SCBC_RecipeBook)  
[CHANGELOG](notes/CHANGELOG.md)  
[TODO](notes/TODO.md)
