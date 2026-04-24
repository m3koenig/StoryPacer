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
- 🎬 **Built-in Scenarios** - Atmospheric prompts to inspire you
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
 
```

Then open `index.html` in your browser.

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


## Crafting "Skeleton Prompts"

While many prompts provide sensory details (VAKOG) to help the speaker, Skeleton Prompts take the opposite approach. They provide only the bare architectural minimum—a situation or a location—forcing the storyteller to generate every single sensory detail from scratch during Phase 1 (The Setup).

1. The Core Philosophy: The Empty Stage

A Skeleton Prompt is like an empty stage with only one prop. It defines where you are and what the basic situation is, but it deliberately ignores how it looks, sounds, or feels.

VAKOG Prompt: "You stand in a cold, damp cellar where a single bulb flickers overhead."

Skeleton Prompt: "You are locked in a cellar."

2. Why Strip Away Sensory Details?

By removing VAKOG elements from the base text, you achieve several training goals:

Active Generation: The speaker cannot simply "repeat" the description provided in the text.

Creative Ownership: The speaker decides if the cellar is high-tech, medieval, or domestic.

Sense of Discovery: The speaker "discovers" the smell or the temperature in real-time as they talk.

3. How to Write a Good Skeleton Prompt

A. Define the Boundary

Tell the user exactly where they are limited to.

Example: "You are inside a stranded submarine."

B. Use a Static Starting Point

Ensure there is no immediate action happening. The prompt should feel like a "Start" button, not a "Fast Forward" button.

Example: "You are sitting at the head of a long, empty banquet table."

C. Include a "Mystery Variable"

Provide one object or circumstance that requires explanation, but don't explain it.

Example: "You are in an elevator that has stopped between floors, and there is a gift-wrapped box on the floor." (The box is the variable; how it looks or smells is up to the speaker).

4. Examples of High-Quality Skeleton Prompts

"You are standing on a stage behind a heavy velvet curtain."

"You are in the driver's seat of a car parked on an empty bridge."

"You wake up in a hospital room with no windows."

"You are at the top of a lighthouse during a calm night."

"You are inside a high-security vault that just slammed shut."


## Criteria for Excellent Practice Texts

A strong practice text in Story Pacer serves as a "spark." It should provide enough detail to create a mental image but remain vague enough for the storyteller to fill in the gaps.

### 1. Focus on Location and Atmosphere (Setting)
A good text describes a place or a state, not a plot.
 * **Bad:** "You fight a dragon in a cave." (Dictates action)
 * **Good:** "You stand at the entrance of a massive cave, with a hot, sulfurous wind blowing from its depths." (Focuses on the setting)

### 2. The VAKOG Principle (Sensory Input)
Great texts trigger at least two or three senses to make Phase 1 (Setup) easier to navigate:
 * **Visual (Seeing):** "Flickering neon lights," "thick fog."
 * **Auditory (Hearing):** "A rhythmic dripping," "distant howling of wolves."
 * **Kinesthetic/Olfactory (Feeling/Smelling):** "Clammy cold," "the smell of old paper."

### 3. Tension or Curiosity
An effective scenario creates a subtle sense of tension. Why is the protagonist there? What could happen?
 * **Example:** "A table grandly set for twelve people, but the food has been rotting for days."
 * This invites the speaker to describe details in Phase 1 (mold, silverware, silence) before answering "What happens now?" in Phase 2.

### 4. Conciseness and Precision
A practice text should be graspable in a maximum of two sentences. The storyteller shouldn't be reading a story; they should be forming associations.
**Senior Dev Tip:** When creating your own scenarios, use words with strong connotations (e.g., "abandoned," "pulsating," "icy," "magnificent"). These adjectives serve as anchors for your free-form narration.

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