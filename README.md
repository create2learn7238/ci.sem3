# 📜 Complete Indian Constitution Quiz

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
![Questions](https://img.shields.io/badge/Questions-502-blue)
![Chapters](https://img.shields.io/badge/Chapters-10-green)

## 📋 Overview

An interactive, comprehensive quiz application covering all 502 questions from the Indian Constitution syllabus (QB_CI_SEM-III.pdf). Test your knowledge across 10 detailed chapters with instant feedback and progress tracking.

## ✨ Features

### 🎯 Interactive Learning
- **502 Questions** covering the entire Indian Constitution syllabus
- **10 Chapters** organized by topic for focused learning
- **Instant Feedback** on every answer with explanations
- **Progress Tracking** per chapter and overall

### 📊 User Interface
- **Modern Design** with gradient backgrounds and smooth animations
- **Responsive Layout** works on desktop, tablet, and mobile
- **Dark/Light Mode** ready (auto-detects system preference)
- **Progress Bars** showing completion status for each chapter

### 📈 Tracking & Analytics
- **Real-time Stats** showing answered and correct questions
- **Chapter-wise Progress** with percentage completion
- **Detailed Results** summary with overall score
- **Answer History** persists during the session

## 🚀 Quick Start

### Option 1: Direct Usage
1. Download the `index.html` file
2. Open it in any modern web browser
3. Start learning!

### Option 2: Host Online
Upload to any static hosting service:
- GitHub Pages
- Netlify
- Vercel
- Any web server

## 📚 Chapter Breakdown

| Chapter | Title | Questions |
|---------|-------|-----------|
| 1 | Historical Background & Evolution | 50 |
| 2 | Union, Citizenship & State Reorganization | 50 |
| 3 | Fundamental Rights & Duties | 70 |
| 4 | Fundamental Rights (Continued) | 52 |
| 5 | Directive Principles of State Policy | 47 |
| 6 | Amendment of the Constitution | 24 |
| 7 | Federal System & Centre-State Relations | 52 |
| 8 | Parliament & State Legislature | 53 |
| 9 | Emergency & The President | 80 |
| 10 | Local Government | 26 |
| **Total** | | **502** |

## 🎮 How to Use

### Getting Started
1. **Select a Chapter** from the main dashboard
2. **Answer Questions** by clicking on your choice
3. **Get Instant Feedback** showing correct/incorrect answers
4. **Track Progress** via progress bars and stats

### Features Explained

#### 📊 Stats Bar
- **Total Questions**: All 502 questions
- **Total Chapters**: 10 chapters
- **Answered**: Questions you've answered
- **Correct**: Questions answered correctly

#### 🎨 Chapter Cards
Each chapter card shows:
- Chapter title and icon
- Number of questions answered / total
- Progress percentage
- Visual progress bar

#### 📝 Question Interface
- **Question Number** with ID
- **Status Indicator** (Unanswered/Correct/Incorrect)
- **Four Options** (A, B, C, D) with visual feedback
- **Explanation** showing correct answer if wrong
- **Color-coded** responses (green for correct, red for incorrect)

## 🎯 Learning Features

### Instant Feedback System
- ✅ **Correct Answer**: Green highlight with confirmation
- ❌ **Incorrect Answer**: Red highlight showing correct option
- 📖 **Explanation**: Shows correct answer with letter

### Progress Tracking
- **Per Chapter Progress**: Individual progress bars
- **Overall Stats**: Global counters for answered/correct
- **Results Summary**: Complete performance breakdown

## 📱 Responsive Design

### Desktop
- Full 3-column chapter grid
- Side-by-side question layout
- Hover effects and animations

### Tablet
- 2-column chapter grid
- Adjusted font sizes
- Touch-friendly buttons

### Mobile
- Single column layout
- Optimized for portrait
- Warning for landscape mode
- Large touch targets

## 🛠️ Technical Details

### Built With
- **HTML5** - Structure
- **CSS3** - Styling and animations
- **JavaScript** - Functionality and data management
- **Font Awesome** - Icons

### Key Features
- **No Dependencies** - Pure HTML/CSS/JavaScript
- **Single File** - Easy to deploy and share
- **Offline Ready** - Works without internet
- **Session Storage** - Progress persists during session

### Data Structure
```javascript
quizData = {
  "chapter1": {
    title: "Chapter Title",
    icon: "fa-icon-class",
    questions: [
      {
        id: 1,
        text: "Question text?",
        options: ["Option A", "Option B", "Option C", "Option D"],
        correct: 0  // Index of correct answer
      }
    ]
  }
}
