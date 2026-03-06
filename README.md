# Pritom Mondal's Portfolio - React Version

This is a React version of Pritom Mondal's portfolio website, converted from the original HTML/CSS/JavaScript implementation.

## Features

- **Modern React Architecture**: Built with functional components and React hooks
- **Responsive Design**: Fully responsive across all device sizes
- **Interactive Animations**: Smooth scrolling, hover effects, and dynamic content
- **Component-Based Structure**: Modular components for easy maintenance
- **Performance Optimized**: Efficient rendering and smooth animations

## Project Structure

```
src/
├── components/
│   ├── Header.js & Header.css
│   ├── Hero.js & Hero.css
│   ├── About.js & About.css
│   ├── Skills.js & Skills.css
│   ├── Education.js & Education.css
│   ├── Experience.js & Experience.css
│   ├── Leadership.js & Leadership.css
│   ├── NavigationBoxes.js & NavigationBoxes.css
│   ├── Gallery.js & Gallery.css
│   ├── Contact.js & Contact.css
│   └── Footer.js & Footer.css
├── App.js & App.css
├── index.js & index.css
└── package.json
```

## Setup Instructions

### 1. Install Dependencies

```bash
npm install
```

### 2. Copy Assets

You need to copy the following folders from your original project to the `public/assets/` directory:

```bash
# Copy fonts
cp -r Font/ public/assets/Font/

# Copy images
cp -r Image/ public/assets/Image/

# Copy SVGs
cp -r SVG/ public/assets/SVG/
```

**Windows PowerShell:**
```powershell
# Copy fonts
Copy-Item -Path "Font" -Destination "public\assets\Font" -Recurse

# Copy images
Copy-Item -Path "Image" -Destination "public\assets\Image" -Recurse

# Copy SVGs
Copy-Item -Path "SVG" -Destination "public\assets\SVG" -Recurse
```

### 3. Start Development Server

```bash
npm start
```

The application will open at `http://localhost:3000`

## Key Features Converted

### React Hooks Implementation
- **useState**: For managing component state (changing words, active navigation)
- **useEffect**: For side effects (date updates, animations, intervals)
- **Custom Hooks**: For reusable logic

### Component Features
- **Header**: Fixed navigation with smooth scrolling
- **Hero**: Dynamic word changing animation and current date display
- **About**: Personal information with social links
- **Skills**: Scrolling text animation
- **Education/Experience/Leadership**: Card-based layouts with hover effects
- **Navigation Boxes**: Interactive navigation with state management
- **Gallery**: Image grid with hover effects
- **Contact**: Contact information and social links
- **Footer**: Background image with title overlay

### CSS Features
- **CSS Variables**: Consistent theming
- **Responsive Design**: Mobile-first approach
- **Animations**: Smooth transitions and hover effects
- **Font Loading**: Custom Inter font family
- **Grid Layouts**: Modern CSS Grid for layouts

## Technologies Used

- **React 18**: Latest React with hooks
- **CSS3**: Modern CSS with variables and animations
- **Framer Motion**: For advanced animations (optional)
- **Create React App**: Development environment

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance Optimizations

- Component-based architecture for better performance
- CSS animations instead of JavaScript animations where possible
- Optimized image loading
- Efficient state management

## Development

### Available Scripts

- `npm start`: Start development server
- `npm build`: Build for production
- `npm test`: Run tests
- `npm eject`: Eject from Create React App

### Customization

To customize the portfolio:

1. **Content**: Update data in component files
2. **Styling**: Modify CSS files in each component
3. **Images**: Replace images in `public/assets/`
4. **Colors**: Update CSS variables in `App.css`

## Deployment

### Build for Production

```bash
npm run build
```

This creates a `build` folder with optimized production files.

### Deploy to Netlify/Vercel

1. Build the project: `npm run build`
2. Upload the `build` folder to your hosting service
3. Configure redirects for single-page application routing

## Original vs React Version

### Improvements in React Version
- **Better State Management**: React hooks for cleaner state handling
- **Component Reusability**: Modular components for easier maintenance
- **Performance**: Better rendering optimization
- **Developer Experience**: Hot reloading and better debugging
- **Scalability**: Easier to add new features and sections

### Maintained Features
- **Visual Design**: Identical to original design
- **Animations**: All original animations preserved
- **Responsiveness**: Same responsive behavior
- **Content**: All original content maintained

## License

MIT License - Feel free to use this as a template for your own portfolio.

## Contact

For questions about this React implementation, contact: contact.pritommondal@gmail.com