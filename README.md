# Web Calculator

A modern, responsive calculator web application converted from Python Tkinter to React with TypeScript.

![Calculator Preview](https://images.pexels.com/photos/5699456/pexels-photo-5699456.jpeg?auto=compress&cs=tinysrgb&w=800)

## 🚀 Live Demo

[View Live Calculator](https://your-calculator-url.netlify.app) *(Replace with your actual deployment URL)*

## ✨ Features

- **Full Calculator Functionality**: Addition, subtraction, multiplication, and division
- **Modern UI Design**: Clean, professional interface with smooth animations
- **Responsive Layout**: Works perfectly on desktop, tablet, and mobile devices
- **Error Handling**: Prevents division by zero with proper error messages
- **Keyboard Support**: Use your keyboard for quick calculations
- **Visual Feedback**: Button hover effects and click animations

## 🛠️ Technologies Used

- **React 18** - Modern JavaScript library for building user interfaces
- **TypeScript** - Type-safe JavaScript for better development experience
- **Tailwind CSS** - Utility-first CSS framework for rapid styling
- **Vite** - Fast build tool and development server
- **Lucide React** - Beautiful, customizable icons

## 📱 Screenshots

### Desktop View
The calculator features a clean, modern design with a dark display area and colorful operation buttons.

### Mobile View
Fully responsive design that adapts perfectly to mobile screens while maintaining usability.

## 🏃‍♂️ Quick Start

### Prerequisites
- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/web-calculator.git
   cd web-calculator
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open in browser**
   Navigate to `http://localhost:5173` to see the calculator in action.

## 📦 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint for code quality

## 🎯 Usage

### Basic Operations
1. Click number buttons to input values
2. Click operation buttons (+, -, *, /) to select operations
3. Click equals (=) to calculate the result
4. Click C to clear the display

### Keyboard Shortcuts
- **Numbers (0-9)**: Input numbers
- **+, -, *, /**: Mathematical operations
- **Enter or =**: Calculate result
- **Escape or C**: Clear display

## 🏗️ Project Structure

```
src/
├── components/
│   └── Calculator.tsx      # Main calculator component
├── App.tsx                 # Root application component
├── main.tsx               # Application entry point
├── index.css              # Global styles and Tailwind imports
└── vite-env.d.ts          # TypeScript environment definitions

public/
└── vite.svg               # Application favicon

Configuration Files:
├── package.json           # Dependencies and scripts
├── tsconfig.json          # TypeScript configuration
├── tailwind.config.js     # Tailwind CSS configuration
├── vite.config.ts         # Vite build configuration
└── eslint.config.js       # ESLint configuration
```

## 🔧 Development

### Adding New Features
1. Create new components in the `src/components/` directory
2. Import and use them in `App.tsx` or other components
3. Follow TypeScript best practices for type safety

### Styling Guidelines
- Use Tailwind CSS utility classes for styling
- Follow the existing color scheme and design patterns
- Ensure responsive design for all new components

### Code Quality
- Run `npm run lint` before committing changes
- Follow TypeScript strict mode guidelines
- Use meaningful variable and function names

## 🚀 Deployment

### Netlify (Recommended)
1. Build the project: `npm run build`
2. Deploy the `dist` folder to Netlify
3. Configure build settings:
   - Build command: `npm run build`
   - Publish directory: `dist`

### Other Platforms
- **Vercel**: Connect your GitHub repository for automatic deployments
- **GitHub Pages**: Use GitHub Actions for automated deployment
- **Firebase Hosting**: Use Firebase CLI for deployment

## 🐛 Known Issues

- None currently reported

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Original Python Tkinter calculator implementation
- React and TypeScript communities
- Tailwind CSS for the amazing utility-first approach
- Lucide React for beautiful icons

## 📞 Contact

- **Developer**: Your Name
- **Email**: your.email@example.com
- **GitHub**: [@yourusername](https://github.com/yourusername)
- **LinkedIn**: [Your LinkedIn Profile](https://linkedin.com/in/yourprofile)

---

⭐ **Star this repository if you found it helpful!**
