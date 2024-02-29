# Migrating from React Table v7

## Notable Changes

- Full rewrite to TypeScript with types included in the base package
- Removal of plugin system to favor more inversion of control
- Vastly larger and improved API (and new features like pinning)
- Better controlled state management
- Better support for server-side operations
- Complete (but optional) data pipeline control
- Agnostic core with framework adapters for React, Solid, Svelte, Vue, and potentially more in the future
- New Dev Tools

## Migration

There are a fair amount of breaking changes (they're worth it, trust us!):

- Turns out that TypeScript makes your code **a lot** better/safer, but also usually requires breaking changes to architecture.
- Plugin system has been removed so plugins must be rewritten to wrap/compose the new functional API. Contact us if you need help!
- Column configuration options have changed, but only slightly.
- Table options are mostly the same, with some larger changes around optional state management/control and data pipeline control
- The `table` instance while similar in spirit to v7 has been reconfigured to be much faster.

## Installation

Install one of the following packages based on your framework of choice:

```bash
# Npm
npm install @rewikipx/simple-rewiki-tstacktable
```

<!-- USE THE FORCE LUKE -->
