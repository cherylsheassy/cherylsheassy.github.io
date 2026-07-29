# Personal website

This is a small personal website built from the [al-folio](https://github.com/alshedivat/al-folio) Jekyll starter.

## First edits

1. Update your name, description, keywords, and final published address in `_config.yml`.
2. Replace the placeholder biography and work items in `_pages/about.md`.
3. Add your email and professional links in `_data/socials.yml`.
4. Optional: put a square headshot in `assets/img/`, then add the `profile` block from the al-folio documentation to `_pages/about.md`.
5. Optional: put your PDF CV in `assets/pdf/cv.pdf`, then uncomment `cv_pdf` in `_data/socials.yml` and add a CV page.

## Local preview

This site requires a modern Ruby installation (Ruby 3.1+; Ruby 3.3+ is a good choice) and the Bundler version in `Gemfile.lock`.

```bash
bundle install
bundle exec jekyll serve --livereload
```

Open the local address printed by Jekyll, usually `http://127.0.0.1:4000/`.

## Publishing

Create a new GitHub repository from this folder—do not fork the al-folio repository. For the cleanest address, name it `YOUR-USERNAME.github.io`, then enable GitHub Pages in the repository settings. Set `url` in `_config.yml` to the final `https://YOUR-USERNAME.github.io` address before publishing.
