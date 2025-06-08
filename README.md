# Pramis Subedi's Blog

A personal blog built with Jekyll, featuring a clean black and white design with dark/light theme switching.

## Features

- **Theme Toggle** - Switch between light and dark modes with preference persistence
- **Responsive Design** - Optimized for all device sizes
- **Clean Typography** - Focused on readability and content
- **Syntax Highlighting** - Code blocks with theme-aware highlighting
- **Archive Page** - Organized post listing by year
- **Fast Loading** - Optimized for performance

## Built With

- [Jekyll](https://jekyllrb.com/) - Static site generator
- [SCSS](https://sass-lang.com/) - CSS preprocessing
- [GitHub Pages](https://pages.github.com/) - Hosting
- Based on the [Hitchens theme](https://github.com/patdryburgh/hitchens) by Pat Dryburgh

## Local Development

To run this blog locally:

```bash
# Clone the repository
git clone https://github.com/pramissubedi/pramissubedi.github.io.git
cd pramissubedi.github.io

# Install dependencies
bundle install

# Serve the site locally
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`.

## Writing Posts

Create new posts in the `_posts` directory with the format:

```
YYYY-MM-DD-title-of-post.md
```

Include front matter at the top:

```yaml
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD HH:MM:SS -0000
categories: [category1, category2]
excerpt: "A brief description of your post."
---
```

## Customization

### Colors

Theme colors are defined in `_sass/_variables.scss`. The site uses CSS custom properties for theme switching.

### Navigation

Update the navigation menu by editing `_data/menu.yml`.

### Site Configuration

Modify `_config.yml` to update site title, description, and other settings.

## License

The code for this blog is available under the [MIT License](LICENSE.txt).

The EB Garamond font is licensed under the [SIL Open Font License](assets/fonts/OFL.txt).

---

Built with ❤️ and lots of coffee ☕
