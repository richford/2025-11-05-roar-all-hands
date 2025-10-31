# All-Hands Presentation

Presentation on team development stages and process improvements.

## Setup

Install dependencies:

```bash
npm install
```

## Development

Start the presentation in development mode:

```bash
npm run dev
```

This will open the presentation in your browser with hot-reload enabled.

## Presenter Mode

To view presenter notes while presenting:

1. Start the dev server (`npm run dev`)
2. Press `p` to enter presenter mode
3. This will open a separate window with:
   - Current slide
   - Next slide preview
   - Comprehensive presenter notes
   - Timer

The presenter window stays in sync with the main presentation window.

## Navigation

- Use arrow keys or space to navigate slides
- Press `f` for fullscreen
- Press `o` for overview mode
- Press `d` for dark mode toggle
- Press `p` for presenter mode (with notes)

## Presenter Notes

Each slide includes comprehensive presenter notes that provide:

- **Talking points** - Specific language and key messages to convey
- **Timing cues** - When to pause, when to reveal click animations
- **Detailed explanations** - Context and examples for each concept
- **Transitions** - How to smoothly move between topics
- **Discussion facilitation** - Questions and prompts for the Q&A section

The notes are visible only in presenter mode (press `p`) and won't appear in exported slides or the main presentation view.

## Building

Build the presentation for production:

```bash
npm run build
```

## Exporting

Export to PDF:

```bash
npm run export
```

## Editing

Edit `slides.md` to modify the presentation content. Slidev uses markdown with special frontmatter and directives:

- `---` separates slides
- `layout: center` and other layout options control slide appearance
- `<v-click>` creates click-to-reveal animations
- `<v-clicks>` wraps multiple items for sequential reveal
- `<!-- PRESENTER NOTES -->` adds notes visible only in presenter mode

## Learn More

- [Slidev Documentation](https://sli.dev/)
- [Tuckman's Stages of Group Development](https://en.wikipedia.org/wiki/Tuckman%27s_stages_of_group_development)
