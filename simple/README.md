# The Simple IDX Rabbit Template Pack

This template works best with the Bootstrap framework as it already uses classes that exist within that framework, but these templates can be easily modified to work with any CSS framework.

Small pieces of jQuery are also used to enhance template functionality, but that code can easily be converted over to vanilla JS or removed.

## Structure

The main views are housed in the aptly named **views** directory. These templates serve as parent views in that they include partials from the other directories which will be described below.

### Layouts

This directory houses two layout templates which help with displaying collections of listings with two common formats: grid and list.

These two formats in turn take the responsibility of including templates from the **listings** directory.

### Listings

You will find two different templates in this directory.

1. `grid_item.html` is responsible for displaying a grid property
2. `list_item.html` is responsible for displaying a property in a list

### Macros

Inside the two previous item templates, you'll find the usage of the import directive for pulling in some handy macro templates.

Macros are a construct which the Twig templating engine provides as a means of creating reusable functions which can perform template logics using Twgi syntax to produce a desired HTML output.

The `errors.html` macro for instance houses two different macros which are responsible for formatting and outputting errors.

### Modals

This final directory houses templates which are specifically usesful when building with the Bootstrap framework.