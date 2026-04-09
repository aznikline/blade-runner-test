# Blade Runner Voight-Kampff & Baseline Test

A cyberpunk-styled interactive web-based questionnaire inspired by the Voight-Kampff Test and Baseline Test from the Blade Runner universe.

![Blade Runner Aesthetic](https://img.shields.io/badge/aesthetic-cyberpunk%20%7C%20neon%20%7C%20retro--futuristic-ff00ff?style=for-the-badge)

## About This Project

This application implements a fictional empathy test based on the **Voight-Kampff Machine** used by Blade Runners to detect replicants. The test measures emotional responses through scenario-based questions to distinguish between humans and replicants.

### What is the Voight-Kampff Test?

In the Blade Runner universe, the **Voight-Kampff Test** is a polygraph-like machine that measures physiological responses (pupil dilation, blushing, respiration) while the subject is presented with emotionally charged scenarios. The test typically takes 20-30 questions and can distinguish between humans and Nexus-6 replicants.

### What is the Baseline Test?

The **Baseline Test** (also called the "Voight-Kampff Baseline") is a shorter, more direct test used to ensure replicants don't develop human emotions over their lifespans. It asks simpler, more direct questions about empathy and moral reasoning.

## Features

- **16 questions** combining VK Test and Baseline Test styles
- **Cyberpunk aesthetic** with neon cyan/magenta color scheme
- **Animated UI** with scanlines, glitch effects, and smooth transitions
- **Progress tracking** with visual progress bar
- **Detailed analysis** showing empathy index and classification
- **Responsive design** works on desktop and mobile
- **No dependencies** - pure HTML, CSS, and JavaScript

## How to Run

Simply open `index.html` in any modern web browser. No server required!

```bash
# Option 1: Double-click index.html

# Option 2: Open with browser
open index.html          # macOS
xdg-open index.html      # Linux
start index.html         # Windows
```

## Questions Included

### VK Test Style (Questions 1-8)
1. Describe in single words the good things about your mother
2. Your son shows you his butterfly collection + killing jar
3. A middle-aged man has an眼角 come to rest
4. A woman at a play starts crying
5. Desert scenario with water
6. Best friend dying in terrible pain
7. Photo of loved one in an envelope
8. Electric vs. real animals

### Baseline Test Style (Questions 9-16)
9. Person crying at a diner
10. Memory erasure question
11. Lost child scenario
12. Found wallet scenario
13. Witnessing bullying
14. Stranger without food
15. Partner saying "I'm fine"
16. Rumors being spread about you

## Classification Results

The test provides a final **Empathy Index Score** and classifies you as:

| Score | Classification |
|-------|---------------|
| 70%+ | **HUMAN** - Strong empathic responses |
| 40-69% | **UNCERTAIN** - Inconclusive results |
| <40% | **REPLICANT** - Reduced empathic responses |

## Technical Details

- Pure vanilla HTML5, CSS3, JavaScript (ES6)
- Google Fonts: Orbitron, Share Tech Mono
- CSS Grid and Flexbox for layout
- CSS animations for visual effects
- No external dependencies
- Single file deployment

## Screenshots

The application features:
- Animated neon gradient header
- Scanline overlay effect
- Glitch text animation on title
- Card-based question layout
- Progress bar with gradient fill
- Responsive option buttons
- Animated results display

## Lore Context

In Ridley Scott's *Blade Runner* (1982) and Denis Villeneuve's *Blade Runner 2049*, the Voight-Kampff test is used by Blade Runners to identify replicants—bioengineered beings that are nearly identical to humans. The test measures empathic responses, as replicants were designed without the ability to fully simulate human emotions.

The Nexus-6 replicants were so advanced that they required 100-200 questions to detect. Later models in the films showed even more human-like responses, making detection increasingly difficult.

## License

This is a fan project created for educational and entertainment purposes. Blade Runner and Voight-Kampff are trademarks of their respective owners.

---

**All those moments will be lost in time, like tears in rain. Time to run the test.**
