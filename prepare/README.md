# Prepare

This action checks out the repository and installs a specific Node.js 
version on the runner OS.

## Used Actions

- [actions/checkout][1]
- [actions/setup-node][2]

## Usage

Add the following snippet to your workflow.

```yaml
- name: Checkout repository and set up Node.js
  uses: KTE-Future-Farming/github-composite-actions/prepare@v1
```

Keep in mind to specify a version tag for your action. It could be either a 
tag like `prepare@v1` or a full commit SHA like 
`prepare@b4ffde65f46336ab88eb53be808477a3936bae11`.

More information on versioning GitHub Actions can be found [here][3].

[1]: https://github.com/actions/checkout
[2]: https://github.com/actions/setup-node
[3]: https://devopsjournal.io/blog/2022/10/19/How-GitHub-Actions-versioning-works
