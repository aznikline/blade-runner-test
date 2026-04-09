# Voight-Kampff Voice-Enabled Empathy Test

A cyberpunk-styled interactive web-based questionnaire inspired by the Voight-Kampff Test from the Blade Runner universe. **Now with full voice interaction support.**

![Blade Runner Aesthetic](https://img.shields.io/badge/aesthetic-cyberpunk%20%7C%20neon%20%7C%20retro--futuristic-ff00ff?style=for-the-badge)
![Voice Enabled](https://img.shields.io/badge/voice-enabled-brightgreen?style=for-the-badge)
![Questions](https://img.shields.io/badge/questions-22-blue?style=for-the-badge)

## About This Project

This application implements a **voice-enabled** empathy test based on the **Voight-Kampff Machine** used by Blade Runners to detect replicants. The test measures emotional responses through voice analysis and scenario-based questions.

### What is the Voight-Kampff Test?

In the Blade Runner universe, the **Voight-Kampff Test** is a polygraph-like machine that measures physiological responses (pupil dilation, blushing, respiration) while the subject is presented with emotionally charged scenarios.

## What's New in v3.0

### Voice Interaction
- **Speech Synthesis**: Questions are read aloud using Web Speech API with a calibrated voice
- **Speech Recognition**: Your spoken responses are captured and analyzed
- **Voice Status Indicator**: Real-time feedback on microphone and synthesis status
- **Keyboard Shortcuts**: Press `Space` to hear question, `Enter` to proceed

### Extended Question Bank
- **22 questions** combining VK Test and Baseline Test styles
- Categories: Emotional Memory, Empathy Action, Moral Dilemma, Social Response
- Deeper probing questions for authentic emotional measurement

### Enhanced UI
- CRT scanline overlay effect
- Animated pupil monitoring visualization
- Real-time heartbeat line animation
- Voice waveform visualizer
- Listening state indicator with animated dots

## Features

- **Voice-first interaction**: Speak or type your answers
- **22 questions** in 5 categories (VK Test, Baseline, Deep Empathy, Self-Reflection, Final Assessment)
- **Cyberpunk aesthetic** with neon cyan/magenta color scheme
- **CRT monitor effects** with scanlines and vignette
- **Animated pupil monitor** simulation
- **Heartbeat visualization** during test
- **Progress tracking** with glowing progress bar
- **Detailed analysis** showing empathy index and classification
- **Response review** showing all your answers
- **Responsive design** works on desktop and mobile
- **No dependencies** - pure HTML, CSS, and JavaScript

## How to Run

Simply open `index.html` in any modern web browser. **For best voice experience, use Chrome or Edge.**

```bash
# Option 1: Double-click index.html

# Option 2: Open with browser
open index.html          # macOS
xdg-open index.html      # Linux
start index.html         # Windows
```

### Voice Permissions

The browser will request microphone access for speech recognition. Allow it for the full voice interaction experience.

### Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Space` | Read current question aloud |
| `Enter` | Proceed to next question |

## Question Categories

### Section A: Classic VK Test (7 questions)
Focus on empathy, emotional memory, and moral dilemmas.

### Section B: Baseline Test (5 questions)
Emotional trigger word scenarios and social responses.

### Section C: Deep Empathy (4 questions)
Complex emotional reasoning and personal reflection.

### Section D: Self-Reflection (4 questions)
Emotional awareness and identity questions.

### Section E: Final Assessment (2 questions)
Core identity and regret attachment.

## Scoring System

The test analyzes your responses for:

| Metric | Description |
|--------|-------------|
| **VK Empathy Index** | Score based on emotional resonance in classic VK scenarios |
| **Baseline Response** | Score based on social and emotional trigger responses |
| **Total Empathy Score** | Combined classification score |

### Classification Results

| Score | Classification |
|-------|----------------|
| 70%+ | **HUMAN** - Strong empathic responses with authentic emotional processing |
| 40-69% | **UNCERTAIN** - Inconclusive results requiring further evaluation |
| <40% | **REPLICANT** - Reduced empathic responses with atypical emotional patterns |

### Analysis Factors

The AI scoring considers:
- Emotional word usage
- Response length and complexity
- Uncertainty expression
- Rationalization patterns
- Category-specific indicators

## Technical Details

- Pure vanilla HTML5, CSS3, JavaScript (ES6)
- Google Fonts: Orbitron, Share Tech Mono, Special Elite
- Web Speech API (SpeechSynthesis + SpeechRecognition)
- CSS Grid and Flexbox for layout
- CSS animations for visual effects
- No external dependencies
- Single file deployment

## Browser Compatibility

| Feature | Chrome | Edge | Firefox | Safari |
|---------|--------|------|---------|--------|
| Speech Synthesis | Full | Full | Full | Full |
| Speech Recognition | Full | Full | Limited | Limited |
| CRT Effects | Full | Full | Full | Full |

## Screenshots

The application features:
- Animated neon gradient header with glitch effect
- CRT scanline and vignette overlay
- Animated pupil monitoring simulation
- Real-time heartbeat visualization
- Voice waveform animation
- Pulsing microphone status indicator
- Card-based question layout
- Glowing progress bar with animated indicator
- Response history review
- Detailed metrics dashboard

## Lore Context

In Ridley Scott's *Blade Runner* (1982) and Denis Villeneuve's *Blade Runner 2049*, the Voight-Kampff test is used by Blade Runners to identify replicants—bioengineered beings that are nearly identical to humans. The test measures empathic responses, as replicants were designed without the ability to fully simulate human emotions.

The Nexus-6 replicants were so advanced that they required 100-200 questions to detect. Later models in the films showed even more human-like responses, making detection increasingly difficult.

## License

This is a fan project created for educational and entertainment purposes. Blade Runner and Voight-Kampff are trademarks of their respective owners.

---

**All those moments will be lost in time, like tears in rain. Time to run the test.**
