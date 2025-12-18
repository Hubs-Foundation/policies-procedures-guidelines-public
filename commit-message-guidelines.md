# Commit Message Guidelines

[Atomic commits](https://www.aleksandrhovhannisyan.com/blog/atomic-git-commits/) are preferred.

## Title

* Separate the title of the commit message from the body of the commit message with a blank line.
* Try to keep the title descriptive and concise.
* Title should specify what the commit does. 
* Capitalize the title line and don't end the line with a period.
* Make sure the title completes either of these sentences:
    * "If applied, this commit..."
    * "If applied, this commit will..."

## Body

* Explain what the commit does.
* Explain why the commit does what it does.
* Add any additional details that could be useful.

## Commit Message Instructions

1. After entering "git commit" in VS Code, select the new tab labeled "COMMIT_EDITMSG".

![Capture from VS Code of tab with text: Commit_editmsg](/images/commit1.png)

2. Starting on line 1, follow the template for Subject/Title and Body explained in this policy and include your Title, What, Why, and optional Note sections. Insert a blank line between each section.

![Capture from VS Code, new commit message tab. First line is blank.](/images/commit2.png)

Meanwhile, the Terminal window will state "hint: Waiting for your editor to close the file...".

![Capture from VS Code Terminal window with text highlighted "hint: Waiting for your editor to close the file..."](/images/commit3.png)

4. After you have completed your commit message, select File, Save and then close the COMMIT_EDITMSG tab.

![Capture from VS Code, example of a complete commit message tab. Highlights show that the first line is the Title. Then there is a What, Why, and Note section.](/images/commit4.png)

At this point, you can push your local changes to your online repository.

## Example Title, What, Why, and Note sections

Add commit message guidelines

What:
Adds guidelines for commit messages to be used by contributors in all of our projects.

Why:
This keeps things standardized and predictable and encourages people to include the very important context of why they're making their changes.

Note:
The example for the body of the commit message doesn't have to be followed exactly, the most important part is that the commit message is clear and informative, but I find the headings useful for saving brain power by essentially just giving me a form to fill out, and helping make sure I think about what context I need to convey so that others (including my future self) will understand what I'm doing.

## References:

* https://cbea.ms/git-commit
