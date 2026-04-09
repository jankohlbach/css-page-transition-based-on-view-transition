# CSS view-transition based page transitions

Hacking CSS here a bit, but I wanted to make this work.
Usually, CSS view-transitions are there to morph elements from one state or page to another.
Often though, page transitions are completely separate elements and effects like curtains that cover the viewport or similar.
With this approach, I found a way to make this work purely with CSS animations, the JS needed is only to time things, send events after finishing etc.

## Setup

Make sure to install the dependencies:

```bash
yarn install
```

## Development Server

Start the development server on http://localhost:4321

```bash
yarn dev
```

## Production

Build the application for production:

```bash
yarn build
```

Locally preview production build:

```bash
yarn preview
```
