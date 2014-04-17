## open.edx.org

This is the landing page for open.edx.org, hosted by Github Pages.

- - -

### Dependencies

The static front end of this page/site is built with the following resources:

* [Bourbon](http://bourbon.io/) - Basic Sass Utilities/Framework
* [Neat](http://neat.bourbon.io/) - Sass Grid/Responsive Design System
* [Font Awesome v3.2.1](http://fontawesome.io/3.2.1/) - Font/Vector Icons


### Sass/CSS Rendering

The page/site relies on [Sass](http://sass-lang.com/) to compile its production CSS file ([assets/css/main.css](assets/css/main.css)). No CSS files should be directly edited because of this. Instead, all Sass partial files contained in assets/sass control presentation.

To preview changes and compile Sass locally, you can use an existing workflow tool like [Grunt](), [Gulp](), or GUI  like [CodeKit]() or have a local copy of the Sass Ruby Gem watch the assets/sass directory for changes and compile them into ([assets/css/main.css](assets/css/main.css)). Here are basic instructions for that last option:

1. Install sass gem locally: ```gem install sass```
2. Watch this project's sass directory for changes + compile in compressed format: ```sass --watch assets/sass:assets/css --style compressed```
