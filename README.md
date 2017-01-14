# Github Pages Template
Use this Template to accompany your repository with a demo, documentation etc.
It uses github preset to automatically match your repository with links etc., and adds a few useful widgets to the page:
 - Header
     - Repository name and description
     - GitHub Star and Fork widgets
 - Main content area
     - Containing your own content
 - Footer
     - Link to the github repository
     - Social sharing links (through Facebook, Twitter and LinkedIn)
 - Sidebar
     - Author box
     - Author social links
     - Twitter follow button

### Demo
Our end result can be seen [here](https://omriallouche.github.io/github-pages-personal-template).


## Introduction:
GitHub is the world's leading git repository host, but also offers a powerful static site hosting through its [GitHub Pages](https://pages.github.com/) feature.
The pages can include html, js and css, and be served using the GitHub CDN, offering a free solution for basic sites.
By default, the pages are automatically compiled by the [Jekyll](https://jekyllrb.com/) static site generator, and can even be connected to a custom domain.

## Improving your repo with accompanying pages
 So we've created the coolest ever Javascript library. We feel proud, and rightly so.
 Unfortunately, without a proper README file and an appealing demo, most changes are our library will never enjoy its well-deserved 15 minutes of fame.
 To provide basic text for our repo, we simply need to create a README.md file in our root directory, that contains markdown.
 GitHub automatically presents the compiled README.md file in each folder it finds it.

 To create a static page, we'll follow these steps:

##### Activate the GitHub Pages feature
Simply follow [this guide](https://guides.github.com/features/pages/) from GitHub.

##### Create a _config.yml file
 In your repo's root directory, add a `_config.yml` file.

 The file includes the repo name, the name of the template it should use (in case we don't explicitly provide it, as we do below), and additional Jekyll gems. In our case, we'll add the SEO tags gem, to improve our project's visibility to search engines.

##### Create a `_layouts` folder with the template html
 Inside the file `_layouts/default.html`, we'll put the html of our page template, that will be shared among different pages.

## Contributing
Pull requests are welcome!



 
