# [DRAFT] Pull Request (PR) Guidelines
* PRs changing documentation or media require one approving review (from anywhere).
* PRs changing code require one approving reviews (from anywhere) and an approving review from the Quality Control team (currently Imaginer and YvonneG), or if one other reviewers aren’t available in a reasonable time frame, an approving review from the Quality Control team will suffice.
* PRs that change the code must have an approved accompanying PR for updating the documentation, if the changes require a documentation update, before the code PR can be approved.
* Big features/changes need to be approved by a team lead and ideally should be made as a proposal before a PR is started.  See the proposal guidelines.
* Major refactoring of existing systems to use different technologies/frameworks must be made as a proposal before a PR is started.  See the proposal guidelines.

## Revision of PRs

* Commits may be amended and force-pushed only if
  * the intended functionality of the commit is unchanged, and
  * there are no outstanding comments/conversations on the file(s) involved that are not clearly resolved by the changes
* Otherwise, another commit should be added to the PR

## Closing PRs: Merging, Squashing and Rebasing

* Merge conflicts must be resolved before the commit is closed
* Merge commits are always acceptable
* Squash merge may be appropriate if a single commit would be an acceptable unit to revert.
* A PR may not be closed by Rebasing if that would require a merge conflict to be resolved

## No knowledgeable reviewer
If no knowledgeable reviewers are available for a review within a reasonable time frame PRs can still be merged via the following procedure:
* PRs from first time or non-regular contributors, or contributors who don’t know the area very well
  - Unreviewed PRs can only be merged during the [alpha stage](/release-schedule.md#alpha-stage).
  - The PR must be discussed first with the Programming team.
  - The Programming team must agree with the general idea of the PR and feel the contributor is capable of implementing it and committed to maintaining it at least for the short term.
  - The PR must be prefixed with `[UNREVIEWED]` for easy reversion if necessary.
  - _PRs could be squashed to a minimal number of commits for easy reversion if necessary? Unsure_
  - The PR is only reviewed for basic compatibility (style, tests pass, docs are present, etc.)
* PRs from regular contributors who know the area well
  - The PR is only reviewed for basic compatibility (style, tests pass, docs are present, etc.)
    - If there are no reviewers around to even review for basic compatibility and the contributor has commit rights, then the PR may be merged under their own review.
