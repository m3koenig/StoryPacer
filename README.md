# StoryPacer

A trainer app to improve your storytelling skills through structured practice (Built with AI)

[🚀 Try it now](https://m3koenig.github.io/StoryPacer)

## What is StoryPacer?

StoryPacer teaches you to tell stories with better pacing and atmosphere. It breaks storytelling into two phases:

1. **Setup Phase (45s)** - Describe only the environment and atmosphere using all your senses
2. **Action Phase (45s)** - Continue the story with events and movement

The key insight: Separate scene-building from action to improve your storytelling flow and learn to hold atmospheric tension.

## Features

- 🎙️ **Guided Storytelling** - Two-phase training with timers
- 🎬 **17 Built-in Scenarios** - Atmospheric prompts to inspire you
- 📁 **Custom Scenarios** - Import your own `.json` files
- 🔗 **URL Sharing** - Share specific stories with others via URL parameters
- 🌙 **Dark Theme** - Easy on the eyes during practice sessions
- ⏸️ **Breathing Breaks** - Mindful transitions between phases

## Getting Started

### Online (No installation needed)
Visit [m3koenig.github.io/StoryPacer](https://m3koenig.github.io/StoryPacer) and start immediately.

### Local Setup
```bash
# Clone the repository
git clone https://github.com/m3koenig/StoryPacer.git
cd StoryPacer

# Serve locally (requires a local server)
python -m http.server 8000
# or use Live Server in VS Code
```

Then open `http://localhost:8000` in your browser.

## How to Use

### Basic Training
1. Click **Starten** on the home screen
2. Take a deep breath during the breathing exercise
3. **Setup Phase**: Describe the scenario's atmosphere—what you see, hear, feel, smell
4. **Pause**: Hold the silence for 3 seconds
5. **Action Phase**: Tell what happens next in the story
6. Get feedback and start again

### Import Custom Scenarios

Create a `.json` file with an array of story prompts:

```json
[
  "You wake up in an abandoned train station.",
  "You find a mysterious door in your basement.",
  "You're alone in a crowded subway that suddenly stops."
]
```

Upload it in the app or download the template from the help screen.

### Share Specific Scenarios via URL

Pass a story directly in the URL:

```
https://m3koenig.github.io/StoryPacer/?story=You%20wake%20up%20in%20an%20old%20library%20at%20midnight
```

Perfect for practice groups or teaching scenarios.

## Technology Stack

- **Frontend**: HTML5, Vanilla JavaScript, Tailwind CSS
- **Deployment**: GitHub Pages
- **No Backend**: Fully client-side, works offline

## License

MIT License - See [LICENSE](LICENSE) for details

## Contributing

Found a bug or have a feature idea? Open an issue or submit a pull request!

---

**Practice tip**: Do this regularly. Separating atmosphere from action rewires how you tell stories.