# How to name branches for GraphScript Projects

When contributing to the GraphScript project, it is important to follow a consistent naming convention for branches. This helps maintain clarity and organization within the codebase, making it easier for contributors to understand the purpose of each branch.

## Branch Naming Conventions

```
gs/<repo-name>/<type>/short-description
```

## Components of the Branch Name

### Prefix

The branch name starts with `gs/`, which indicates that this is a GraphScript project branch. This prefix helps differentiate GraphScript branches from other projects or repositories.

### Repository Name

The next part of the branch name is `<repo-name>`, which specifies the repository you are contributing to. This could be one of the main repositories like `editor`, `launcher`, or `console`.

### Type of Change

The branch name includes a `<type>` to categorize the nature of the changes being made. This helps in understanding the purpose of the branch at a glance. The types can include:
- `feat`: For new features or enhancements.
- `fix`: For bug fixes.
- `no-code`: For changes that do not affect the functionality of the code, such as documentation updates or configuration changes.
- `chore`: For routine tasks and maintenance that do not fit into the other categories.
- `other`: For any other type of change that does not fit into the above categories.

### Short Description

Finally, the branch name ends with a `short-description`, which provides a brief summary of the changes being made. This should be concise yet descriptive enough to give an idea of the branch's purpose.

## Examples of Branch Names

- `gs/guidebook/no-code/update-contributing-guidelines`
- `gs/editor/fix/save-button-issue`
- `gs/launcher/feat/loading-screen-for-updates`

