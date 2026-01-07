# Quarto Porting Checklist (Wowchemy -> Quarto)

- [ ] Replace Wowchemy home widgets from `content/home/` with Quarto homepage sections (About, Experience, Skills, Projects, Publications, Talks, Posts, Contact, etc.).
- [ ] Recreate the Hero/Slider sections from `content/home/hero.md` and `content/home/slider.md` (likely custom HTML/CSS or a Quarto include).
- [ ] Port the People widget (`content/home/people.md`) to a Quarto listing or a custom data-driven section.
- [ ] Migrate the Publications widget and BibTeX-driven entries from `content/publication/**/` into Quarto citations or a publications page.
- [ ] Migrate Talks from `content/talk/**/` into a Quarto listing page.
- [ ] Migrate Posts from `content/post/` into a Quarto blog or listing page.
- [ ] Recreate Tags/Featured widgets (`content/home/tags.md`, `content/home/featured.md`) with Quarto listings or filters.
- [ ] Port the Contact widget settings (address, form, map) to Quarto equivalents or embeds.
- [ ] Move assets from `static/` and `assets/` to Quarto `static/` or `resources/` equivalents as needed.
- [ ] Recreate menus and navigation from `config/_default/menus.toml` in `_quarto.yml`.
- [ ] Replace any Wowchemy shortcodes (none active found yet; re-check after content migration).
