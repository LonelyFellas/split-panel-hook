# split-panel-hook
Split-Pane React component, can be nested or split vertically or horizontally!

## Installing
```bash
npm install @darwish/split-pane-hook

# or if you use yarn

yarn add @darwish/split-pane-hook
```

## Example Usage
```tsx
<Split split="vertical" minSize={50} defaultSize={100}>
  <div />
  <div />
</Split>
```
```tsx
<Split split="vertical" minSize={50}>
  <div />
  <Split.Pane split="horizontal">
    <div />
    <div />
  </Split.Pane>
</Split>
```