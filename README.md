# 🎭 Paranoma - Interactive 360° Panorama Editor

A Next.js-based interactive 360° panorama viewer and editor built with Three.js and React Three Fiber. Create immersive panoramic experiences with blur effects, text annotations, and interactive controls.

![Paranoma Demo](public/paranoma.webp)

## 🖼️ Project Images

- **paranoma.webp** - Main panorama image used in the application
- **next.svg** - Next.js logo
- **vercel.svg** - Vercel deployment platform logo

## ✨ Features

- **360° Panorama Viewer**: Immersive spherical panorama viewing experience
- **Interactive Controls**: Orbit controls for camera movement and exploration
- **Blur Effects**: Add selective blur effects to specific areas of the panorama
- **Text Annotations**: Place and edit text overlays on the panorama
- **Real-time Editing**: Interactive tools for immediate visual feedback
- **Responsive Design**: Modern UI with Tailwind CSS styling
- **TypeScript Support**: Full type safety and modern development experience

## 🛠️ Tech Stack

- **Frontend**: Next.js 13, React 18, TypeScript
- **3D Graphics**: Three.js, React Three Fiber, React Three Drei
- **Styling**: Tailwind CSS, PostCSS
- **State Management**: Zustand, Redux Toolkit
- **Maps**: Mapbox GL, Maplibre GL
- **Animation**: GSAP
- **Development**: ESLint, Prettier, Husky

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd Next_Paranoma
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🎮 How to Use

### Basic Navigation
- **Mouse/Touch**: Click and drag to rotate the panorama view
- **Scroll**: Zoom in/out of the panorama

### Editing Tools

#### Camera Control Mode
- Default mode for navigating the panorama
- Click and drag to rotate, scroll to zoom

#### Blur Effect Tool
- Select the blur tool from the bottom-right panel
- Click anywhere on the panorama to add a blur effect
- Perfect for hiding sensitive information or creating focus areas

#### Text Annotation Tool
- Select the text tool from the panel
- Click on the panorama to place text
- Edit text content and styling in real-time

#### Remove Items
- Select the remove tool to delete blur effects or text annotations
- Click on items to remove them

## 📁 Project Structure

```
Next_Paranoma/
├── src/
│   ├── app/
│   │   └── (home)/
│   │       ├── page.tsx          # Main page component
│   │       └── scene.tsx         # 3D scene setup
│   ├── components/
│   │   ├── BlurDot/              # Blur effect component
│   │   ├── Loading/              # Loading state component
│   │   ├── Panel/                # Tool selection panel
│   │   ├── Paranoma/             # Main panorama component
│   │   └── TextEditor/           # Text annotation component
│   └── store/
│       ├── useAction.tsx         # Action state management
│       ├── useBlurStack.tsx      # Blur effects state
│       └── useText.tsx           # Text annotations state
├── public/
│   └── paranoma.webp             # Panorama image
└── package.json
```

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint and Prettier
- `npm run lint:check` - Check code quality
- `npm run analyze` - Analyze bundle size

## 🎨 Customization

### Adding New Panoramas
1. Place your panorama image in the `public/` folder
2. Update the texture path in `src/components/Paranoma/index.tsx`
3. Adjust the sphere geometry size if needed

### Custom Tools
1. Create new tool components in the `components/` folder
2. Add tool state to the appropriate store
3. Update the Panel component to include your new tool

### Styling
- Modify `src/app/globals.css` for global styles
- Use Tailwind CSS classes for component styling
- Customize `tailwind.config.ts` for theme changes

## 🚧 Development

### Code Quality
- ESLint for code linting
- Prettier for code formatting
- Husky for git hooks
- TypeScript for type safety

### State Management
- Zustand for local component state
- Redux Toolkit for complex state logic
- Custom hooks for reusable state logic

## 📱 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is private and proprietary. All rights reserved.

## 📧 Contact

- **Email**: metaversy.world@gmail.com
- **Project**: Paranoma

## 🙏 Acknowledgments

- Three.js community for 3D graphics capabilities
- React Three Fiber for React integration
- Next.js team for the amazing framework
- Tailwind CSS for utility-first styling

---

**Note**: This is a private project. Please respect the intellectual property and do not distribute without permission.
