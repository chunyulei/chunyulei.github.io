# Chunyu Lei's Homepage

This is the source code for [Chunyu Lei](https://chunyulei.github.io)'s personal academic website, hosted on GitHub Pages at [chunyulei.github.io](https://chunyulei.github.io).

## About the Owner

**Chunyu Lei (雷春雨)** is a Ph.D. candidate in Computer Science and Technology at South China University of Technology (SCUT), co-supervised by Prof. [C. L. Philip Chen](https://www2.scut.edu.cn/cs/2024/0619/c22284a557049/page.htm) (Member of Academia Europaea, IEEE Fellow) and Prof. [Tong Zhang](https://www2.scut.edu.cn/cs/2021/0317/c22284a422099/page.htm) (National Outstanding Young Scientist). His research interests include:

- Continual Learning
- Foundation Models
- Affective Computing
- Broad Learning Systems
- Neural Architecture Search

## Features

- **Markdown-driven content** — Write content in Markdown files; no build or compilation step required.
- **LaTeX math support** — Inline math with `$...$` or `\(...\)`, display math with `$$...$$` or `\[...\]`, plus macros like `\ref{}`, `\eqref{}`, and `\begin{equation}`.
- **Responsive design** — Built on Bootstrap 5, mobile-friendly out of the box.
- **Zero server dependency** — Fully static; deploy to GitHub Pages, Netlify, or any static file server.

## Directory Structure

```
.
├── contents/
│   ├── config.yml        # Site configuration (title, subtitle, copyright)
│   ├── home.md           # Biography, contact, education, experience, services
│   ├── publications.md   # Published & submitted papers
│   ├── fundings.md       # Research funding
│   └── awards.md         # Awards & honors
├── static/
│   ├── assets/
│   │   ├── favicon.ico
│   │   ├── photo.jpg     # Avatar photo
│   │   └── background.jpeg  # Top section background
│   ├── css/
│   │   ├── styles.css    # Bootstrap + Base styles
│   │   └── main.css      # Custom styles
│   └── js/
│       ├── scripts.js          # Core logic (YAML + Markdown loading)
│       ├── marked.min.js       # Markdown parser
│       ├── js-yaml.min.js      # YAML parser
│       └── bootstrap.bundle.min.js  # Bootstrap
├── index.html            # Entry point
├── LICENSE               # MIT License
└── README.md
```

## Getting Started (as a template)

This site can be used as a template for your own academic homepage.

### 1. Fork the repository

Create a repository named `<username>.github.io` (this will be your website URL).

### 2. Clone and customize

```
git clone https://github.com/<username>/<username>.github.io.git
```

Edit the following files to personalize your site:

| File | Purpose |
|------|---------|
| `contents/config.yml` | Site title, navigation text, copyright |
| `contents/home.md` | Your biography, contact, education, etc. |
| `contents/publications.md` | Publication list |
| `contents/fundings.md` | Research funding information |
| `contents/awards.md` | Awards and honors |
| `static/assets/photo.jpg` | Your avatar photo |
| `static/assets/background.jpeg` | Hero section background image |

### 3. Deploy to GitHub Pages

1. Go to your repository **Settings** → **Pages**.
2. Under **Source**, select **Deploy from a branch**.
3. Choose the `main` (or `master`) branch and root folder.
4. Your site will be live at `https://<username>.github.io`.

> Changes may take up to 10 minutes to publish after pushing.

## Technical Details

- **Markdown rendering** — [marked.js](https://marked.js.org/) parses `.md` files client-side.
- **YAML config** — [js-yaml](https://github.com/nodeca/js-yaml) loads `config.yml` for dynamic page text.
- **Math typesetting** — [MathJax 3](https://docs.mathjax.org/en/latest/index.html) renders LaTeX formulas with SVG output.
- **Layout** — [Bootstrap 5](https://getbootstrap.com/) via [Start Bootstrap - New Age](https://github.com/StartBootstrap/startbootstrap-new-age) theme.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Copyright © 2023–2026 Sen Li (original template). Content and modifications © Chunyu Lei 2025–2026.
