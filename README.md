# Agency Website

A professional website built using the Tabler template framework to showcase Agency projects with a web-agency style approach.

## Project Overview

This website serves as a showcase for Agency open source projects. It is built using the Tabler template framework, which is based on Bootstrap 5 and provides a responsive and modern UI. The website presents rabbitOS as an AI-native operating system designed to revolutionize human-machine interaction.

## Features

- **Responsive Design**: Fully responsive layout that works on mobile, tablet, and desktop devices
- **Modern UI**: Clean and professional design based on the Tabler framework
- **Dynamic Content**: Project data loaded dynamically from JSON files
- **Interactive Elements**: Search functionality, filtering, and smooth animations
- **SEO Optimized**: Meta tags and semantic HTML for better search engine visibility
- **Cross-Browser Compatible**: Works on all modern browsers
- **Contact Forms**: Integrated contact forms on multiple pages
- **Optimized Assets**: Compressed images and efficient code for fast loading

## Technologies Used

- **Tabler**: UI framework based on Bootstrap 5
- **Bootstrap 5**: CSS framework for responsive design
- **HTML5**: Semantic markup for better accessibility and SEO
- **CSS3**: Custom styling with modern CSS features
- **JavaScript**: Interactive elements and dynamic content loading
- **JSON**: Data storage for project information
- **Font Icons**: Tabler Icons for scalable vector icons

## Project Structure

```
agency-website/
├── assets/
│   ├── css/                     # CSS files including Tabler and custom styles
│   │   └── custom.css           # Custom CSS overrides and additions
│   ├── js/                      # JavaScript files
│   │   └── custom.js            # Custom JavaScript for interactive elements
│   ├── img/                     # Images for the website
│   │   ├── hero/                # Hero section images
│   │   ├── projects/            # Project screenshots and images
│   │   ├── products/            # Product images
│   │   ├── team/                # Team member photos
│   │   └── logo/                # Logo files and favicon
│   └── fonts/                   # Font files if needed
├── pages/                       # Individual page content
│   ├── about.html               # Chi siamo (About Us) page
│   ├── services.html            # Servizi (Services) page
│   ├── current-projects.html    # Progetti in corso (Current Projects) page
│   └── portfolio.html           # Portfolio page
├── data/                        # JSON data files for projects
│   ├── current-projects.json    # Data for current projects
│   └── portfolio-projects.json  # Data for completed projects
├── index.html                   # Home page
├── README.md                    # Project documentation for GitHub
└── .gitignore                   # Git ignore file
```

## Installation and Setup

### Prerequisites

- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript (for development)
- Git (for version control)

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/agency-website.git
   cd agency-website
   ```

2. Open `index.html` in your browser to view the website locally.

3. Make changes to the HTML, CSS, or JavaScript files as needed.

4. Refresh your browser to see the changes.

### Deployment

1. Push your changes to GitHub:
   ```bash
   git add .
   git commit -m "Your commit message"
   git push origin main
   ```

2. Deploy to your web hosting service:
   - Upload all files to your web server via FTP
   - Or set up GitHub Pages to automatically deploy from your repository
   - Or use a CI/CD pipeline for automated deployment

## Usage Guidelines

### Adding New Projects

1. Add project data to the appropriate JSON file in the `data/` directory:
   - For current projects: `data/current-projects.json`
   - For completed projects: `data/portfolio-projects.json`

2. Add project images to the `assets/img/projects/` directory.

3. The website will automatically load and display the new projects.

### Modifying Content

- **Pages**: Edit the HTML files in the root directory and `pages/` folder
- **Styles**: Modify `assets/css/custom.css` for styling changes
- **Scripts**: Update `assets/js/custom.js` for JavaScript functionality
- **Images**: Add or replace images in the `assets/img/` directory

### Browser Compatibility

The website is compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Maintenance

Regular maintenance tasks include:

1. Updating project information in the JSON files
2. Adding new team members or services as needed
3. Checking for broken links and fixing them
4. Optimizing new images before adding them to the site
5. Keeping dependencies updated (Tabler, Bootstrap, etc.)

## Credits and Acknowledgments

- [Tabler](https://tabler.io/) - UI framework
- [Bootstrap](https://getbootstrap.com/) - CSS framework
- [Tabler Icons](https://tabler-icons.io/) - Icon set
- [DoDa Agency Team](https://github.com/doda-agency) - Content and concept

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

For questions or support, please contact the DoDa Agency Team via GitHub or through the contact form on the website.