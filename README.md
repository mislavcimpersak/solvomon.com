# ![solvomon.com](/img/color_logo_with_background.png)

Source code for Solvomon llc. (Solvomon d.o.o.) homepage.

------

- Based on [Start Bootstrap - Agency](https://startbootstrap.com/template-overviews/agency/) template.
- Header image from by [Scott Rock on Unsplash](https://unsplash.com/@scottrockphoto?utm_medium=referral&amp;utm_campaign=photographer-credit&amp;utm_content=solvomon).
- Contact image from by [Fabian Kozdon on Unsplash](https://unsplash.com/photos/5ZeooCGNw3s?utm_source=unsplash&utm_medium=referral&utm_content=solvomon).

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
