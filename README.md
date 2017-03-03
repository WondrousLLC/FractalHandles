# Fractal Handles

Drupal 8 module. Convert a fractal Handle '#componentName' to a twig template path.

# Usage

Similar to the drupal module [Components Library](https://www.drupal.org/project/components/)
this module allows you to have a folder called `components` in your active theme.
Within this folder you can put `components/into/any/folder/a_file.twig` and it will be
discovered by referencing it via

```twig
{% include '#a_file' %}
```

# Credits

code base: [github.com/WondrousLLC/fractal_handles](https://github.com/WondrousLLC/fractal_handles/)

developed by [WONDROUS LLC](https://www.wearewondrous.com/)