# Sass File Structure

In this repo, I have prepared the right structural environment for the projects that use [Sass](https://sass-lang.com/).

## Structure

- abstracts

  - `_functions.scss` -> will include user defined functions.
  - `_mixins.scss` -> will include your mixin. <br />
    **`In this file I put some of useful mixins you can see it. ex: Media Query Manager mixin (mq) `**
  - `_variables.scss` -> will include your variables.
  
- base
  
  - `_animations.scss` -> will include your animations.
  - `_base.scss` -> will include your styles for default elements.
  - `_typography.scss` -> will include typography styles. ex: font-family, font-size, color, ....
  - `_utilities.scss` -> will include your custom utilities.

- components

      add component styles here, It is preferred to make file for every component.

- layout

      styles for repeated layouts like: header, footer, navigation, etc...

- pages

      If there is specific style for element in specific page you can add it here in file with page name.
      like: home, about, etc...

- `main.scss`

      Main File that will import other files on it.

## Notes

> This is the appropriate structure of my mind, you can modify it as you desire.
