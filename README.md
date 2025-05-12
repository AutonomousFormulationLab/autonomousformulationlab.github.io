# Autonomous Formulation Laboratory Website

This repository contains the GitHub Pages website for the Autonomous Formulation Laboratory, providing comprehensive information about our mission, offerings, and links to our various repositories and projects.

## About the AFL

The AFL is a multi-facility collaborative project that originated at the National Institute of Standards and Technology (NIST), US Department of Commerce, and has since expanded to include partnerships with companies, academic laboratories, and facilities worldwide. The AFL aims to provide open-source hardware, control software, and AI algorithms to accelerate materials optimization and discovery.

## Website Structure

- `index.html` - Main page with comprehensive information about the AFL
- `styles.css` - Modern, responsive styling for the website
- `images/` - Directory containing website images

## Content Sections

The website includes the following sections:

1. **About the AFL** - Introduction to the laboratory and its origin
2. **Our Mission** - The AFL's objectives and focus areas
3. **What We Offer** - Overview of hardware, software, and AI algorithms
4. **Program Overview** - Detailed information about the program's structure and goals
5. **Key Milestones** - Achievements and progress highlights
6. **How to Get Involved** - Ways for the community to participate
7. **Resources** - Links to documentation, publications, and community forums
8. **Our Repositories** - Links to all AFL GitHub repositories

## Local Development

To test this website locally, you can use Python's built-in HTTP server:

```bash
python -m http.server
```

Then visit `http://localhost:8000` in your browser.

## Deployment

This website is automatically deployed to GitHub Pages. Any changes pushed to the main branch will be reflected on the live site.

## Adding New Repositories

To add new repositories to the list, edit the repository list section in `index.html` and add a new list item following the existing format:

```html
<li><a href="https://github.com/AutonomousFormulationLab/repo-name" target="_blank">Repo-name</a> - Description of the repository</li>
```

## Modifying Content

The website is structured with clear section divisions in the HTML. To update content:

1. Locate the appropriate section in `index.html`
2. Make your desired changes while maintaining the HTML structure
3. If adding new sections, follow the existing pattern and add appropriate styling in `styles.css`

## Contact

If you are interested in replicating the AFL or using it at the NCNR, please reach out to Dr. Peter Beaucage or Dr. Tyler Martin.
