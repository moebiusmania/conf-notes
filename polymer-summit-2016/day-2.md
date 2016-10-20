# Polymer Summit 2016 - Day 2

## What's New in Polymer Tools - Justin Fagnani

- Polymer tools are not specific for the library but they are tools for **Web Components**
- **PRPL** Push Render Pre-cache Lazy-load
- Polidev tool: to see which type of features cost the most.
- Polyperf tool: to analyse the performance of a component.
- How-to reduce the cost of an element:
  - Remove components that do something simple we can quickly replicate.
  - Move the creation of certain details for when its needed.
  - Use CSS instead of toggling classes via js.
  - Reduce the use of default values for the properties.
  - Defer work until after render. ```Polymer.renderStatus.afterNextRender()```.
- Polymer Analyzer
  - understand HTML, CSS, Javascript, JSON, TypeScript...
  - ```npm install polymer-analyzer```
- Polymer Import / Lazy load
  - supports HTML import and soon JS imports
  - importLazyGroup()
- Polymer Linter ```npm install polymer-lint my-rule```
- Packaging
  - no NPM yet :) but its on the roadmap
  - ```yarn install —flat``` is huge for Polymer development
- Bundling: new bundler in Polymer CLI
  - It can produce shards.
  - Produces a bundle with shared dependencies (customizable).
- ```polymer init``` supports custom components/application templates
- Polymer Build services can be imported inside custom workflows
- Polymer Editor Plugins
  - contextual autom completion (properties, methods,...)
  - open source
  - Polymer Editor Service, codebase for Plugin cross editor

## Related Codelabs

https://codelabs.developers.google.com/polymer-summit-2016
