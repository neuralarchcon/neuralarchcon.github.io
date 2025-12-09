# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is the website for the NeurArchCon COST Action CA18106 (Neural Architectures of Consciousness), built with Jekyll and the Helium Bootstrap 4 theme. The site is hosted on GitHub Pages at neuralarchcon.github.io.

## Development Commands

### Running Jekyll locally
```bash
bundle exec jekyll serve
```
The site will be available at http://localhost:4000

### Building the site
```bash
bundle exec jekyll build
```

### Installing dependencies
```bash
bundle install
```

## Architecture and Structure

### Jekyll Configuration
- Main config: `_config.yml`
- Base URL: configured for GitHub Pages deployment
- Theme: Helium Bootstrap 4 (heavily customized)
- Markdown processor: kramdown
- Excerpt separator: `<!--more-->`

### Layout System
The site uses a hierarchical layout structure:
- **`_layouts/`**: Top-level layout wrappers
  - `main-index.html`: Homepage layout
  - `index.html`: Standard page layout
  - `blog.html`: Blog post listing
  - `dataset.html`: Dataset detail pages
  - `default.html`: Base layout with Bootstrap theme
  - `post.html`: Individual blog post
  - `page.html`: General purpose page

- **`_includes/themes/bootstrap/`**: Theme-specific components
  - `main-nav-bar.html`: Main navigation
  - `footer.html`: Site footer
  - Layout-specific includes referenced by `_layouts/`

### Content Types

#### Posts (`_posts/`)
Organized by category with date-based naming:
- `news/`: News updates and announcements
- `lessons/`: Tutorial/educational content
- `docs/`: Documentation pages

#### Datasets Collection (`_datasets/`)
Datasets are managed as a Jekyll collection (not posts):
- **Location**: `_datasets/` directory
- **Filename format**: `dataset-name.md` (NO date prefix required)
- **Layout**: `dataset`
- **Required front matter**:
  - `modality`: Array of modalities (e.g., `["eye-tracking"]`)
  - `participants`: Number of participants
  - `site`: Array of collection sites (e.g., `["Krakow"]`)
  - `authors`: Array of author names
  - `contact`: Array of contact names
  - `email`: Array of contact emails
  - `ratings`: Boolean
  - `summary`: Brief description
  - `citation`: Publication citation (optional)
  - `doi`: DOI link (optional)

#### People Pages
Located in `people/` directory (e.g., `people/ksandberg.html`)
- Team member profiles
- Working group leaders
- Action chairs

### Key Pages

- **`index.html`**: Main homepage
- **`datasets.html`**: Dataset listing with filtering functionality
- **`people.html`**: Team member directory
- **`blog.html`**: News and updates listing
- **`about.html`**: About the project
- **`publications.html`**: Research publications

### Dataset Filtering System

The datasets.html page implements client-side filtering:
- **Text search**: Searches dataset titles
- **Participant slider**: Filters by minimum number of participants
- **Site checkboxes**: Filters by collection site (Aarhus, Brno, Krakow)
- Filtering logic is in inline `<script>` tag within `datasets.html`
- Key functions: `findTextInTitle()`, `checkParticipants()`, `checkSite()`, `decideVisibility()`

### Custom Includes

- **`side-bar.html`**: Sidebar for dataset/blog pages
- **`about-bar.html`**: About section sidebar
- **`social-block.html`**: Social media links
- **`ads-block.html`**: Ad placement (Google AdSense configured)

### Theme Configuration

Jekyll-Bootstrap (JB) settings in `_config.yml`:
- Analytics: Google Analytics configured
- Comments: Disqus integration available
- Asset path: `/assets`
- Theme paths for archives, tags, categories

## Assets Organization

- **`assets/images/`**: Images including team photos, dataset figures, sliders
- **`assets/js/`**: JavaScript libraries
  - Bootstrap, jQuery, Owl Carousel (for post carousel)
  - Custom scripts: `sliders.js`, `main.js`, `portfolio.js`
- **`assets/css/`**: Stylesheets (not detailed in this analysis)

## Important Notes

- Site uses Jekyll-Bootstrap helper includes via `{% include JB/setup %}`
- BASE_PATH variable is used throughout for proper URL generation
- Bootstrap 4 components are available sitewide
- The site includes Font Awesome icons
- Responsive design with mobile-optimized layouts

## Content Guidelines

### Adding a New Dataset
1. Create markdown file in `_datasets/` with format: `dataset-name.md` (no date prefix needed)
2. Set layout to `dataset`
3. Include all required front matter fields (modality, participants, site, authors, etc.)
4. Add dataset image to `assets/images/datasets/`
5. Use `{{ BASE_PATH }}` when referencing images
6. Dataset will automatically appear at `/datasets/dataset-name/`

### Adding News/Blog Posts
1. Create markdown file in `_posts/news/` with date-based naming
2. Front matter should include: title, tagline, author, img (optional)
3. Posts automatically appear in blog listing and carousel

### Adding Team Members
1. Add profile image to `assets/images/people/`
2. Create HTML file in `people/` directory
3. Update `people.html` to include team member card
