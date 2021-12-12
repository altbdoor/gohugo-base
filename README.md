# gohugo-base

Personal base directory structure for Hugo.

1. Create a Markdown file inside `content`, with `pagename.md`.
1. Set the front matter with `type` and `layout` in `content/pagename.md`.
    -   ```md
        ---
        type: page
        layout: pagename
        ---
        ```

1. Inside `layouts/page`, create the `pagename.html`.
1. Do whatever that is necessary in `layouts/page/pagename.html`.

The empty Markdown file in `content` is necessary to tell Hugo that there is a page to be rendered. Hugo will then take the layout from `layouts/page` folder, and render.
