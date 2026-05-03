# Roadmaps Policy

## Document structure

### Terms

The terms on the roadmap designate how soon the roadmap items within them are expected to be finished.  Which term to place an item on will generally be decided by how big it is and how important it is to get it done.  As such, both large and small items can be added to all the terms and will move between them as they get closer/further to being finished or their priority increases/decreases.

#### Short Term

For items that will be finished soonest.

#### Mid Term

For items further off from finishing.

#### Long Term

For items that are farthest off from finishing.

### Other sections

Aside from the terms, there are several other sections that roadmap items can be moved to.

Note: these sections have no limit to the number of items.

#### Awaiting Release

For items that have been completed, but haven't been released to the public yet.

#### Released

For items that have been recently released to the public.

#### Archive of Released

For items that have been previously released.  This section gets cleared every year.

---

## Item structure

### Project

Used to indicate what the team plans to do.

### Status

Used to indicate where the item is on its journey to release, and to record when it gets completed/released.

### Notes

Used to keep track of any relevant information on the item, e.g. GitHub Issues/Pull Requests (PRs) related to it, contextual information, etc..  If there is a tracking issue/document, it should be indicated like so: `Tracking Issue: <link-to-tracking-issue>`.

#### Size
Notes on roadmap items should generally fit within the space of a small (~3x3 in) sticky note, otherwise they should probably be moved to a GitHub issue.

#### What not to put in a note

* PR links that are related to the tracking issue (put them in the tracking issue itself or get someone else to).
  * *If the PR doesn't logically fit in the tracking issue then it can be added to the note, but consider whether the tracking issue should be expanded or if an additional tracking issue should be created.*
* In general, information that is specific to a linked PR/issue, should be added as a comment on the PR/issue and not to the note on the roadmap, e.g. that PR #XXX still needs review from person Y, or that issue #XXX has been solved for everything except situation Z should be noted on the PR/Issue, not the roadmap.
  * *General status notes are okay, though, e.g. that PR #XXX has been merged or that issue #XXX is closed.*

### Firmness

Used to indicate how sure it is the item will be completed.

### Who's working on it

Used to indicate who is doing what (or is planning to) and who should be contacted for more information.  Reviewers aren't generally listed here, or if they are, they are marked as such.

---

## Item lifecycle

### Adding items to roadmaps

As the roadmaps indicate what each team will be spending time on, issues, PRs, projects, etc. should generally be discussed by the team before being added to the roadmap as a separate item, and the proposer may need to make a case for inclusion depending on where they're proposing it be included and how full the roadmap is already.

Issues and PRs can be added to related, already existing, items without discussion, but this may result in challenges by other team members if they disagree with the change.

#### Term limits

Each roadmap term should have a soft limit of around 10 items.

Note: it is advised that a bit of a buffer normally be left to accommodate new contributors.

#### Proposals

Anyone may propose something be added to a roadmap at any time (whether or not it's theirs), and may repropose, provided there is space on the roadmap and it's been a few weeks since the last proposal, or something has significantly changed since the last proposal that warrants a reproposal.

Roadmap items can be proposed and discussed via any public method of communication such as GitHub Issue comments, meeting discussion items, Discord channels, and Pull Request comments.

#### When proposals/team consensus isn't required

Small to medium size PRs/issues that aren't controversial and likely won't take too much time to complete may not need team consensus to be added as a roadmap item and may be handled by individual team members, provided that everyone that would work on/review the item is agreeable, and it doesn't interfere too much with the other work of the team members involved.

Note: the privilege of individual team members adding items to the roadmap without team consensus may be revoked if the team feels it is being used to avoid working on larger team projects or push controversial stuff through.

#### Extraneous tasks

Very small projects/tasks that are assigned to a single person may not need to be added to a roadmap, provided they are completed quickly.  If they are still pending completion at the next meeting, they should be re-evaluated.  If they are still pending completion after two meetings, they should be added to a roadmap or moved to somewhere else visible and permanent (e.g. a GitHub issue, PR, or comment, whatever is most appropriate).

#### Why proposals are generally required

Team members (or anyone) can always open PRs/issues at any time, but since reviewing and merging the PRs, or investigating the issues, will take resources from the team, it will generally be a collective team decision when those PRs/issues will be allocated the resources to move forward.

### Removing items from roadmaps

Issues, PRs, and projects should be discussed by the team before being removed from roadmaps, whether present as an individual item, or as part of the note of an individual item.

When removing a roadmap item that is still wanted at some point, check whether it has an equivalent GitHub issue, and if not, create one before removing it from the roadmap.

When removing something that isn't wanted at all, archive/close anything related to it, e.g. issues, PRs, documents, etc..

### Moving roadmap items between terms

Moving a roadmap item from one term to another should be discussed by those working on it, and any other relevant parties, before it is moved.

### Marking roadmap items as completed

Marking a roadmap item as completed is left up to the consensus of the people working on it, although the team may override if they feel it is necessary and have consensus.  When a roadmap item is marked as completed, the (ISO) date of when it was marked as completed should be added underneath the "completed" label in the same table cell.

### Moving roadmap items to the awaiting release and released sections

Once a roadmap item has been marked as completed it should be moved to either the awaiting release section (if it still has to wait for a public release) or directly to the released section (if no wait is needed).

Roadmap items in the awaiting release section should be moved to the released section when they are released.

When items are moved to the released section, the status column should be updated with a `RELEASED` label and the (ISO) date of when it was released.  The final state of the status column should look like the following.
```
Completed
2026-03-10

RELEASED
2026-03-11
```

### Moving roadmap items to the archive of released section

Roadmap items that have been moved to the released section will be left there for review/celebration until the next team meeting and then moved to the bottom/end of the archive of released section at the meeting.

---

## Sprinting

Occasionally, one or more roadmap items may be deemed to be so important that they need to be focused on to the exclusion of all else and released as soon as possible.

*Warning: sprints shouldn't be enacted unless really needed.*

### Initiating a sprint

If the team decides that a sprint is warranted, then the following actions are taken.

* The focused items are isolated in the short term section with a note added to each item saying that they are part of the YYYY-MM-DD sprint.
* Everything else that was present in the short term section is moved to the mid term section.
* A sprint backlog item is created at the top of the mid term section to keep track of any issues/PRs that come in during the sprint.
* The short term section label is prefixed with `(SPRINT)`.

Note: the soft limit for the number of items per term is waived for the duration of the sprint.

### Requirements during a sprint

Until the sprint items are completed, no other items may be added to the short term section unless they are judged to be even more important/urgent than the current sprint items.

### Concluding a sprint

After the sprint is finished, the `(SPRINT)` prefix is removed from the short term section label, the sprint backlog issues/PRs are evaluated as if they had just been opened, and the short term section is repopulated with appropriate items.

---

## Yearly maintenance

Archive a copy of the roadmaps at the end of each year.  Put a copy of each roadmap in an archive folder and name it with the format "X Team Roadmap YYYY" (use "ARCHIVED: X Team Roadmap YYYY" for the title text at the top of the document), then clear the items from the archive of released section in the main copy of each roadmap.

Note: to copy the roadmap you need to open the Google Doc, go to **File > Make a copy**.  Make sure "Copy comments and suggestions" and "Include resolved comments and suggestions" are enabled.

---

## Updating GitHub issues/PRs

### Initial status

When GitHub issues/PRs are opened by non team members (or anyone, if an auto-commenter is used), a comment should be made to convey that the teams work via roadmaps and the issue/PR will be updated as its place on/off a roadmap changes.  The current place on/off the roadmap, as well as links to the roadmaps and this policy should also be included in the comment.

### Status changes

When an issue/PR gets added to, removed from, or changes section on the roadmap, the issue/PR should be updated with a comment indicating it's new place on/off the roadmap and the appropriate roadmap label should be applied.  Links to the roadmap it's on and this policy should be included in the comment.

Note: it's possible that issues/PRs may end up on multiple roadmaps.

### GitHub issue/PR templates

#### Initial comment for non team member issues/PRs

```
Thank you for the <THING>.

ROADMAP STATUS: This <THING> isn't currently on any roadmap.  Updates will be conveyed here as its place on/off a roadmap changes.

You can view the roadmaps here: [Roadmaps Google Drive folder](https://drive.google.com/drive/folders/1Z6q2GoqnXIslxfcPP0ctVlTAKLi9OzEt).

For more information on how the roadmaps work, see our [roadmaps policy on GitHub](https://github.com/Hubs-Foundation/policies-procedures-guidelines-public/blob/main/roadmaps-policy.md).
```

#### Followup comment for issue/PR addition to a roadmap

```
ROADMAP STATUS UPDATE: This <THING> has been added to the <TERMNAME> term section of the [<TEAMNAME> Team Roadmap](<LINK>).
```

#### Followup comment for issue/PR term changes on a roadmap

```
ROADMAP STATUS UPDATE: This <THING> has been moved to the <SECTIONNAME> section of the [<TEAMNAME> Team Roadmap](<LINK>).
```

#### Followup comment for issue/PR removal from a roadmap

```
ROADMAP STATUS UPDATE: This <THING> has been removed from the [<TEAMNAME> Team Roadmap](<LINK>).
```
