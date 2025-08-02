# Carnexa Coming Soon Page

A modern, responsive coming soon page for Carnexa - The Ultimate Auto Platform.

## 🚗 Features

- **Dark Theme Design** with modern gradients
- **Responsive Layout** that works on all devices
- **Animated Elements** with smooth transitions
- **Email Signup Form** for visitor notifications
- **Professional Branding** with Carnexa logo
- **Single Screen Experience** - no scrolling required

## 🚀 Deploy to GitHub Pages

### Option 1: Static Site Deployment (Recommended)

1. **Push to GitHub**: Upload this project to a GitHub repository
2. **Enable GitHub Pages**: 
   - Go to your repository Settings
   - Navigate to Pages section
   - Set Source to "GitHub Actions"
3. **Automatic Deployment**: The GitHub Actions workflow will automatically deploy your site when you push to the main branch

### Option 2: Manual Deployment

1. **Copy static files**:
   - Copy the contents of the `static/` folder to your GitHub Pages branch
   - Or use the GitHub Actions workflow provided

## 🛠️ Local Development

### For Static Version (Recommended for GitHub Pages):
1. **Open the static folder**:
   ```bash
   cd static
   ```
2. **Open index.html** in your browser or use a local server

### For Blazor Version (Local development):
1. **Navigate to the project**:
   ```bash
   cd comingsoonpage/comingsoonpage
   ```
2. **Run the application**:
   ```bash
   dotnet run
   ```
3. **Open in browser**: http://localhost:5042

## 📁 Project Structure

```
comingsoonpage/
├── static/                          # Static version for GitHub Pages
│   ├── index.html                   # Main HTML file
│   ├── styles.css                   # All CSS styles
│   ├── logo.png                     # Carnexa logo
│   └── favicon.png                  # Site favicon
├── comingsoonpage/                  # Blazor version (for local development)
│   ├── Components/
│   │   ├── Pages/
│   │   │   └── Home.razor          # Main coming soon page
│   │   └── Layout/
│   │       ├── MainLayout.razor    # Layout component
│   │       └── NavMenu.razor       # Navigation menu
│   ├── wwwroot/
│   │   ├── app.css                 # Main styles
│   │   ├── bootstrap/              # Bootstrap CSS
│   │   │   └── logo.png           # Carnexa logo
│   │   └── favicon.png            # Site favicon
│   └── Program.cs                  # Application entry point
└── .github/
    └── workflows/
        ├── deploy.yml              # Blazor deployment (complex)
        └── deploy-static.yml       # Static deployment (simple)
```

## 🎨 Customization

### Colors
The site uses a dark theme with:
- **Primary Background**: `#1a1a2e` → `#16213e` → `#0f3460`
- **Accent Color**: `#00d4ff` (Cyan)
- **Text Colors**: White and light grays

### Logo
Replace `static/logo.png` with your own logo.

### Content
Edit `static/index.html` to modify:
- Company name and tagline
- Description text
- Launch date
- Feature icons and text

## 🌐 Live Demo

Once deployed, your site will be available at:
`https://[your-username].github.io/[repository-name]/`

## 📱 Responsive Design

The page is fully responsive and optimized for:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (320px - 767px)

## 🔧 Technologies Used

- **HTML5** with semantic markup
- **CSS3** with modern features (Grid, Flexbox, Animations)
- **JavaScript** for interactive elements
- **Bootstrap 5** (CDN) for responsive design
- **GitHub Actions** for automated deployment

## 🚨 Important Notes

- **Use the `static/` folder** for GitHub Pages deployment
- **The Blazor version** is for local development only
- **Static version** has all the same features but works perfectly on GitHub Pages
- **No build process required** for the static version

## 📄 License

This project is created for Carnexa. All rights reserved. 