# Social Quest - Interactive Social Skills Learning for Autistic Children

An educational React application designed to help autistic children (ages 6-12) learn and practice social skills through interactive scenarios and game-based learning.

##  Features

### Core Learning Approach
- **5 Master Principles**: Universal social rules that apply to ANY situation
- **Practice Mode**: Learn through familiar scenarios in 5 different locations
- **Challenge Mode**: Apply principles to unexpected situations
- **Progressive Learning**: Track mastery of tools and principles

### Sensory-Friendly Design
- Muted color palette (pastels, soft blues)
- Gentle animations only
- Large, clear buttons and text
- Predictable, consistent layout
- No autoplaying sounds or flashy effects

### Educational Features
- **15 Interactive Scenarios**:
  - 10 guided scenarios across 5 locations
  - 5 unexpected challenge scenarios
- **Personal Story Analyzer**: NEW! Kids can input their own situations and get personalized advice
- **Immediate Feedback**: Positive reinforcement and gentle corrections
- **Concrete Language**: Direct, literal instructions (no metaphors)
- **Progress Tracking**: Stars, tools, and mastered principles
- **Meta-Learning**: Teaching flexible thinking, not rigid scripts

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone or download this repository
2. Navigate to the project directory:
   ```bash
   cd social-quest-app
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:5173`

##  How It Works

### The 5 Master Principles

1. ** Safety First**: If something feels unsafe, find an adult
2. ** Use Your Words**: Communicate needs and feelings calmly
3. ** Respect Space**: Keep one arm's length from others
4. ** Wait and Watch**: Pause and observe when confused
5. ** Ask for Help**: It's always okay to ask for help

### Learning Modes

**Practice Mode** - Five locations with guided scenarios:
- 🛒 Supermarket
- 🍽️ Restaurant
- 🎪 Playground
- 🏥 Waiting Room
- 🏫 School Hallway

**Challenge Mode** - Unexpected situations:
- Fire alarm emergencies
- Language barriers
- Routine changes
- Unfamiliar situations
- Making mistakes in public

**Personal Story Analyzer** - NEW Interactive Feature:
- Kids share their own uncomfortable situations
- AI-powered analysis based on the 5 Master Principles
- Personalized advice for "what to do differently next time"
- Helps apply learned principles to real-life experiences
- Builds self-reflection and growth mindset

## 🎨 Customization

### Adding New Scenarios

Edit `src/data/scenarios.js` or `src/data/unexpectedScenarios.js`:

```javascript
{
  id: 'unique_id',
  title: 'Scenario Title',
  situation: 'Description of the situation',
  image: '🎯', // Emoji representation
  principles: ['safety', 'words'], // Related principles
  choices: [
    {
      text: 'Choice text',
      isCorrect: true,
      feedback: 'Explanation of why this is good',
      tool: 'Tool Name', // Optional
      principlesUsed: ['safety'] // Optional
    },
    // ... more choices
  ]
}
```

### Modifying Master Principles

Edit `src/data/masterPrinciples.js` to change the core rules.

### Styling Changes

- Global styles: `src/index.css`
- Tailwind config: `tailwind.config.js`
- Component-specific styles: Use Tailwind classes in components

## 🛠️ Build for Production

```bash
npm run build
```

The built files will be in the `dist/` directory.



## 📄 License

This project is created for educational purposes.

