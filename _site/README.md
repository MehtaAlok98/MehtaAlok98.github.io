# My Jekyll Website

This is a personal blog and website built with Jekyll and hosted on GitHub Pages.

## Project Structure

```plaintext
.
├── _config.yml          # Jekyll configuration file
├── about.md             # About page
├── articles.md          # Articles page
├── contact.md           # Contact page
├── index.md             # Home page
├── posts.md             # Blog posts page
├── _layouts/            # Layout templates
│   ├── default.html     # Default layout
│   └── post.html        # Layout for individual blog posts
├── _posts/              # Blog post files
│   ├── 2024-09-15-first-post.md    # First blog post
│   └── 2024-09-16-second-post.md   # Second blog post
├── _includes/           # Reusable components (e.g., navbar)
│   └── navbar.html      # Navbar partial
├── _sass/               # Sass partials for styling
│   ├── _variables.scss  # Variables for consistent design
│   └── _navbar.scss     # Styles for the navbar
├── _data/               # Structured data files
│   └── navigation.yml   # Data for the navigation bar
└── _site/               # Auto-generated directory (don't edit)
```

## Features

- **Blog:** A blog section powered by Markdown and Jekyll's post functionality.
- **Responsive Design:** Uses Sass for styling, making it easy to extend and manage styles.
- **Reusable Components:** Navbar and other elements are stored in `_includes` for reuse across pages.
- **Dynamic Navigation:** The navigation bar is generated from a data file (`_data/navigation.yml`).

## How to Use

1. **Install Jekyll**:
   If you don't have Jekyll installed, run:
   ```bash
   gem install bundler jekyll
   ```

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

3. **Run the Project Locally**:
   Start the Jekyll server:
   ```bash
   bundle exec jekyll serve
   ```
   Open [http://localhost:4000](http://localhost:4000) in your browser.

4. **Deploy to GitHub Pages**:
   Just push your changes to the `main` or `gh-pages` branch, and GitHub Pages will automatically deploy the site.

## Customization

- **Layouts:** Customize the `_layouts/default.html` or `_layouts/post.html` to change the page structure.
- **Sass:** Edit the files in `_sass/` for styles and variables.
- **Navigation:** Modify `_data/navigation.yml` to change the navigation links.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

### Summary:
- **`_sass/`** is used for organizing Sass styles, and you should import Sass partials into a main stylesheet and link it in your layout.
- **`_data/`** is for structured data that can be used in templates, like navigation menus, and you can access this data in your layouts using Liquid.

This `README.md` will help guide anyone using your project on how to install, customize, and contribute to it.