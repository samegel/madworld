# Maximizing Reuse Within Flare
## Mathew Ellison
## 4/3/2017

## Intro
- Recommends paragraph level snippets
- translation hard for smaller snippets

## Focus on Snippets and Variables
* "placeholder"
* variables vs snippets, plain text vs xhtml
* block level snippets (snippetBlock) must be in empty paragraph
* Pin snippets in CTRL+R dialog
* *Use snippets as a template for complicated elements, like tables. Insert snippet > convert to text.*

### Sharing Snippets and Stuff
* Nomenclature: stuff possible to include: author, warning, etc
* project "import file" (.flimpfl) controls shared variables
* Use "global project" for reusing snippets between projects. Global project snippets ripple into other projects
* Global project linking should be one way - global to child project. Authors can choose not to update imported snippets,
but they cannot edit the global project snippet.
* Some two way linking exits, but not the best

### Variable reuse
* reuse one variable in multiple targets, but specify which variable definition gets output in which target - in the target.
* You can change which def of a variable is used w/in a snippet, so multiple definitions of a variable can be used w/in
a target

Email Ellison for example project
