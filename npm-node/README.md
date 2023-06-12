# npm-node

> Use this action for installing dependencies and Node.js with npm and for
> caching `node_modules`.

This action installs all necessary dependencies based on the `package.json`
file using [npm](https://npmjs.com). It will also
install [Node.js](https://nodejs.org/en) and cache the `node_modules` folder.

## Used Actions

- [actions/checkout@v3](https://github.com/actions/checkout)
- [actions/setup-node@v3](https://github.com/actions/setup-node)

## Usage

Add the following snippet to your workflow.

```yaml
- name: Install dependencies and Node.js with npm and cache node modules
  uses: koerber-technologies/github-composite-actions/npm-node@main
```
