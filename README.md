# Food Waste Dashboard

A comprehensive dashboard for tracking and managing food waste with AI-powered insights, gamification, and sustainability metrics.

![Dashboard Preview](https://raw.githubusercontent.com/yourusername/food-waste-dashboard/main/preview.png)

## Features

- 📊 Real-time waste tracking and analytics
- 🤖 AI-powered insights and predictions
- 🌱 Sustainability scoring and environmental impact
- 🎮 Gamification with challenges and achievements
- 📈 What-If analysis and forecasting
- 🔔 Smart alerts and notifications
- 📱 Responsive design for all devices

## Tech Stack

- React 18
- TypeScript
- Vite
- Tailwind CSS
- Supabase
- Recharts
- Lucide Icons

## Prerequisites

- Node.js 16+
- npm or yarn
- Supabase account

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/food-waste-dashboard.git
cd food-waste-dashboard
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
Create a `.env` file in the root directory with your Supabase credentials:
```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

4. Start the development server:
```bash
npm run dev
```

5. Open [http://localhost:5173](http://localhost:5173) in your browser

## Database Setup

The project uses Supabase as the backend. Run the migrations in the `supabase/migrations` folder to set up the database schema:

```bash
supabase migration up
```

## Project Structure

```
├── src/
│   ├── components/     # React components
│   ├── hooks/         # Custom React hooks
│   ├── lib/           # Utilities and configurations
│   ├── types/         # TypeScript type definitions
│   └── utils/         # Helper functions
├── supabase/
│   └── migrations/    # Database migrations
└── public/           # Static assets
```

## Key Features

### Real-time Tracking
- Live waste monitoring
- Historical data visualization
- Period comparison

### AI Features
- Waste prediction
- Trend analysis
- Anomaly detection
- Smart recommendations

### Sustainability
- Environmental impact tracking
- Carbon footprint calculation
- Sustainability scoring

### Gamification
- Monthly challenges
- Achievement badges
- Leaderboards

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Recharts](https://recharts.org/) for beautiful charts
- [Lucide](https://lucide.dev/) for icons
- [Tailwind CSS](https://tailwindcss.com/) for styling
- [Supabase](https://supabase.com/) for backend services