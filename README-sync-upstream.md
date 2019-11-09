Merging an upstream repository into your fork:

1. Change the current working directory to your local project.

2. Check out the branch you wish to merge to. Usually, you will merge into `master`.

```bash
git checkout master
```

3. Pull the desired branch from the upstream repository. This method will retain the commit history without modification.

```bash
git pull git@github.com:zedshaw/learn-more-python-the-hard-way-solutions.git master
```

4. If there are conflicts, resolve them.

5. Commit the merge (if needed):

```bash
gcm "Merge from upstream"
```

6. Review the changes and ensure they are satisfactory.

7. Push the merge to your GitHub repository.

```bash
git push origin master
```