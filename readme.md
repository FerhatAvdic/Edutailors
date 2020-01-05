#### Running the project

- bundle update
- bundle exec jekyll serve

#### Building the project

- jekyll build

#### Editing the text

- open _includes folder and find the about.md or terms.md file to edit
- both files use markdown to style the text

#### Editing the social links

- open the _data folder and find the social_links.yml file
- change the text or url in the list

#### Changing the images

- located in assets
- source reference is found in:
  * _layouts/home.html for the instagram screenshot, 
  * _includes/navigation.html for logo
- either change the images in assets and set the same filename and file extension, or change the source text

#### Changing the colors

- the style is found in assets/sass/style.scss
- the colors can be changed in the following part:

```scss
$theme-colors:(
  "primary": #00A6B8,
  "purple": rgb(58, 24, 146)
);
```