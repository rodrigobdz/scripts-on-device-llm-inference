# How to contribute

Here are some important resources:

- [How to Write a Git Commit Message](https://cbea.ms/git-commit/)
- [Addressing Merge Conflicts](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts)

## Conventions

<!-- markdownlint-disable MD033 -->
<details><summary>Project Management</summary>
<p>

We use [GitHub Issues](https://github.com/rodrigobdz/hugging-face-voice-assistant/issues) with [labels](https://github.com/rodrigobdz/hugging-face-voice-assistant/issues/labels) to track issues and tasks.

</p>
</details>

<!-- markdownlint-disable MD033 -->
<details><summary>Git conventions</summary>
<p>

We follow the [Feature Branch Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow) and [make atomic commits](https://dev.to/samuelfaure/how-atomic-git-commits-dramatically-increased-my-productivity-and-will-increase-yours-too-4a84) and atomic PRs.

</p>
</details>

<!-- markdownlint-disable MD033 -->
<details><summary>Submitting changes</summary>
<p>

We strive to write meaningful and clear commit messages.

> Write a clear log message for commits. One-line messages are fine for small changes, but bigger changes should look like this ([source](https://github.com/opengovernment/opengovernment/blob/4dc9499f735b680c124f04100b1ab19146242a13/CONTRIBUTING.md)):

```sh
git commit --gpg-sign --message "Scope: A brief summary of the commit
>
> A paragraph describing what changed, why it was necessary, and its impact."
```

The example above loosely follows the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification.

</p>
</details>

<!-- markdownlint-disable MD033 -->
<details><summary>Coding conventions</summary>
<p>

- Shell scripts: [Google Styleguide](https://google.github.io/styleguide/shellguide.html)
- Python: [black](https://black.readthedocs.io/en/stable/), [Pydantic](https://docs.pydantic.dev/latest/)

</p>
</details>

## Getting Started

### Requirements

- `pre-commit`

  ```sh
  # Install pre-commit binary
  brew install pre-commit

  # Install pre-commit hooks
  pre-commit install
  ```

### Development Environment

We recommend the following development environment:

- [VSCode](https://code.visualstudio.com)

<!-- markdownlint-disable MD033 -->
<details><summary>VSCode extensions</summary>
<p>

- [Ruff](https://marketplace.visualstudio.com/items?itemName=charliermarsh.ruff)
- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

</p>
</details>
