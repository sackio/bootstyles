# bootstyles

Style Bootstrap, showcase on a demo site, and package up the assets for export

## Getting Started
Bootstyles makes it easier to create a unique Bootstrap themes.

**./src/less** contains LESS files breaking up Bootstrap's variables into five categories:

*   **colors.less** - any variable having to do with coloring/shading
*   **fonts.less** - variables related to font style (font family, shadows, weight - not spacing and sizing)
*   **sizing.less** - variables related to sizing and spacing (font sizes, line height, padding, margins, width/height - think px and %)
*   **borders.less** - any variable having to do with border radii (border colors, spacing, etc. are in other files)
*   **layouts.less** - layering and responsive variables (z-indices, container sizing, grids)

**./demo** contains a minimized version of the Bootstrap documentation site. A single page showcases all CSS, components, and Javascript elements, just add a bootstrap.min.js file to the **./demo/dist/css** directory

If there's interest in the project, I'm happy to add some generators for automatically building themes (LESS compilation, minification, etc.). For now, I'm manually building themes by appending @import directives at the end of a standard varibles.less file. Other ideas about better categorizing the LESS for theming would be very helpful.

## License
Copyright (c) 2014 Ben Sack  
Licensed under the MIT license.
