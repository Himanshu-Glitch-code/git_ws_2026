# Git Troubleshooting

## Git Is Not Recognised

Check whether Git is installed:

```bash
git --version
```

If it is not recognised, install Git and restart your terminal.

## Nothing Appears in `git status`

Check whether you saved your file and are in the correct repository.

## I Cannot Push My Branch

Check that you have the required permissions and that your remote is configured correctly:

```bash
git remote -v
git status
```

If you are contributing to someone else's repository, you may need to fork it first.

## I Committed the Wrong File

Do not panic. Ask a mentor for help before running commands that rewrite commit history.

## I Have a Merge Conflict

Open the affected file, inspect the conflicting sections, and decide which changes should remain. Ask a mentor if you are unsure.
