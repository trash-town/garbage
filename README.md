# possum
**P**ublishing **O**ur **S**ite by **S**lurping **U**p **M**arkdown
possum is a bespoke site generator for trash.town

## spec
the goal is to read a tree of markdown files and use jinja2 templates to easily create our webpage

### markdown specs
md files will have a heading space delimited by a line of `+++++`
this heading space will contain values that the generator will read and apply properly, these will be structured as `key: value` each on their own line

keys that should exist at launch:

- title: html title for the doc
- template: jinja2 template name that will be in the root templates dir to apply to the page
