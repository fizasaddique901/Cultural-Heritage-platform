# Cultural-Heritage-platform
Web platform for cultural heritage preservation

# Heritage Hub - Cultural Heritage Preservation Platform

A modern web platform dedicated to preserving and celebrating cultural heritage by connecting youth with their roots through stories, traditions, and shared wisdom.

## Overview

Heritage Hub is an educational and engaging platform that digitally preserves cultural heritage and helps young people connect with their cultural roots. This platform features cultural stories, traditional attire galleries, indigenous languages, values, educational facts, and a contribution system for youth to share their own traditions.

## Features

### Core Features

1. **Homepage**
   - Mission statement and cultural importance
   - Featured cultural stories
   - Call-to-action for exploration and contribution

2. **Cultural Stories Section**
   - Text-based stories with beautiful images
   - Category filtering (folklore, tradition, history)
   - Featured story highlights

3. **Traditional Attire Gallery**
   - Card-based gallery showcasing traditional clothing
   - Detailed descriptions of cultural significance
   - Regional and occasion-based organization

4. **Languages & Values Page**
   - Indigenous language phrases and translations
   - Cultural meanings and context
   - Proverbs, greetings, and moral teachings

5. **Cultural Facts Section**
   - Short educational facts about cultural heritage
   - Category-based organization
   - Source attribution

6. **Youth Contribution Page**
   - Submission form for stories and traditions
   - Multiple contribution types (story, tradition, recipe, craft, language)
   - Review system for quality control

7. **About & Impact Page**
   - Problem statement and solution
   - Target audience and impact
   - Future vision and roadmap

## Tech Stack

- **Frontend**: React 18 with Vite
- **Routing**: React Router DOM
- **Database**: Supabase (PostgreSQL)
- **Styling**: Custom CSS with CSS Variables
- **Images**: Pexels stock photos

## Design Features

- Clean, modern UI with cultural aesthetics
- Earthy color palette (browns, beiges, greens, maroon)
- Fully responsive design (mobile + desktop)
- Smooth animations and transitions
- Accessible and youth-friendly interface

## Project Structure

```
project/
├── src/
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── Header.css
│   │   ├── Footer.jsx
│   │   └── Footer.css
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── Home.css
│   │   ├── Stories.jsx
│   │   ├── Stories.css
│   │   ├── Attire.jsx
│   │   ├── Attire.css
│   │   ├── Languages.jsx
│   │   ├── Languages.css
│   │   ├── Facts.jsx
│   │   ├── Facts.css
│   │   ├── Contribute.jsx
│   │   ├── Contribute.css
│   │   ├── About.jsx
│   │   └── About.css
│   ├── lib/
│   │   └── supabase.js
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── .env
├── package.json
└── README.md
```

## Database Schema

### Tables

1. **cultural_stories**
   - Stores cultural narratives with images
   - Fields: title, content, image_url, author, category, is_featured

2. **traditional_attire**
   - Showcases traditional clothing
   - Fields: name, description, image_url, region, occasion

3. **languages_values**
   - Preserves indigenous languages and sayings
   - Fields: language_name, phrase, translation, meaning, type

4. **cultural_facts**
   - Educational cultural facts
   - Fields: fact, category, source

5. **youth_contributions**
   - User-submitted content
   - Fields: contributor_name, contributor_email, title, content, type, status

## Get Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```

3. The database is already configured with sample data

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Build for production:
   ```bash
   npm run build
   ```

## Features Breakdown

### Navigation
- Sticky header with responsive mobile menu
- Smooth scroll navigation
- Active link indicators

### Homepage
- Hero section with gradient background
- Mission cards with icons
- Featured stories grid
- Call-to-action section

### Content Pages
- Consistent page headers with gradients
- Filter functionality for categories/types
- Card-based layouts with hover effects
- Responsive grid systems

### Contribution Form
- Validation for required fields
- Multiple submission types
- Success/error feedback
- Guidelines and information section

### Design System
- CSS Variables for consistent theming
- Reusable utility classes
- Responsive breakpoints at 768px and 480px
- Smooth transitions and animations

## Color Palette

- Primary: #8B4513 (Saddle Brown)
- Secondary: #D2691E (Chocolate)
- Accent: #556B2F (Dark Olive Green)
- Earth: #DEB887 (Burlywood)
- Sage: #8FBC8F (Dark Sea Green)
- Maroon: #800000
- Background: #FDFBF7 (Warm White)

## Responsive Design

The platform is fully responsive with breakpoints for:
- Desktop (>968px): Full layout with multi-column grids
- Tablet (768px-968px): Adjusted layouts
- Mobile (<768px): Single column layouts, mobile navigation

## Future Enhancements

1. Multimedia integration (audio, video)
2. Language learning tools
3. Virtual reality cultural experiences
4. Mobile application
5. Community partnerships
6. AI-powered content preservation

## License

This project is open source and available for educational purposes.

## Contact

For questions or contributions, please use the contribution form on the platform.

---

Built with passion for cultural preservation and heritage celebration.
