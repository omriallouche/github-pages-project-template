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
Our end result can be seen [here](https://omriallouche.github.io/github-pages-project-template).


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

 The file includes the repo name, the name of the template it should use (in case we don't explicitly provide it, as we do below), additional Jekyll gems, and any additional data we want to have available in the pages.
 In the example code provided, we use the following data:
 ```
owner_display_name: Omri Allouche
owner_bio: Entrepreneur, Data Scientist and Software engineer, with a PhD in Computational Ecology and 15 years experience leading R&amp;D teams and managing startups.
owner_facebook_username: omri.allouche
owner_linkedin_url: https://www.linkedin.com/in/omria
twitter:
  username: GilgameshSleeps
facebook:
  admins: omri.allouche
google_analytics: UA-89870336-1
 ```

 The parameters we provide are available in the Jekyll template and pages under the `site` variable. For example, in our example {{site.owner_display_name}} will be compiled to `Omri Allouche`.

 Note that we added the [SEO tags gem](https://github.com/jekyll/jekyll-seo-tag), to improve our project's visibility to search engines. The gem [documentation]((https://github.com/jekyll/jekyll-seo-tag)) describes additional tags you can set in your `_config.yml` file, in case you need more control.


##### Create a `_layouts` folder with the template html
 Inside the file `_layouts/default.html`, we'll put the html of our page template, that will be shared among different pages.

## Contributing
Pull requests are welcome!



 
