This site is built as a Jekyll site, with a Vue.js instance powering the instrument finder. It has Jekyll as a dependency.

# First time setup

If you alraedy have Jekyll installed, you're good to go. Else, [refer to their installation guide](https://jekyllrb.com/docs/installation/)

# Running a development server

```
jekyll serve --watch
```

This will serve the site at localhost:4000, and recompile your site when you make changes. 

# An overview of the files

- `/_includes` - Contains reusable HTML blocks, currently only used for the header and footer.
- `/_layouts` - Contains the HTML for each page - all of the pages inherit from default.html, which contains the barebones page setup.
- `/assets` - Contains static files - currently just stylesheets
- `/docs` - Don't touch this as it contains the generated site.
- `framework.md` - This is the only markdown file with content. The YAML frontmatter generates the table of contents, and the markdown generates the actual framework content. 
