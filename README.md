# Temporary back up page for New Inquiry

This is using [Github Pages]() and [Jekyll]().

The essays were copied over from the WordPress admin dashboard, which is still accessible. Unfortunately, I couldn't figure out how to make images work, so the images have been deleted.

The redirection is happening on the WordPress server in `.htaccess`. It redirects everything but admin and login to the Github Pages for this account.

## Changing content

You can edit the text on the homepage by editing `index.md`. That file is in [Markdown]() format.

`nyt` is just literally copied from the nyt repo (twice).

The different sections (features, essays, etc) are all Jekyll collections. You can edit them or add new ones in `_config.yml`.

Each collection has a directory like `_features` or `_blogs-marginal-utility`. Each file in that directory is a post.

I already added the 3 newest features, the 3 newest essays, and the 3 newest blog entries. I had to add paragraph breaks and remove the images.

I tried to mirror the paths of the WordPress site so links still work.

## Making it look nicer

The overall layouts are in `_layouts`: `index.html` for the index page and 404 page and `posts.html` for all the different kinds of posts.

The layouts include other bits of html from the `_includes` directory: `header.html`, `footer.html`, `recent.html` (described above), and `linkassets.html` (the references to the stylesheets).
