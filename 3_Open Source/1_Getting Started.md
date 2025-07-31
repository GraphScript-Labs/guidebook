# How to get started with Open Source Projects

Every open source project has its own set of guidelines and processes for contributing. And so does GraphScript as well. To get started with contributing to GraphScript, you can follow these steps:

1. Fork the repository
2. Clone the fork to local machine
3. Create a new branch for your changes
4. Make your changes, commit and push them
5. Create a pull request to the original repository
6. Wait for review and feedback

## Before you start contributing

Before you start contributing to GraphScript, it is recommended to use the project or repository you want to contribute to. This will help you understand the project better and identify areas where you can contribute.

Additionally, you can check the issues section of the repository to see if there are any open issues that you can work on. If you find an issue that you want to work on, you can comment on the issue to let the maintainers know that you are working on it.

It'll be better if you start from small issues or features, and gradually work your way up to larger contributions. This will help you get familiar with the codebase and the contribution process.

## Forking the repository

To contribute to GraphScript, you need to fork the repository. This creates a copy of the repository under your GitHub account, allowing you to make changes without affecting the original project.

You can fork the repository by clicking on the "Fork" button on the top right corner of the repository page on GitHub.

This will create a copy of the repository under your account, allowing you to make changes without affecting the original project.

## Cloning the forked repository

Once you have forked the repository, you need to clone it to your local machine. This allows you to work on the code locally and push your changes back to your forked repository.

Check the [GitHub documentation](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) for more information on how to clone a repository.

## Creating a new branch

Before making any changes, it is a good practice to create a new branch for your changes. This helps keep your work organized and makes it easier to manage multiple contributions.

It is also suggested to update your forked repository with the latest changes from the original repository before creating a new branch. This ensures that your changes are based on the most recent code.

You can create a new branch using the following command in your terminal:

```bash
git checkout -b <branch-name>
```

> Please also check the Branch Naming Conventions page for more information on how to name your branches.

And after updating your forked repository, to update your local branch with the latest changes from the original repository, you can use:

```bash
git pull origin main
```

Overall command:

```bash
git checkout main
git pull origin main
git checkout -b <branch-name>
```

## Making changes, committing and pushing

Once you have created a new branch, you can start making changes to the code. After making your changes, you need to commit them to your local branch.

You can commit your changes using the following command:

```bash
git add .
git commit -m "Your commit message"
```

After committing your changes, you need to push them to your forked repository on GitHub. You can do this using the following command:

```bash
git push origin <branch-name>
```

## Creating a pull request

Check the [GitHub documentation](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/creating-a-pull-request) for more information on how to create a pull request.

Once you have pushed your changes to your forked repository, you can create a pull request to the original repository. This allows the maintainers of the original project to review your changes and merge them into the main codebase.

In case there might be any issues with your pull request, the maintainers will comment on it and you can make the necessary changes. Once the changes are made, you can push them to your forked repository and the pull request will be updated automatically.

## Waiting for review and feedback

After creating a pull request, you need to wait for the maintainers to review your changes. They may provide feedback or request changes before merging your pull request.

You can check the status of your pull request on the GitHub page of the original repository. If there are any issues, you can address them and push the changes to your forked repository.

