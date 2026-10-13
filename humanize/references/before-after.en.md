# Calibration examples: a research guide and an event proposal

These examples come from editing discussions on October 11–13, 2026. English renderings below convey the original Chinese reasoning; they are not quotations from an English source. Distinguish approved prose, rejected revisions, and the eventual editorial decision. Learn the relationships between sentences, not a template to impose on every article.

## 1. Foundations: preserve the actual argument

The user approved an argument with two connected ideas:

> Research can proceed from a project down to its prerequisites, while understanding mathematics, ML/DL, and computing still needs to develop from simple ideas to deeper ones. Learn what the work calls for, using courses and blogs flexibly. Sometimes enough understanding to continue is appropriate; sometimes a project or research direction calls for systematic study. The foundations include Python, computing, machine learning, deep learning, and mathematics.

The rejected revision said, in effect:

> You can start from an interesting problem and fill in knowledge while reading, coding, and experimenting. Or you can take courses systematically. Combine the two methods. Courses provide an overview, while textbooks, blogs, and code explain specific questions in depth.

There is no obvious grammatical problem in the revision. But it replaces the author's point about depth and learning order with a “projects versus courses” classification, then assigns functions to media without justification. Preserve the reasoning before smoothing the prose.

## 2. Mathematics and models: explain a real connection

Keep the connection between conditional probability, expectation, gradients, and KL divergence and their later use in language models, generative models, and reinforcement-learning objectives.

Remove repeated endings such as “Understanding these lets you understand frontier research” or “These ideas help build awareness.” The former material explains something; the latter offers generic benefits. A short transition can establish direction without listing every model again in the introduction, each section, and the conclusion. Do not imply that VAE, diffusion, and flow models use identical mathematics just to make the explanation tidy.

## 3. A first project: show something worth trying

Rejected additions promised that a small project would produce a research question, or introduced a dataset by warning immediately that it was too small for meaningful performance comparisons.

The approved opening showed concrete possibilities:

> If you want to play with AI and see what it can do, start with a small project. Recognize handwritten digits, detect people and cars in your own photos, or let a model call tools to help with a task.

Concrete results establish interest. Data splits can still be explained when discussing training and evaluation. An introduction to a first run does not need every evaluation caveat in advance. This is not a rule to remove all qualifications.

## 4. A paper page: describe the resources

| Before | Adopted treatment | Why |
|---|---|---|
| Once you have a question, consult the long list | More papers | Do not invent a prerequisite for browsing resources. |
| Read one with an experienced person | Paper discussions; introduce Mu Li's readings directly | Name the content and source. |
| First pick a direction, then a paper and examine its question and validation | Remove the extra workflow | Filters and descriptions already make browsing possible. |
| Includes images, short descriptions, and paper links | Remove | The reader can see them. |
| Some of our cards also include links, such as… | Mention illustrated Transformer explanations and annotated code as examples of accompanying material | Explain the material, not how the site arranges links. |
| 49 cards → introduction → duplicate recommendations | Introduction → 49 cards → discussions → more papers | Order itself communicates the structure. |

The final title was “Selected papers.” All 49 cards, images, filters, and details remained. This decision does not make “pick a paper” or “try it” universally unnatural.

## 5. Links and sources

Use subjects for resource headings, such as “Attention, positional encoding, and generative-model derivations.” Link the source's public name to its blog. A particular article, such as a scaling-ladder explanation, should link to the article itself; the author's handle can separately link to their blog.

Put links beside the relevant topic on a website without repeatedly linking the same destination in one paragraph. A WeChat article may need an end-of-article reference list; changing medium must not lose the original URLs.

## 6. Preserve presentation that already works

The homepage's question-based navigation table, research-direction diagrams, and terminology search each have a purpose. A request to match a lookup page's colors to the main site does not authorize rewriting its content and functionality.

The user liked “If you…” phrasing on the homepage while rejecting repeated branching instructions inside the paper article. There is no contradiction: judge the page's function and density, not isolated words.

## 7. Event proposals

On October 12, the user requested direct, formal wording for an event proposal reviewed by senior students. The previous draft had used a beginner-facing guided-tour tone. The appropriate formality came from this audience and purpose, not a universal rule for all writing.

| Before | Adopted treatment | Reason |
|---|---|---|
| Which students is this for? | Eligibility | Identify the information category. |
| What will you gain? | Expected benefits | State the topic without simulating a conversation. |
| What does the website do? | Website features | Use a content heading. |
| First join the group and register | Registration | Put actual procedures in the body. |
| Publish the group files in this order | Publication schedule | The dates and order belong in the schedule. |
| Try something fun | AI application experience | Use action recognition, exploration, and robot manipulation to show the concrete experience. |
| Find people to do things with | Collaboration and mentorship | Preserve the value of working with and learning from others. |
| Try a research question | Research experience | Explain comparisons, experiments, error analysis, and sharing findings. |
| First part… second part… | Announcement, materials, talks | Name the stages; numbers only locate them. |

Rejected passage:

> First make sure students can find it, understand it, and register. Prepare the main group, announcement, four documents, and registration form together, with promotion pointing to the group and signup entry.

Adopted passage:

> The AI Club will publish the announcement, overall event description, three task PDFs, and team registration form on October 13, and establish the main competition group. Promotional copy, posters, and banners will use the same group and registration entries.

The revision identifies the actor, date, materials, and destinations. The original turns the goal into a slogan and leaves the arrangement vague. The problem is not simply informality; it substitutes guidance for information a reviewer can assess.

A patronizing effect often comes from excessive instruction: repeatedly telling readers where to look and what to do assumes they cannot interpret already-clear material. Necessary tutorial steps still belong in tutorials. Here, the reader needed to assess an event plan, not be led through it.

“First,” “then,” “one,” and “two” are not forbidden. “Presentations about ten days after evaluation” states timing; “three task briefs” states a quantity. Remove invented sequences, generic encouragement, and filler. Changing only the headings leaves the problem in the body.

## 8. A writing page and the two checks

The repeated correction in this discussion concerned why the article suddenly introduced a subject. A writing page that opens with “First write a few sentences…” or a list of tools gives advice before establishing why writing is being discussed and what those suggestions serve.

The approved progression was: introduce writing through how research becomes a paper; discuss the throughline and the roles of the abstract, introduction, setup, and method; consider questions to ask while drafting and revising—“Why say this here? What am I communicating?”; discuss defensive prose, overexplaining, self-deprecation, and formulaic AI wording; then introduce writing resources, tools, and rebuttal material. An introduction leading from background and motivation to a proposal, a setup formalizing the problem, and a method explaining the approach are concrete examples here, not a paper structure to impose on every article.

The **content check** asks whether these parts serve the purpose of communicating research clearly, whether any section is disconnected, whether tools appear before their purpose, and whether reminders crowd out the main explanation. The **expression check** looks at groundwork and transitions, advice becoming patronizing instructions, imagined criticism, and useful experience being reduced to dry commonplaces.

For code reading, “Don't worry about all the files; first make a checklist, then verify each item” does not explain how to understand an implementation. “Use the paper's architecture and design to trace data through the program, then follow training and inference” gives a practical line of understanding. AI helping connect the paper and repository is a concrete role worth retaining. Do not append an unnecessary assignment.

## Scenarios for a skill self-check

For a substantial skill revision, choose a relevant scenario; do not run the whole set on every edit.

1. Given “This is an important entry point for building knowledge; read one item and save a record,” describe the real resource rather than substituting another platitude. Do not invent missing course content.
2. If the user requests preserving a foundations introduction and only changing links below it, retain that introduction.
3. For a WeChat article with a complex paper figure and eight links, keep figures readable and sources accessible. Do not replace technical information with decorative art.
4. Given the same event material for an organizer and a new participant, adapt the tone to each audience while preserving facts. Do not use one voice for both.
5. For a writing page containing an opening, section explanations, revision experience, AI tools, and rebuttal resources, check each part's role, continuity, and proportion. Removing a few words is not a complete review.
6. If the request is “Make an English version of the humanize skill and add two editorial checks,” edit the skill and its references. Translating the recently discussed website does not fulfill the request.
