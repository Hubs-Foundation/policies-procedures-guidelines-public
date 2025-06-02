# Pull Request (PR) Review Policy/Guidelines
_For Hubs Foundation (Volunteer) Staff_

## Pre-review

- Check that all the required sections in the PR description have been filled out satisfactorily - ask the submitter to update it, if needed, or ask them to clarify anything you don't understand.
    - If the changes require a pre-agreed-upon [proposal](new-technology-or-big-feature-proposal-guidelines.md), but no proposal has been linked, ask the submitter to add the link to the proposal or to please open a proposal and link the pull request to it.  Mark the PR as a draft.
- Add any missing links to related issues/PRs in a comment.

## Review (started once everything passes pre-review)

Visual:
- Look over each line that's changed.
    - If there are unrelated changes included in the PR, ask the submitter to split them off into a separate PR.
    - Check for bugs, or improvements that could be made.
    - If the changes don't follow the style guidelines we're following, link to the guidelines and ask the submitter to update.
    - Make sure the changes are clear/well organized and that any gotchas (or convoluted bits) are commented at the appropriate place.
- Make sure the changes integrate well into our current systems and they aren't a kludge/spaghetti code/etc..
- Make sure the changes are in line with our [vision and guiding principles](vision-and-guiding-principles.md).
- Check the commits/commit messages for insights and to see whether they adhere to our guidelines.
- If needed, provide guidance to the submitter on what should be changed and mark the PR with "Request changes".
- If the PR description no longer fits the PR, ask the submitter to update it.

QA (Quality Assurance):
- Pull the changes from a PR to a local branch.  See [Getting PR Branches Locally]().
- Build/run the changes and verify that the PR does what it purports to. (It is often beneficial to combine this with the visual review to aid in understanding the PR)
    - You can't always rely on just following the testing instructions in the PR, so make sure you double check with the actual submitted changes to make sure you test everything that needs testing.
- Spend a little time trying to make the PR break.
- Keep your eyes open for breakages in related things that this PR could have caused.
- If this is a modification to an existing feature/doc (or a port of a feature/doc), check the original functionality/doc to make sure the changes have parity or are an improvement, and there are no unforeseen negative side effects.
- Communicate to the submitter any issues you find and mark the PR with "Request changes".

## Merging/Rejection

- Once the pre-review and review have been completed and all issues have been addressed and verified, mark the PR as approved.
- Once all reviewers have marked the PR as approved, merge the PR (optionally squashing to one commit, if it is deemed beneficial and the commits don't follow our commit guidelines).
- Alternatively, if the PR has been discussed and it has been agreed that we should reject the PR, close the PR with a comment explaining why the PR has been rejected.
- If the PR is merged, close any open issues that need to be closed, but weren't auto-closed.

Note: a healthy discussion between reviewer and submitter is encouraged, feel free to push back on issues, but be ready to yield if the other party has a good point.
