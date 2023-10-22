# Fall 2023 Basic Review Outline

## Part 1 - Dev Tools and Setup

### Terminal

- ZSH and `ohmyz.sh`
- Home folder `~`
- `mkdir`, `cd`, `ls -la`
- `touch` and `code`
- Environment variables
- `$PATH`
- NodeJS and NPM

### MacOS

- Copy, Cut, and Paste
- `⌘` + Space: spotlight search
- Force Quit, Keep in Dock
- Finder: Go to Folder, adding Home Folder to sidebar
- Hidden files: `⌘` + `⇧` + `.`

```bash
defaults write com.apple.Finder AppleShowAllFiles true
killall Finder
```

- File locations
- Naming files - lowercase, no spaces

### VSCode

- extensions
- Live Share from project folder
- Opening projects
- keyboard shortcuts

### Chrome

- Developers use Chrome, not Safari

### Git

- `init`, `add`, `commit`
- `status` and `log`
- `git remote add origin <url>`
- `git push origin main`
- `git pull`
- git branches

## Part 2 - JavaScript

### Variables

- scope
- `let` vs. `const`
- hoisting
- primitive vs Object datatypes
- truthy and falsy

### Chrome Dev Tools

- console
- network
- elements
- toggle device mode
-

### Functions

- declarations vs expressions
- IIFE
- regular vs arrow
- return keyword
- function parameters | arguments
- default values
- callbacks

### Objects

- Object literals
- dot notation vs. square bracket syntax
- properties and methods
- adding, merging, deleting properties

### Arrays

- Array literals
- `push`, `pop`, `shift`, `unshift`
- `slice`, `splice`, `concat`, `sort`
- `foreach`, `map`, `filter`

### Namespaces and Modules

- Namespace objects
- type="module" and defer
- `import` and `export`

## Part 3 - Styles

- CSS Box Model
- `display`: `block`, `none`, `inline`, `inline-block`, `flex`, ...
- Classes vs ids
- Multiple classes
- pseudo-classes and -elements
- Specificity
- Chrome Dev Tools
- Typographic Hierarchy
- Grids, spacing, and rhythm
- Fonts, [Google fonts](https://fonts.google.com/)
- Flexbox

```css
.container {
  display: flex;
  flex-direction: row; /* column, *-reverse */
  flex-wrap: nowrap;
  justify-content: flex-start; /* flex-start flex-end center space-around space-evenly space-between */
  align-items: stretch;
  gap: 1rem 1rem;
}
.item {
  /* flex: grow shrink basis; (0 1 auto default) */
  flex-basis: auto;
  flex-grow: 1;
  flex-shrink: 1;
  /* order: 1 */
  /* width, height */
}
```
