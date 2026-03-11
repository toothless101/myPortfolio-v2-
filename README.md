# My Portfolio Website

A simple and clean personal portfolio website built with Vite and Tailwind CSS. This project showcases my information as a Web Developer, including my contact details and an option to download my CV.

## Features

- **Personal Information Display** - Shows name, profile photo, location, and profession
- **Download CV** - Button to download resume/CV in PDF format
- **Send Email** - Button to quickly send an email
- **Responsive Design** - Works on both mobile and desktop devices
- **Clean UI** - Modern and minimal design using Tailwind CSS

## Technologies Used

- **Vite** - Fast build tool and development server
- **Tailwind CSS v4** - Utility-first CSS framework
- **HTML5** - Semantic markup
- **Font Awesome** - Icons
- **Google Fonts** - Poppins font family

## Project Structure

```
vite-project/
├── index.html          # Main HTML file
├── package.json        # Project dependencies
├── vite.config.js      # Vite configuration
├── public/             # Static assets
│   └── vite.svg
└── src/
    ├── main.js         # Entry point JavaScript
    ├── style.css       # Tailwind CSS styles
    ├── counter.js     # Default Vite counter (can be removed)
    ├── javascript.svg  # Default Vite asset (can be removed)
    └── imgs/
        ├── img1.jpg            # Profile photo
        ├── copeh.JPG          # Favicon
        ├── location.png       # Location icon
        └── Updated Resume.pdf # Resume/CV file
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd vite-project
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

### Development

Run the development server:

```bash
npm run dev
```

Open your browser and visit `http://localhost:5173` to see the website.

### Build for Production

To create a production build:

```bash
npm run build
```

The built files will be in the `dist` folder.

### Preview Production Build

To preview the production build locally:

```bash
npm run preview
```

## Customization

### Updating Personal Information

Edit `index.html` to update:
- Name: Line 19
- Location: Line 23
- Profession: Line 26
- Email address: Line 34
- CV/Resume link: Line 30

### Changing Profile Photo

Replace `src/imgs/img1.jpg` with your own photo (recommended size: 160x160 pixels).

### Updating CV/Resume

Replace `src/imgs/Updated Resume.pdf` with your own resume file.

### Changing Colors/Styles

Edit `src/style.css` to customize:
- Colors (defined in `:root`)
- Font family
- Custom utility classes

## Deployment

### GitHub Pages

1. Build the project:
   ```bash
   npm run build
   ```

2. Deploy the `dist` folder to GitHub Pages

### Netlify / Vercel

1. Connect your GitHub repository to Netlify or Vercel
2. The platform will automatically detect Vite and configure the build settings
3. Deploy!

## License

This project is for personal use. Feel free to use it as a template for your own portfolio.

## Author

**Hilary Poralan**
- Location: Tagum City, Philippines
- Profession: Web Developer
- Email: poralanhilarymae@gmail.com

## Acknowledgments

- [Vite](https://vitejs.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Font Awesome](https://fontawesome.com/)
- [Google Fonts](https://fonts.google.com/)
