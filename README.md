# [Solvomon.com](https://solvomon.com)

Source code for Solvomon ltd. (Solvomon d.o.o.) homepage.

------

- Based on [Start Bootstrap - Agency](https://startbootstrap.com/template-overviews/agency/) template.
- Header image from [Unsplash]().
- Contact image from [Unsplash]().

## Development

To begin hacking on this project first clone the repo:

```
git clone https://github.com/MislavCimpersak/solvomon.com.git
```

install required packages:

```
npm install
```

and run live reloading dev server with _gulp_:

```
gulp dev
```

### Gulp Cheatsheet

- `gulp` the default task that builds everything
- `gulp dev` browserSync opens the project in your default browser and live reloads when changes are made
- `gulp sass` compiles SCSS files into CSS
- `gulp minify-css` minifies the compiled CSS file
- `gulp minify-js` minifies the themes JS file
- `gulp copy` copies dependencies from node_modules to the vendor directory
