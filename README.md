# Portfolio
Hi there, thank you for stopping and looking at my portfolio page.

## Setup and Server
### Setup
To get the source code
``` bash
git clone git@github.com:erik-trantt/erik-trantt.github.io.git
cd erik-trantt.github.io
bundle install
```
### Server
The site is powered by Jekyll static site generator.
Jekyll is a Ruby gem that can be installed on most computers.
Requirements:
- *Ruby* (version *2.5* and above)
- *RubyGems*

Details installation guidelines for your platforms can be found in the [official documenation](https://jekyllrb.com/docs/installation/):
- [macOS](https://jekyllrb.com/docs/installation/macos/)
- [Ubuntu](https://jekyllrb.com/docs/installation/ubuntu/)
- [Windows](https://jekyllrb.com/docs/installation/windows/)

### Deployment
#### Running it locally
``` bash
bundle exec jekyll serve
```
Open your browser and go to [http://127.0.0.1:4000/](http://127.0.0.1:4000/)

#### BYO (Built your own)
GitHub Pages support Jekyll. Simply clone the project and push to your own GitHub repo.
Follow this [guideline](https://guides.github.com/features/pages/) to turn a GitHub repo into GitHub Page.

*Any commits to master branch is auto-deployed to your GitHub Page.*

## The site
**Site:** https://eriktran.me/

**GP Pages Link:** https://erik-trantt.github.io/

My site is continuously developed and maintained by myself.

## Tech stacks and Tools:
- Github & Github Pages - version control and hosting the development site
- Jekyll - building and deploying the site
- SASS and SCSS Syntax - stylesheet preprocessor
- Figma - Wireframe
- VS Code, Sublime Text 3 - coding

## Stylesheets
Organizing my stylesheets into this simple structure: 
- _sass/
  - main.scss
    - _base.scss
      - css-reset.css
    - _layout.scss
    - _components.scss
- assets/
  - css/
    - plugins/
      - icofont/
    - styles.scss

## Plugins
- [jekyll-autoprefixer](https://github.com/vwochnik/jekyll-autoprefixer) for auto-prefixing CSS properties.

## Resources
- Webring [Webring](https://webring.xxiivv.com/#random) for inspirations on my personal portfolio
- [Lennon](https://lennonzf.me)'s advice on stylings and structures
- CSS-Tricks for tips and snippets on how to structure my Sassy CSS and usage:
  - [https://www.creativebloq.com/how-to/how-to-structure-media-queries-in-sass](https://www.creativebloq.com/how-to/how-to-structure-media-queries-in-sass)
  - [https://css-tricks.com/approaches-media-queries-sass/](https://css-tricks.com/approaches-media-queries-sass/)
  - [https://css-tricks.com/autoprefixer/](https://css-tricks.com/autoprefixer/)
