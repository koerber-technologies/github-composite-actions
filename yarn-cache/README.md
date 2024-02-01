# Yarn Cache

This action caches your yarn dependencies.

## Used Actions

- [actions/cache][1]

## Usage

Add the following snippet to your workflow.

```yaml
- name: Cache yarn dependencies
  uses: KTE-Future-Farming/github-composite-actions/yarn-cache@v1
```

Keep in mind to specify a version tag for your action. It could be either a
tag like `yarn-cache@v1` or a full commit SHA like
`yarn-cache@b4ffde65f46336ab88eb53be808477a3936bae11`.

More information on versioning GitHub Actions can be found [here][2].

[1]: https://github.com/actions/cache
[2]: https://devopsjournal.io/blog/2022/10/19/How-GitHub-Actions-versioning-works
