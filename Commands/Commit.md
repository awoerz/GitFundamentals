# git commit

The comamand `git commit` will take all tracked changes (items added with [git add](./Add.md)) and package them up in what is callled a commit.

Commits come with commit messages that are required for each commit. You add a message to a commit command by using the `-m` flag followed by a message in quotes.

A commit message _can_ bee anything, but best practices dictates that you should use that message to indicate the changes included in the commit.

For example, if we have a n application we're working on where we just build out the ability to register new accounts, then you might have some variation of the following:

```
git add .
git commit -m "Added restier functionality"
```

Then when view the history of a git repository, you can pinpoint where the registration functionality was added.

## Resources

- [Git Copmmit Documentation](https://git-scm.com/docs/git-commit)

---

[Back to home](../README.md)
