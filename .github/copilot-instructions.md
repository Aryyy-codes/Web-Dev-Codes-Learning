# Copilot Instructions for Web Dev Learning Repository

## Repository Overview

This is a **learning-focused repository** for HTML and CSS fundamentals. It's organized as a progressive tutorial series with numbered lessons (03–29) that build upon each other, covering foundational web development concepts.

## Directory Structure & Conventions

### Lesson Organization
- **Numbered directories** (e.g., `03 Skeleton`, `04 link`, `05 Image, table, and List`): Each directory represents a single lesson or topic
- **Sequential progression**: Numbers indicate the intended learning order (03 → 04 → 05, etc.)
- **Topic-focused**: Directory names describe the concept being taught

### File Structure Within Lessons
Each lesson directory typically contains:
- **index.html**: Main demonstration file for the lesson
- **hw.html** (optional): Homework or practice exercise file
- **style.css** (optional): External stylesheet used to demonstrate CSS application
- **Info.txt** (optional): Explanatory notes about the topic (e.g., element lists, concepts)
- **Other HTML files**: Alternative implementations or variations (e.g., `delete.html`, `AI made Index.html`)

### Example Directory Structure
```
14 CSS Intro/
├── index.html
├── style.css (if CSS is demonstrated)

20 Homework/
├── index.html (homework problem)
├── solution.html (solved version)

23 CSS Display Property/
├── index.html
```

## Key Conventions

### HTML Files
- **Boilerplate format**: HTML files typically use a standard skeleton:
  ```html
  <!DOCTYPE html>
  <html lang="en">
  <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>Document</title>
  </head>
  <body>
      <!-- Content here -->
  </body>
  </html>
  ```
- **Minimal styling**: Inline `<style>` tags or external CSS are preferred over pre-existing classes for teaching clarity
- **No build process**: Files are meant to be opened directly in a browser (Live Server/Live Preview)

### Naming Conventions
- **HTML files**: Use lowercase descriptive names (`index.html`, `hw.html`, `question.html`, `Solution.html`)
- **CSS files**: `style.css` is the standard name for external stylesheets
- **Topics in directory names**: Use descriptive, readable names with capitalized words separated by spaces (e.g., `CSS Position`, `Semantic Tags`)

### CSS Demonstrations
- When demonstrating CSS concepts, use **external stylesheets** (`style.css`) to show proper separation of concerns
- Include comments explaining which HTML elements are being styled
- Keep examples focused on a single concept or closely related concepts

## Development Workflow

### Viewing Content
- **No build/test/lint process**: Files are intended to be viewed directly in a browser
- **Live Preview**: VS Code Live Preview is configured (see `.vscode/settings.json`)
- Simply open HTML files in a browser to see the rendered output

### Adding New Lessons
1. Create a new numbered directory following the pattern: `[next-number] [Topic Name]`
2. Add an `index.html` file with the standard boilerplate
3. Include relevant content and optionally external CSS if demonstrating styling concepts
4. Add an `Info.txt` file if providing explanatory context is helpful
5. If creating practice exercises, add `hw.html` or follow the pattern of existing homework directories

### Modifying Existing Lessons
- Keep HTML files standalone and self-contained (no cross-file dependencies)
- Update Info.txt files to clarify concepts if needed
- Preserve existing solutions; use alternative filenames if creating variations (e.g., `AI made Index.html`)

## Content Coverage by Lesson Range

### HTML Fundamentals (03–13)
- 03: HTML Skeleton/Boilerplate
- 04: Links
- 05: Images, Tables, Lists
- 06: SEO & Core Web Vitals
- 07: Forms & Input Tags
- 08: Inline & Block Elements
- 09: IDs & Classes
- 10: Video, Audio & Media
- 11: Semantic HTML Tags
- 12: HTML Media Players
- 13: Entities, Code Tags & More

### CSS Fundamentals (14–29)
- 14: CSS Introduction
- 15: CSS Application Methods (Inline, Internal, External)
- 17: CSS Selectors
- 18: CSS Box Model
- 19: Fonts, Text & Color
- 20: Homework/Practice
- 21: Color, Specificity & Cascade
- 22: CSS Sizing Units
- 23: CSS Display Property
- 24: Shadows & Outlines
- 25: Styling Lists
- 26: CSS Overflow Property
- 27: Tutorial Solutions
- 28: CSS Position
- 29: (In progress)

## Notes for Contributors

- **Learning focus**: Prioritize clarity and pedagogical value over production-quality code
- **Self-contained lessons**: Each lesson should be understandable independently, though they build sequentially
- **Practical examples**: Include working examples that render correctly in modern browsers
- **Documentation**: Use Info.txt or inline comments to explain concepts, especially for complex topics
