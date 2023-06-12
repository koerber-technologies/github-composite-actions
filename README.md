# GitHub Composite Actions

Use these composite actions for avoiding redundant code in your workflow file.
You can reference the `action.yaml` files in your workflow like this:

```yaml
- name: Checkout repository, cache node_modules and install dependencies
  uses: koerber-technologies/github-composite-actions/yarn@develop
```

Checking out the repository is a standard behaviour of the composite actions.

- List github actions website
