# CodeSee Review Maps

Open CodeSee Review Maps without leaving VS Code!

Review Maps create diagrams from pull requests and help you gain a better understanding of the code you're reviewing.

![Review Map demo](https://s3.us-east-2.amazonaws.com/maps.codesee.io/extension_preview.gif)

## Getting started

These steps are available [in our docs as well](https://docs.codesee.io/docs/review-maps-for-visual-studio-code).

1. Install the extension by searching for "CodeSee" within VS Code or [downloading it from the marketplace](https://marketplace.visualstudio.com/items?itemName=codesee.maps)
2. Install the [GitHub Pull Requests and Issues extension](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)
3. Open your desired GitHub repository in VS Code
4. Check out the branch you'd like to review
5. Log in to your CodeSee account when prompted by the sidebar
6. Bring up the command palette using `Ctrl/Cmd` + `Shift` + `P`
7. Choose `CodeSee: Open Review Map` to review changes on your branch

## Usage

When you're browsing a pull request locally, open the command palette with `Ctrl/Cmd` + `Shift` + `P` and choose `CodeSee: Open Review Map`. This will open a visual representation of your pull request.

- use your mouse to drag the map around
- use `Ctrl` + your mouse wheel to zoom in and out
- click on a file to view its dependencies and tune out the rest
- double-click on a file to open a diff view
- right-click on a file to mark it as viewed -- this will be reflected in GitHub

### GitHub Pull Request sidebar

When you're viewing a file inside the sidebar of the GitHub Pull Request & Issues extensions, you can create a Review Map of those changes without checking out the branch.

![Review Map within the GitHub extension](https://s3.us-east-2.amazonaws.com/maps.codesee.io/github_extension.gif)

## Requirements

- [a CodeSee account](https://app.codesee.io/)
- CodeSee Maps [must be installed in your repository](https://docs.codesee.io/en/latest/installation/)
- the [GitHub Pull Request extension](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)

## Copyright

Copyright (C) 2023 CodeSee
