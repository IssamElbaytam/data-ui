---
layout: default
---

`data-ui` is a collection of modules & documentation of approaches for editing & managing data through user interfaces.

- **[data-ui on Github](http://github.com/sethvincent/data-ui)**
- **[Discussions, tasks, and issue reporting](http://github.com/sethvincent/data-ui/issues)**
- **[Contributing guidelines](CONTRIBUTING.md)**
- **[Resources](resources.md)**

## The goal

Create a set of open source js, css, & html packages that provide accessible, easy-to-use tools related to editing & managing various kinds of data sets & data types.

## Objectives

- Document current approaches to providing interfaces for editing loosely-structured data
- Mockup, prototype, & user test a wide range of approaches to editing, validating, & organizing data through a user interface
- Build npm packages for the approaches that best address problems
- Use the npm packages to build editors for projects like [dat](http://github.com/maxogden/dat) & [editdata.org](http://editdata.org), content management systems, etc.

## Focus areas include:

- tabular grid editing
- interfaces for editing loosely structured data that are _not_ a spreadsheet-like grid, possibly including:
  - a blog admin-style interface
  - a streamlined ui similar to inbox.google.com
  - interactive input similar to slack's onboarding prompts
  - one field at a time similar to typeform.com
- activity stream & notifications about changes to data sets
- revision history & showing diffs of changes
- automating population of additional fields based on input in one field
- input helpers for various data types
- data validation ui helpers
- team production/editorial workflows for data sets
- ordering & filtering data
- realtime editing

## Modules
- [data-editor](http://github.com/editdata/data-editor) – a flexible editor for data
- [data-format](http://github.com/editdata/data-format) – format data for use in various [data-ui](https://github.com/editdata/data-ui) modules
- [data-grid](http://github.com/editdata/data-grid) – a grid editor/viewer for data
- [data-map](http://github.com/editdata/data-map) – show a dataset on a map
- [data-form](http://github.com/editdata/data-form) – turn a row in a dataset into a form
- [data-fields](http://github.com/editdata/data-fields) – fields for editing & displaying data
  - [data-field-geojson](http://github.com/editdata/data-field-geojson) – edit & display geojson with leaflet & leaflet-draw 
  - [data-field-image](http://github.com/editdata/data-field-image) – edit & display images
  - [data-field-list](http://github.com/editdata/data-field-list) – edit & display lists, both arrays & key/value lists
  - [data-field-string](http://github.com/editdata/data-field-string) – edit & display strings
  - [data-field-url](http://github.com/editdata/data-field-url) – edit & display URLs
- _more soon!_

## Tools
- [editdata.org](http://editdata.org) – edit data & save it to GitHub
- [editdata](https://github.com/editdata/editdata) – desktop app for editing data

## See also

There are a number of existing projects related to editing JSON & tabular data.

We're documenting those projects & approaches in the [resources.md](resources.md) file, and contributions are welcome!

## Contributing

This project is as much about design & documentation as it is about code, and we are actively seeking contributions!

Read the [contributing guidelines for details](CONTRIBUTING.md).

## License

Code is licensed as [MIT](LICENSE.md), content is licensed as [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
