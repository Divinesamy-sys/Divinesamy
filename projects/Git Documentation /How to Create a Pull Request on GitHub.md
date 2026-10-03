
# How to Create a Pull Request on GitHub

## Overview

A **pull request (PR)** is a GitHub feature that allows someone to propose changes to a repository and request that another person review them.

Pull requests are commonly used for:

* Code changes
* Documentation updates
* Bug fixes
* New features
* Content improvements

For technical writers, pull requests are particularly useful when documentation changes need to be reviewed by developers, product managers, or other writers before publication.

## Prerequisites

Before creating a pull request, make sure you have:

* A GitHub account
* Access to the repository
* A Git branch containing your changes
* Changes that have been committed and pushed to GitHub
* A basic understanding of Git

## Workflow Overview

A typical pull request workflow looks like this:

**Create branch → Make changes → Commit changes → Push branch → Open pull request → Review → Merge**

## Step 1: Create a Branch

Create a separate branch for your changes instead of modifying the main branch directly.

For example:

```bash
git checkout -b update-installation-guide
```

The branch name should clearly describe the purpose of the change.

## Step 2: Make Your Changes

Edit the relevant files.

For example, you might update:

```text
docs/installation.md
```

Add the new information, correct errors, or improve the existing instructions.

## Step 3: Review Your Changes

Before committing your work, check the changes carefully.

You can use:

```bash
git diff
```

Look for:

* Incorrect information
* Formatting problems
* Broken links
* Spelling or grammar errors
* Unintended changes
* Missing steps

## Step 4: Commit the Changes

Stage the files:

```bash
git add docs/installation.md
```

Then create a commit:

```bash
git commit -m "Update installation guide"
```

A good commit message briefly describes what changed.

## Step 5: Push the Branch

Push your branch to GitHub:

```bash
git push -u origin update-installation-guide
```

Your branch should now be available in the remote repository.

## Step 6: Open the Pull Request

Open the repository on GitHub.

GitHub may display an option to create a pull request for your recently pushed branch.

Select the option to open a new pull request.

## Step 7: Add a Title and Description

Give the pull request a clear title.

For example:

```text
Update installation guide
```

In the description, explain:

* What changed
* Why the change was made
* What reviewers should check
* Any relevant testing or verification

For example:

```text
## Summary

- Updated the installation steps
- Added the required system prerequisites
- Clarified the verification step

## Verification

- Tested the installation procedure
- Confirmed that all referenced files are available
```

## Step 8: Review the Pull Request

Before submitting it for review, check:

* Changed files
* Pull request title
* Description
* Commit history
* Automated checks, if configured

Make sure the changes are limited to the intended scope.

## Step 9: Request a Review

Depending on the repository permissions and workflow, you can request a review from another contributor.

The reviewer can comment on specific changes and request modifications.

## Step 10: Address Feedback

If the reviewer requests changes, update your branch.

For example:

```bash
git add .
git commit -m "Address review feedback"
git push
```

The new commit will automatically appear in the existing pull request.

You do not normally need to create a second pull request for the same branch.

## Step 11: Merge the Pull Request

Once the changes have been reviewed and approved, an authorized contributor can merge the pull request according to the repository's workflow.

After the merge, the changes become part of the target branch.

## Expected Result

After a successful merge:

```text
Feature branch
      ↓
Pull request
      ↓
Review
      ↓
Approval
      ↓
Merge
      ↓
Main branch updated
```

The proposed changes are now part of the repository's target branch.

## Troubleshooting

### The Pull Request Option Does Not Appear

Make sure your branch has been pushed to GitHub and contains changes that differ from the target branch.

### GitHub Shows Merge Conflicts

A merge conflict means that Git cannot automatically combine changes from different branches.

You may need to update your branch, resolve the conflicting files, and push the resolved changes.

### My Changes Are Not Appearing in the Pull Request

Confirm that:

* You committed the changes.
* You pushed the correct branch.
* The pull request uses the correct source branch.
* The files were actually modified.

### A Reviewer's Changes Were Requested

Read the review comments carefully, make the requested updates, commit them, and push the changes to the same branch.

The existing pull request will update automatically.

## Best Practices for Documentation Pull Requests

Technical writers can use pull requests to create a clear review process for documentation.

Before opening a PR:

* Use a descriptive branch name.
* Keep the change focused.
* Review your own changes first.
* Check links and formatting.
* Use a meaningful commit message.
* Clearly explain what changed.
* Mention how the documentation was verified.

For larger documentation projects, a pull request template can also help reviewers consistently check important requirements.

## Key Takeaways

* A pull request proposes changes for review.
* Changes are usually developed on a separate branch.
* The branch is pushed to GitHub before opening the PR.
* Reviewers can comment on and request changes.
* Additional commits can be added to the same pull request.
* Once approved, the changes can be merged into the target branch.
* Pull requests provide a structured workflow for reviewing both code and documentation.
