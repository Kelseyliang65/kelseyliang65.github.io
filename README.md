# Yifei Liang — Academic Homepage

Academic homepage of Yifei Liang, a Ph.D. student at Sun Yat-sen University and Shenzhen Loop Area Institute.

Website: https://kelseyliang65.github.io/

## Updating the site

- `_config.yml`: name, affiliation, email, profile photo, and external links.
- `index.md`: biography, research interests, education, and awards.
- `_data/publications.yml`: research titles, collaborators, status, descriptions, and optional paper links.
- `assets/img/`: profile photo and research images.

GitHub Pages builds and publishes the site from the root of the `main` branch after each push. Photos and paper links will be added later. Original CV files and personal phone numbers are not included.

## Local preview

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve --host 127.0.0.1
```

Open http://127.0.0.1:4000/.

## Theme credit

Based on [Minimal Light](https://github.com/yaoyao-liu/minimal-light) by Yaoyao Liu, released under CC0 1.0. The original license is retained in `LICENSE`.
