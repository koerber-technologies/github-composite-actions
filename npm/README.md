# npm

> Use this action for installing dependencies with npm and caching for 
> `node_modules`.

This action installs all necessary dependencies based on the `package.json`
file using [npm](https://npmjs.com). It will also cache the
`node_modules` folder.

## Used Actions

- [actions/checkout@v3](https://github.com/actions/checkout)
- [actions/cache@v3](https://github.com/actions/cache)

## Usage

Add the following snippet to your workflow.

```yaml
- name: Install dependencies with npm and cache node modules
  uses: koerber-technologies/github-composite-actions/npm@main
```
