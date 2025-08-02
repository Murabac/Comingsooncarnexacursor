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

### Option 1: Automatic Deployment (Recommended)

1. **Push to GitHub**: Upload this project to a GitHub repository
2. **Enable GitHub Pages**: 
   - Go to your repository Settings
   - Navigate to Pages section
   - Set Source to "GitHub Actions"
3. **Automatic Deployment**: The GitHub Actions workflow will automatically build and deploy your site when you push to the main branch

### Option 2: Manual Deployment

1. **Build the project**:
   ```bash
   cd comingsoonpage/comingsoonpage
   dotnet publish -c Release -o ./publish
   ```

2. **Upload to GitHub Pages**:
   - Copy the contents of `publish/wwwroot/` to your GitHub Pages branch
   - Or use the GitHub Actions workflow provided

## 🛠️ Local Development

1. **Clone the repository**
2. **Navigate to the project**:
   ```bash
   cd comingsoonpage/comingsoonpage
   ```
3. **Run the application**:
   ```bash
   dotnet run
   ```
4. **Open in browser**: http://localhost:5042

## 📁 Project Structure

```
comingsoonpage/
├── comingsoonpage/
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
        └── deploy.yml              # GitHub Actions deployment
```

## 🎨 Customization

### Colors
The site uses a dark theme with:
- **Primary Background**: `#1a1a2e` → `#16213e` → `#0f3460`
- **Accent Color**: `#00d4ff` (Cyan)
- **Text Colors**: White and light grays

### Logo
Replace `wwwroot/bootstrap/logo.png` with your own logo.

### Content
Edit `Components/Pages/Home.razor` to modify:
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

- **Blazor WebAssembly** (.NET 8.0)
- **Bootstrap 5** for responsive design
- **CSS3** with modern features (Grid, Flexbox, Animations)
- **GitHub Actions** for automated deployment

## 📄 License

This project is created for Carnexa. All rights reserved. 