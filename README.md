# Yarn Workspaces with TypeScript References Example

Everytime I try to set this up it takes a few tries to get right. This repo is a simple example of it working.

The `main` package depends on `shared`. Running `yarn build` in `main` will first build `shared`.

## Testing

- Clone repo
- Install deps - `yarn`
- Navigate to main package - `cd packages/main`
- Build - `yarn build`
- See that a dist folder has also been created in `packages/shared`
- Run built code - `node dist/index.js`
