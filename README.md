# Sign-up Form

A responsive sign-up form, built as my solution to [The Odin Project's Sign-up Form project](https://www.theodinproject.com/lessons/intermediate-html-and-css-sign-up-form).

## Tech stack

- HTML5
- CSS3
- TypeScript, compiled to ES modules with `tsc`

## Getting started

Install dependencies and compile the TypeScript sources:

```bash
npm install
npm run build   # compile src/ into dist/
```

For development, recompile on change:

```bash
npm run watch
```

## Project structure

```text
.
├── index.html        # Page entry point
├── css/
│   ├── index.css     # Stylesheet entry point
│   ├── tokens.css    # Design tokens
│   ├── elements.css  # Default styles for bare HTML elements
│   └── utilities.css # Utility classes for color, typography, box, and layout
├── src/
│   └── index.ts      # TypeScript entry point
├── dist/
├── tsconfig.json
└── package.json
```

## Status

Scaffolded from a hand-authored HTML/CSS/TypeScript starter. The form markup and validation have not been implemented yet.

## License

ISC
