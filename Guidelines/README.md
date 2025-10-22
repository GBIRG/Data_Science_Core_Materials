# Contribution Instructions

This README provides instructions making contributions to the GBIRG data science core repository

## Cloning an existing repository

Considerations:

```text
These instructions will add an external repo, disconnect that addition from the original and push to the GBIRG collection
```

1.  Clone the entire repo to your local system

2.  Navigate to the appropriate directory

3.  Clone the external repo

4.  Enter the cloned directory and remove the .git directory to detatch from the original

```{bash}
rm -rf .git
```
5. Return to the repo directory and push to github

```{bash}
cd ../../ # precise location will depend of addition you are making
git add path/to/addition
git commit -m "Info about addition"
git push
```
