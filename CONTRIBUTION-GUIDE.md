# Contribution Guidelines

In addition to
the [Encore Digital Group Contribution Terms](https://github.com/EncoreDigitalGroup/.github/blob/main/CODE-CONTRIBUTION-TERMS.md),
the following procedures are in place for contributing to this repository.

## Preparing your pull request branch

Once you have completed your feature or failing test, it's time to submit your Pull Request (PR) to the repository.
First, ensure that you commit your changes to a separate branch (avoid using main). To create a new branch,
you can use the git command:

```bash
git checkout -b my-feature
```

You can name your branch anything you want, but for future reference, it's helpful to use a descriptive name that
reflects your feature or failing test.

Next, commit your changes to your branch. You can use `git add .` to stage all changes and then
`git commit -m "Add my feature"` to commit all changes with a descriptive commit message.

However, your branch is currently only available on your local machine. To create a Pull Request, you need to push your
branch to your forked repository using `git push`.

```bash
git push origin my-feature
```

## Submitting your pull request

We're almost there! Open your web browser and navigate to your forked repository (https://github.com/<
your-username>/<repository-name>). In the center of your screen, you will see a new notification: "my-feature had
recent pushes 1 minute ago" along with a button that says "Compare & pull request." Click the button to open the pull
request form.

In the form, provide a title that describes your pull request and then proceed to the description section. The text area
already contains a predefined template. Try to answer every question:

Review the contribution guide first at: https://github.com/EncoreDigitalGroup/.github/blob/main/CONTRIBUTION-GUIDE.md

1️⃣ Is this something that is wanted/needed? Did you create a discussion about it first?
Yes, you can find the discussion here: https://github.com/livewire/livewire/discussions/999999

2️⃣ Did you create a branch for your fix/feature? (Main branch PR's will be closed)
Yes, the branch is named `my-feature`

3️⃣ Does it contain multiple, unrelated changes? Please separate the PRs out.
No, the changes are only related to my feature.

4️⃣ Does it include tests? (Required)
Yes

5️⃣ Please include a thorough description (including small code snippets if possible) of the improvement and reasons why
it's useful.

These changes will improve memory usage. You can see the benchmark results here:

```bash
... imaginarily benchmark results live...
```

All set? Click on Create pull request 🚀 Congratulations! You've successfully created your first contribution 🎉

The maintainers will review your PR and may provide feedback or request changes. Please make an effort to address any
feedback as soon as possible.

Thank you for contributing!

## Attribution

This contribution guide was adapted from the [Livewire Contribution Guide](https://livewire.laravel.com/docs/contribution-guide).