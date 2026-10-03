# Zamonaviy Iqtisodiyot — WordPress theme

**Custom WordPress theme for the *Zamonaviy Iqtisodiyot* scientific journal portal** ([zamonaviyiqtisodiyot.uz](https://zamonaviyiqtisodiyot.uz)): publishing economics articles, author submissions, saved articles and search — in Uzbek.

![WordPress 6](https://img.shields.io/badge/WordPress%206-21759B?logo=wordpress&logoColor=white) ![PHP 8](https://img.shields.io/badge/PHP%208-777BB4?logo=php&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=white) ![License GPL-2.0](https://img.shields.io/badge/License%20GPL--2.0-blue)

## Features

- Custom post type for articles with an archive and a single-article layout
- **Article submission** page for authors (`page-maqola-yuborish.php`)
- **Saved articles** for readers (`page-saqlangan.php`)
- Search results, About and Contact pages, custom 404
- Responsive layout, light JavaScript (`main.js`)

## Structure

| File | Purpose |
|---|---|
| `style.css` | theme header and styles |
| `functions.php` | post types, assets, theme supports |
| `header.php`, `footer.php` | layout |
| `index.php`, `archive-maqola.php`, `single-maqola.php` | listings and article page |
| `page-*.php` | submission, saved, about, contact pages |
| `search.php`, `404.php` | search and not-found |

## Installation

1. Copy the folder to `wp-content/themes/zamonaviy-iqtisodiyot`.
2. Activate **Zamonaviy Iqtisodiyot** in *Appearance → Themes* (WordPress 6.0+, PHP 8.0+).
3. Create the pages *Maqola yuborish*, *Saqlangan*, *Biz haqimizda*, *Aloqa* — the templates attach by slug.

## Author

Built by **Bluecore Dev** — IT agency · Omonjon, full-stack developer (4+ years)

[+998 91 911 99 88](tel:+998919119988) · [socialmarketing.uz](https://socialmarketing.uz) · Telegram [@anvarov_911](https://t.me/anvarov_911) · [anvarov1170@gmail.com](mailto:anvarov1170@gmail.com)
