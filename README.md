# Minimax + Alpha-Beta Pruning Simulator

## Direct Viewing

Open the live simulator here:

https://lifeknife10a.github.io/minimax-alpha-beta-simulator/

This is a frontend-only React project made with Vite. It lets you create and
edit a game tree, then run Minimax or Alpha-Beta Pruning with visual steps.

## Folder Structure

```text
poster-app/
  index.html
  package.json
  src/
    App.jsx
    App.css
    index.jsx
    index.css
    treeTools.js
```

## Main Features

- Generate a sample depth-3 game tree with 8 leaf nodes
- Create a tree manually by adding and removing nodes
- Edit node labels and leaf utility values
- Run normal Minimax
- Run Alpha-Beta Pruning
- Step forward through either algorithm
- Reset the simulation without deleting the tree
- Show node name, type, minimax value, alpha, beta, visited state, and pruned state
- Highlight the current node, pruned branches, final selected path, and root answer
- Use a floating Step Forward button directly on the graph
- Use Focus Graph mode so only the graph and floating controls are visible while stepping
- Open Exam Mode as a sliding drawer instead of a fixed side panel
- Toggle dark mode
- Autosave the tree and current state in the browser
- Warn before leaving the page when Safe Leave is enabled
- Show an execution log and simple Exam Mode explanation for each step

## Run Locally

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the local URL shown by Vite. It is usually:

```text
http://localhost:5173/
```

Build for production:

```bash
npm run build
```

## Dependencies

- React
- React DOM
- Vite

No backend is required.
