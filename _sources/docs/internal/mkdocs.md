## MKDocs

MkDocs is a tool for project documentation using markdown. For our purpose, it is especially useful since it integrates notebooks, looks nice online, is easy to customize to our needs, generates code-documentation and is easily integrated with github pages.

You can perfectly well do a lot of work without ever touching mkdocs (we can embed notebooks directly in this environment), but feel free to experiment.

It is installed by running

```pip install mkdocs-material```

## Editing the webpages

The content files of the webpages are located in the ```docs```-subdirectory, and are in either .md (markdown) or .ipynb (notebook) syntax.

Which files to include and the configuration of the pages are done in the ```mkdocs.yml``` file in the root folder of the repository.

### Testing locally

When you have made edits, you can test the result locally by running

```mkdocs serve```

...and open the provided IP-adress.

### Updating the github-pages online

If you are satisfied with your edits, update the remote pages (online) by running

```mkdocs gh-deploy```

## More information

MKDocs has a great <a href="https://squidfunk.github.io/mkdocs-material/getting-started/">getting started</a> online if you want to learn more.

