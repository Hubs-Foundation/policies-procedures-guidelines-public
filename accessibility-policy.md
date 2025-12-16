# **Accessibility Policy**

The [Hubs Foundation](http://hubsfoundation.org/) stands on two pillars: free & open standards and a global community focus.

As a proud contributor to the open-source software movement, Hubs Foundation supports collaboration, sharing, and participation. These activities naturally lead to increased accessibility. Thus, the very nature of Hubs software is open, welcoming, and encouraging for all users of every ability. Further, our homepage invites “artists, creatives, and you to create 3D spaces and publish them online for anyone to visit.” We sincerely believe that the “anyone to visit” phrase means that we should develop and create for every one of us. It is our hope that by encouraging accessible options here, we’ll make it easier for our creators and developers to promote accessible content for the wider world.

This policy will not define accessibility in terms of internet access, internet speed, or general ease of use for users. All of these concerns are already covered within our existing working teams. For example, the development team strives to streamline the computing burden of the Hubs software. The documentation team focuses on clear communication. Both the development and documentation teams increase awareness and documentation of how to access Hubs with smartphones (as an example of commonly available technology) and virtual reality headsets (as an example of less commonly available technology). Further, because the Hubs software was born from the WebXR movement, it centers on browser access and the [benefits that the immersive web provides](https://immersiveweb.dev/).

## **Overall Guidance**

One policy statement like “Try your best” cannot relay our accessibility intentions. So, we avoid generic statements like “[Don’t be evil](https://expertbeacon.com/the-rise-and-fall-of-googles-dont-be-evil-motto/)” or “[Be excellent to each other](https://recroom.com/code-of-conduct/)”. At the same time, here is some guidance.

It is good practice for Hubs Foundation content creators to ask if users with vision, sound, mobility, or cognitive differences of ability can equally access the content and if not, what can be done to increase access. The following overall guidance represents starting ideas, but is not meant as a full checklist.

* **Use the formatting tools already present.** Use title, header, list, table, and equation mark up functions that are already available within the media. For example, do not repeat a title for document meta data; instead briefly describe the contents of the document for a user that might be using a screen reader.
* **Use simple language.** This helps our language translation partners. Avoid sayings, cliches, or elaborate language.	Use "select" or "enter" instead of "click" or "scroll".  
* **Express the same information in two different communication methods.** Provide alternative text (alt text) for all images. Do not rely on color alone to relay meaning. If sound is meant to relay information (for example in a how-to video), include a transcript or a visual indicator.
* **Give the user control.** If an element like sound or speed *can* be controlled by the user, let it be controlled by the user, instead of determined for them. If an experience could cause dizziness, provide an advance warning.

## **Technical Writing Style Guide**

Hubs Foundation strives to provide both clarity and accessibility with our writing style. Given that Hubs is a technical product, sometimes those goals conflict; things have to be written in a very detailed way. This section explains the conventions we follow when it comes to this type of technical written expression.

### Action Verbs
Generally, instruction statements should start with an action verb that have an implied but not stated “you” in front of it.

Example:
Go to [Visual Studio Code](https://code.visualstudio.com/).

It is implied that *you* go to the website. Because the user has to go to the website where they will further complete a download action, “Go” is the preferred action verb, instead of “Select” or “Click”.


#### Examples of Action Verbs

Microsoft has [great technical writing suggestions](https://learn.microsoft.com/en-us/style-guide/procedures-instructions/describing-interactions-with-ui) when it comes to interacting with a user interface (UI).

- Open
- Close
- Leave
- Go to
- Select
- Pick
- Select and hold or Right click
- Clear
- Choose
- Switch
- Enter
- Move
- Save
- Zoom or Zoom in or Zoom out

Possibly OK but less preferred: Navigate, Activate, Explore, Access

Restate the action when it could be confusing.

Avoid using “Click”. Note: it is not required to include all possible expressions of the same interaction on different devices. Generally, Mac users know how to interpret “right-click” and trackpad users know how to implement a “double-click” on their devices. Microsoft advises that terms focus on what the user must do with the UI, not focusing on the device doing the action.

Avoid using “Scroll”, but the idea is that “scroll” should be used when it is proper *in context*. Other phrases could be “move through” or “move the wheel button”.


### Bolding

Because bolding changes the shape of letters, it can make some words harder to read. However, there are good uses for bolding. Also, some screen readers disregard bolding all together; that is, there is no auditory difference between a bolded and non-bolded word. As such, it would not relay any extra information in a text-to-speech situation; it is of no help and it is of no harm. We conclude that if bolding is used judiciously, it seems to add more than it possibly subtracts.

Here are two good example sites where bolding is used to good effect.

First, the [Design for Readability, Harvard University](https://accessibility.huit.harvard.edu/design-readability) site. Notice that the bolded sections start with an action verb and brief text.

![Capture of Design for readability webpage. Bulleted list of items has the first sentence bolded, starting with an action verb. Example text: Use visual and semantic space.](img/images/image1.png)

Second, the [Formatting text in instructions, Microsoft](https://learn.microsoft.com/en-us/style-guide/procedures-instructions/formatting-text-in-instructions) site. Notice that in-sentence capitalization and bolding is meant to relay when something is an interaction with the UI. 

![Capture of Microsoft, Formatting text in instructions page. Examples show bolding within instructions. Example bolding of the words save and as in the phrase select save as.](img/images/image2.png)

### Italics

Italics can be used “sparingly for emphasis” or if the type of communication dictates it.

Example:

We investigated [Brevo](https://www.brevo.com/) (formerly Sendinblue) but it does not offer all of the SMTP settings we need *at the free level*. If you want to pay more, Brevo might work.

### List numbering

Numbering on one “page” of instructions should continue numerically through the entire set of instructions displayed on that same page. The Beginner’s Guide is a current example. The idea is to make it easy to refer to a particular step. For example, directing someone to "The Beginner's Guide, Step 14, g" is more identifiable and less confusing than writing "The Beginner's Guide, Section 3, Step 3, Step 7".

Example where the numbering continues through sections, if all of the sections are part of one set of instructions:

#### Section 1
1.
2.
3.
#### Section 2
4.
5.
6.

### Menus


Page menus or right side menus aid navigation and the organized feel of a set of instructions. Navigation menus should be made if possible.


### Capitalization


When referring to other places within Hubs docs, use capitalization (e.g. Part 1, Step 4).


### Links


When including hyperlinks in writing, avoid “Click here” or “here” links. Instead put an active link inside of the description of the link. You can specify *exactly where* the link leads. 

Examples:

Go to the [GitHub Hubs Foundation hubs-cloud repository](https://github.com/Hubs-Foundation/hubs-cloud).


[Regenerating SSL Certificates](https://docs.hubsfoundation.org/regenerating-ssl-certificates.html) explains how to fix the problem of a security warning for your Hubs instance.

Screen readers contain the ability for users to navigate or tab through to only links on the page. It is confusing if the displayed link text is "here".

![Capture of NVDA link elements notification. All of the links and their display text are shown as one list.](img/images/image3.png)


### Discouraged language choices

For various reasons, there are some words that we would rather not use. Generally, we want to avoid language that assumes everyone can visually see, hear, move, or think equally well or not. Avoiding sayings and cliches should help us avoid using language that has violent or dehumanizing tones.

## **No One Walks Alone**

We encourage everyone to address accessibility within Hubs Foundation-produced content, but we also recognize that a “[first attempt at making anything accessible will be awful](https://accessability.substack.com/p/your-first-attempt-at-making-anything)”. Therefore, we’ve structured our efforts so that no single community member must create accessible content alone. A community member will come alongside a content creator to review, suggest, and perhaps directly modify the content to make it more accessible. No one walks alone in this effort; we are a community.

##  **How You Can Help** 

Situated as an XR product within accessibility intentions, Hubs is within “an emerging field and exploration is encouraged” ([XR Accessibility User Requirements, Section 4.10](https://www.w3.org/TR/xaur/#signing-videos-and-text-description-transformation)). Thus, we are always open to suggestions!

You may submit comments on accessibility privately via fictionalemailaddress@hubsfoundation.org.

Also, [GitHub Issues](https://github.com/Hubs-Foundation) (Note: include multiple links to separate repository issues??) is available and preferred for open discussion.

Optional footer wording: This policy is a draft document and may be updated, replaced or obsoleted by other documents at any time. It is inappropriate to cite this document as other than work in progress.

## **Sources**

[XR Accessibility User Requirements (Draft version)](https://www.w3.org/TR/2021/NOTE-xaur-20210825/)

[The XR Accessibility Project repository at GitHub](https://github.com/XRAccessibility/xraccessibility.github.io)

[W3C Immersive Web Working and Community Groups](https://immersiveweb.dev/), Summary of hardware, 	software, and examples

[Accessibility Guide for Authors](https://sigchi.org/resources/guides-for-authors/accessibility/), SIG CHI, The ACM Special Interest Group on 	Computer-Human Interaction, focuses on formal text communication

[IEEE Accessibility Statement](https://www.ieee.org/accessibility-statement), includes form for reporting

[Accessibility for Organization and Text Formatting Emphasis](https://ccaps.umn.edu/academic-technology-and-design/instructors/tutorials-accessibility-dei/accessibility-organization), University of Minnesota

[Design for Readability](https://accessibility.huit.harvard.edu/design-readability), Harvard University

[Captions and Audio Descriptions](https://uit.stanford.edu/accessibility/concepts/captioning), Stanford University

[Capitalisation,](https://a11y-101.com/design/capitalisation) Ally-101

[Text Basics](https://iu.pressbooks.pub/edsaccessibility/chapter/formatting-text/), Indiana University

[Understanding Disability](https://accessibility.engin.umich.edu/why-accessibility/understanding-disabilty/), University of Michigan