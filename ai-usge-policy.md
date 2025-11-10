# AI Usage Policy

Generative AI can be a valuable tool to aid contributors, but it can also introduce legal risks and result in lower quality contributions if not used properly.  In order to ensure that AI usage is of net benefit to the project, the following rules and guidelines have been adopted.

## Rules

1. We require any submissions (issues, pull requests, commits, comments, etc.) that use AI tools to disclose this and what parts it was used for.  If the actual thing getting integrated used AI tools as part of its creation, then what AI program and model was used (e.g. ChatGPT using the GPT-5 model, Claude Code using the Sonnet 4.5 model, GitHub Copilot using the Gemini 2.5 Pro model, etc.) should be documented as well.  Reviewers/Triagers are encouraged to inquire about AI tool usage.  *Reasoning: this ensures that if there are any legal issues (or any other issues) they can be addressed, potentially by the removal of the AI generated content if needed.  Reviewers/Triagers can also do their jobs better if they know whether they're dealing with AI content.*

2. We strongly encourage people to only use AI as assistive tools, e.g. asking questions to help in understanding something, polishing writing outside of contributions (such as pull request descriptions, comments on pull requests/issues, etc.), generating a first draft that is then rewritten completely (or the majority of it is), generating repetitive boilerplate that is then filled in by the contributor, etc..

3. We require contributors that use AI tools in their submissions to understand and stand behind their submissions the same as if they had written them entirely on their own.

4. We require contributors to always be confident that they are the principle owner, and control the copyright, of the AI assisted contribution they submit.

5. We will reject any normally copyrightable submissions that appear to be significantly (or fully) AI generated, e.g. anything that has been "vibe-coded".  *Reasoning: unmodified or mostly unmodified AI output is often considered public domain and not owned by the contributor and so won't follow the terms of our license, and/or it may contain content that is incompatible with our license.*

Note: If submissions don't comply with this policy, reviewers are encouraged to attempt to help submitters refactor their submission to comply with this policy.

## Guidelines

The recommended disclosure for AI tool usage is as follows:

Level 1
Usage of AI for personal edification, e.g. asking AI to explain how something works, doesn't need to be disclosed as this doesn't directly affect the project.  Note: if you are copy/pasting AI responses back to people, then the second level of disclosure should apply.

Level 2
Usage of AI for the generation of anything outside the actual thing getting integrated, e.g. using AI to open an issue or write a commit message, should be disclosed, along with what it was used for, so that people can handle it appropriately.  Disclosing which AI programs were used is encouraged, but not necessarily required.

Level 3
Usage of AI for the generation of the actual thing getting integrated, e.g. using AI to generate part of your code or other assets that you are submitting, should be disclosed along with as many details as you have, e.g. which AI programs were used, what models they used, what you used them for, etc..  Note: this should be included in both the pull request description and the actual commits where AI tools are used, however, you can likely stop at the commit level and just document what AI the commit used without needing to give a breakdown of each line within the commit that used AI, i.e. the whole commit would be considered to be AI assisted.
