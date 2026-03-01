# Resume Builder - Frontend Repository

## 📦 What's Included

This is the **Frontend-Only** repository for the Resume Builder application built with React + TypeScript + Vite.

```
📁 resume-builder-frontend/
├── src/
│   ├── pages/           # All main application pages
│   ├── components/      # React components (UI, landing, resume)
│   ├── context/         # Auth and Resume context
│   ├── lib/             # Utility functions (AI, export, etc.)
│   ├── data/            # Resume templates
│   └── hooks/           # Custom React hooks
├── public/              # Static assets
├── index.html           # HTML entry point
├── package.json         # Dependencies
├── vite.config.ts       # Vite configuration
├── tailwind.config.ts   # Tailwind CSS config
└── tsconfig.json        # TypeScript configuration
```

---

## 🚀 Quick Start (Local Development)

### Prerequisites
- Node.js 18+ or Bun
- Git

### Installation

```bash
# Clone the repository
git clone https://github.com/ashutosh2975/resume-builder-frontend.git
cd resume-builder-frontend

# Install dependencies (choose one)
npm install
# or
bun install

# Configure environment
cp .env.example .env.local
# Edit .env.local and set VITE_API_BASE_URL to your backend URL
```

### Development Server

```bash
# Using npm
npm run dev

# Using Bun
bun run dev
```

The app will be available at `http://localhost:5173`

---

## 📝 Environment Configuration

Create `.env.local` file in the frontend directory:

```env
# Local development (default)
VITE_API_BASE_URL=http://https://resume-builder-backend-aj5w.onrender.com/api

# Production deployment
VITE_API_BASE_URL=https://your-backend-url.onrender.com/api
```

---

## 🔨 Build Commands

```bash
# Development build
npm run dev

# Production build
npm run build

# Preview production build
npm run preview

# Run tests
npm test

# Run tests in watch mode
npm run test:watch

# Lint code
npm run lint
```

---

## 📦 Production Build

The app is optimized for deployment on **Vercel**:

```bash
# Build for production
npm run build

# Output: dist/ directory (ready to deploy)
```

---

## 🎨 Features

✨ **Resume Builder**
- Multiple professional templates
- Real-time preview
- Drag-and-drop section ordering
- Photo upload support

🤖 **AI Enhancements**
- Improve bullet points
- Shorten/expand content
- ATS optimization
- Grammar checking

📥 **Resume Upload**
- Upload existing resume (PDF, DOCX, TXT)
- AI extraction of data
- Smart field population

📤 **Export**
- Download as PDF
- Download as PNG
- Multiple quality options

🔐 **User Management**
- User registration and login
- Save multiple resumes
- Cloud storage integration

📱 **Mobile Friendly**
- Responsive design
- Touch-optimized UI
- Safe area support for notched devices

---

## 🔗 Related Repositories

- **Backend API:** `https://github.com/ashutosh2975/Resume_builder_with_ai` (full stack)
- **This Repo:** `https://github.com/ashutosh2975/resume-builder-frontend` (frontend only)

---

## 🚀 Deployment on Vercel

### Step 1: Import Repository
1. Go to [vercel.com](https://vercel.com)
2. Click "Add New..." → "Project"
3. Select "Import Git Repository"
4. Paste: `https://github.com/ashutosh2975/resume-builder-frontend`
5. Click "Import"

### Step 2: Configure
- **Framework:** Vite (auto-detected)
- **Build Command:** `npm run build`
- **Output Directory:** `dist`

### Step 3: Environment Variables
Add in Vercel dashboard:
```
VITE_API_BASE_URL=https://your-backend-url.onrender.com/api
```

### Step 4: Deploy
Click "Deploy" and wait for the build to complete!

---

## 📚 Tech Stack

- **React 18** - UI framework
- **TypeScript** - Type safety
- **Vite** - Build tool & dev server
- **Tailwind CSS** - Styling
- **shadcn/ui** - Component library
- **React Hook Form** - Form handling
- **React Query** - State management
- **Framer Motion** - Animations
- **jsPDF & html2canvas** - PDF/PNG export
- **React Router** - Routing

---

## 📄 License

This project is open source and available under the MIT License.

---

## 🤝 Contributing

Feel free to fork this repository and submit pull requests!

---

## 📧 Support

For issues and questions:
1. Check existing GitHub issues
2. Create a new issue with detailed description
3. Include screenshots or error messages when applicable

---

## ✅ Repository Status

✅ Frontend code ready for production  
✅ Mobile-optimized  
✅ Environment variables configured  
✅ Build optimized for Vercel  

**Ready to Deploy!** 🚀
