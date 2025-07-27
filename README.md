# Celestial 🌌

A space-themed mood tracking web application that transforms daily emotional wellness into an immersive cosmic journey. Track your moods by selecting planets in a beautiful solar system interface, create mission log-style journal entries, and explore personalized guidance tailored to your emotional state.

## ✨ Features

### 🪐 Planetary Mood Selection
- Interactive solar system interface for mood tracking
- Each planet represents a different emotion (Mercury for anxious, Venus for love, Mars for energetic, etc.)
- Hover effects with emotion emojis and planet animations
- Visual feedback with orbital rings and cosmic glow effects

### 📝 Mission Log Journaling
- Star Trek-inspired mission log interface
- Text and voice recording capabilities
- Stardate timestamp system for entries
- Status tracking (ongoing, completed, archived)

### 📊 Cosmic Analytics
- Mood distribution visualization
- Streak tracking with cosmic fire indicators
- Predominant mood identification
- Weekly pattern analysis

### 🧘 Meditation & Breathing Exercises
- Mood-specific guided exercises
- Interactive breathing visualizations
- Personalized recommendations based on current emotional state

### 🎨 Immersive Space Theme
- Animated starfield backgrounds
- Cosmic color palette with gradient effects
- Retro computer interface aesthetics
- Responsive design with mobile optimization

## 🚀 Technology Stack

### Frontend
- **React 18** with TypeScript
- **Vite** for build tooling and development
- **Wouter** for lightweight routing
- **shadcn/ui** component library
- **Tailwind CSS** for styling
- **TanStack Query** for state management

### Backend
- **Express.js** with TypeScript
- **PostgreSQL** database
- **Drizzle ORM** for type-safe database operations
- **Neon Database** for cloud hosting

### Additional Features
- **Web Audio API** for voice recording
- **React Hook Form** with Zod validation
- **Framer Motion** for animations
- **Custom CSS** for space-themed effects

## 🛠️ Installation

1. Clone the repository
```bash
git clone <repository-url>
cd stellar-mood
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
```bash
# Copy the example environment file
cp .env.example .env

# Add your database URL and other required variables
DATABASE_URL=your_postgresql_connection_string
```

4. Run database migrations
```bash
npm run db:migrate
```

5. Start the development server
```bash
npm run dev
```

The application will be available at `http://localhost:5000`

## 📱 Usage

1. **Dashboard**: Overview of your cosmic journey with quick mood selection and recent activity
2. **Mood Tracker**: Select your current emotional state using the planetary interface
3. **Mission Log**: Create journal entries with text or voice recordings
4. **Analytics**: View your emotional patterns and trends over time

## 🎯 Key Differentiators

- **Visual Innovation**: Planet-based mood selection instead of traditional interfaces
- **Immersive Experience**: Complete space aesthetic with stardates and cosmic terminology
- **Multi-modal Input**: Supports text, voice, and visual mood tracking
- **Personalized Guidance**: Contextual tips and meditation exercises
- **Gamified Wellness**: Makes mood tracking engaging rather than clinical

## 🌟 Design Philosophy

Celestial transforms the often clinical experience of mood tracking into an engaging space exploration adventure. By using familiar celestial bodies as emotional anchors and incorporating Star Trek-inspired interfaces, the app makes mental health tracking feel expansive and hopeful rather than limiting.

## 🔧 Development

### Scripts
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run db:migrate` - Run database migrations
- `npm run db:studio` - Open Drizzle Studio for database management

### Project Structure
```
├── client/src/          # React frontend
│   ├── components/      # Reusable UI components
│   ├── pages/          # Page components
│   ├── hooks/          # Custom React hooks
│   └── lib/            # Utility functions
├── server/             # Express backend
│   ├── routes.ts       # API endpoints
│   └── storage.ts      # Database operations
├── shared/             # Shared types and schemas
└── attached_assets/    # Static assets
```

## 🌌 Future Enhancements

- User authentication and profiles
- Social features for sharing cosmic insights
- Advanced meditation programs
- Mood prediction using AI
- Integration with wearable devices
- Expanded planet system with more emotions

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

---

*Transform your emotional wellness journey into a cosmic adventure with Celestial* ✨
