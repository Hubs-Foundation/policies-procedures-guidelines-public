# Issue Triage Guidelines
_For Hubs Foundation (Volunteer) Staff_

*General Principle: Issues exist to help us, not for the sake of process.*

## Linking

The description or title of a Pull Request that is expected to completely deal with an Issue should be edited to include "fixes" followed by the Issue number.
For example, "Fixes #42".  The Issue will then be automatically closed when the PR is merged.
A Pull Request that partially addresses an Issue or might help with an Issue, should be edited to include the Issue number (but not after "fixes").
For example, "Should help with #69".
If a Pull Request is created, but there is no existing Issue and the PR is one of several approaches to solving the Issue, ask the PR author to create an Issue documenting the problem.

When an Issue has been completely dealt with, it should be closed with an explanatory message.
The message should include the Pull Request number, if it was fixed by a PR.


## Merging

If an Issue addresses one symptom of an underlying problem, the Issue should be broadened to cover the underlying problem.
If an Issue covers several unrelated problems, it should be split or narrowed to one problem.
If an Issue is another aspect of an existing problem, the less-complete Issue should be closed in favor of the better-described Issue.
Include text such as "closed in favor of Issue #101".


## Some reasons to close an issue

* Issues administering a particular instance, or addressed in the documentation, should be closed with a pointer to the relevant documentation and/or support forum.

* Issues that depend on factors outside our control (for example, the behavior of browsers when linking from one WebXR site to another) should be labeled as documentation-required.
Once the documentation has been updated with a note and any workarounds, the issue should be closed.
Typically, there's a better forum for such issues.

* Issues that are obsolete, because of a changed environment, should be closed with an explanation.

* Omnipresent issues such as adding localization in a new language don't require an Issue to exist.

* If an issue is subjective, such as documentation being unclear, but not specifically wrong, there's no need for an issue.
The reporter should submit a Pull Request, which can then be evaluated.


## Some reasons not sufficient to close an issue

* Lack of activity is not, by itself, grounds to close an Issue.
Consider if there is actually some other grounds.
Some Issues can be triaged as Will Not Fix, Working As Intended or Could Not Reproduce.

* Vagueness should prompt a request for clarification.
Continued vagueness requires a judgement call.
If there does appear to be some meat to the Issue, it should remain open, even if it's not clear how to reproduce it, or what can be done.
Otherwise, it should be closed.

