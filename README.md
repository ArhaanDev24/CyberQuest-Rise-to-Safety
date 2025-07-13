# CyberQuest: Rise to Safety - Project Story

## 💡 What Inspired Me

With **91%** of cyberattacks starting with phishing emails and cybersecurity incidents costing companies millions, I wanted to create an engaging way to teach security skills. Traditional training is boring - people learn better through interactive stories and games.

## 🎯 What I Learned

Building this project taught me:
- **Game Design**: Creating engaging narratives that educate
- **Web Audio API**: Implementing sound effects for user feedback
- **Progressive Scoring**: Balancing challenge with achievement
- **Cybersecurity Fundamentals**: Researching real-world attack vectors

The scoring formula ensures balanced gameplay:
$$\text{Score} = \max(0, \min(140, \sum \text{correct choices} \times 20))$$

## 🛠️ How I Built It

**Tech Stack**: HTML5, Tailwind CSS, Vanilla JavaScript, Web Audio API

**Key Features**:
- 7 cybersecurity scenarios (phishing, passwords, social engineering, etc.)
- Real-time scoring with visual feedback
- Interactive audio for correct/incorrect answers
- Responsive design with cyberpunk aesthetic

**Architecture**: State-driven narrative with branching storylines based on user choices.

## 🚧 Challenges I Faced

1. **Audio Context Issues**: Browser autoplay policies required lazy initialization and proper error handling
2. **Game Flow Logic**: Preventing multiple button clicks and ensuring smooth progression
3. **Educational Balance**: Making scenarios realistic but not overwhelming for beginners
4. **Score Calculation**: Ensuring exactly 140 points possible with 7 questions worth 20 points each

## 🎉 Final Result

A fully interactive cybersecurity training game that covers essential security practices through engaging storytelling. Players can achieve expert-level knowledge while protecting fictional TechCorp from real-world threats!
