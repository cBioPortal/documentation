This documentation site is built using a site generator called [Retype](https://retype.com) (similar to Gitbook) which generates a searchable site from markdown files.

It is hosted using github pages (configured in settings of repository) and will regenerate upon update to master branch.

To edit and run the documentation site locally: 

1. [Install Retype using these instructions](https://retype.com/#quick-start)
2. Boot up dev instance using this command: ```retype watch .```
3. Edit markdown files (*.md) or add new ones (see Retype documentation for formatting help)
4. Open a Github PR to master branch of this repository

The navigation of the site is specified in ```/src/SUMMARY.md```.  Any new files need to be added to this list in order
to appear in site navigation. 

