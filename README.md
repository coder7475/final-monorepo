# Final Monorepo

## Setting up the Monorepo Structure

The structure of a monorepo can vary depending on its intended use. There are generally two main types:

## Package-Centric Repositories

- Used for developing and publishing reusable packages
- Common in open source projects (Angular, React, Vue, etc.)
- Typically contains a `packages` folder
- Packages are published to public registries like NPM

## App-Centric Repositories

- Used for developing applications and products
- Common in enterprise environments
- Contains:
  - `apps` folder for buildable/deployable applications
  - `packages` or `libs` folder for shared libraries
  - Libraries can optionally be published to public registries

For this project, we'll use the app-centric approach to demonstrate how an application can consume packages from within the monorepo.

### References

1. https://dev.to/vinomanick/create-a-monorepo-using-pnpm-workspace-1ebn
2. https://nx.dev/blog/setup-a-monorepo-with-pnpm-workspaces-and-speed-it-up-with-nx
