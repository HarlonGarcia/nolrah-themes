# Velvet Code Themes

Three restrained, Dracula-inspired dark themes for VS Code.

- **Obsidian** — deepest background, muted purple accents.
- **Dusk** — balanced dark-purple background.
- **Graphite** — neutral charcoal background, minimal purple.

Designed for TypeScript, TSX/React, JavaScript, Node.js, Go, PHP, Markdown, JSON, YAML, Makefiles, terminals and logs. TextMate and semantic tokens are supported.

## Install locally

1. Open this folder in VS Code.
2. Press **F5** to launch an Extension Development Host, then select a theme using **Preferences: Color Theme**.
3. To package, install `@vscode/vsce` and run `npx @vscode/vsce package`. Update `publisher` in `package.json` before publishing.

For improved bracket distinction, use `editor.bracketPairColorization.enabled: true` in VS Code settings. Theme-specific bracket colors can be added later.

## Notes

Token colors depend on language grammar and semantic token provider; not every language exposes every token class. Review and tune colors with **Developer: Inspect Editor Tokens and Scopes**.

### v0.1.1
Slightly increased syntax color saturation across all three variants; editor backgrounds and UI colors are unchanged.

## v0.1.2

Refined JavaScript/TypeScript declaration scopes, JSX colors, function highlighting and more distinct yet restrained syntax colors.

## v0.2.0

Improved TextMate selectors and semantic token mappings for JS/TS/JSX, function declarations, component tags, properties and template interpolation.

For testing, select the theme in the Extension Development Host and run `Developer: Inspect Editor Tokens and Scopes` on a token to inspect its active color rule.

## v0.2.0

More vivid syntax palette inspired by Dracula, with brighter keywords, function calls, strings, JSX, types and punctuation. Backgrounds remain unchanged. Includes `.vscode/launch.json` for F5 debugging.
