---
name: humanize
description: Edit Chinese and English proposals, documentation, guides, technical blogs, resource pages, and articles. Review the throughline, paragraph purpose, substance, and continuity while preserving the author's voice and judgment. Reduce overexplaining, defensive prose, and patronizing instruction; handle visuals and layout when requested. Use for natural writing, humanizing, refining, or polishing, not AI-authorship detection.
---

# Humanize · Writing and presentation

Write with substance, a clear progression, and the author's judgment. Learn from wording the user has already approved. Preserve accurate knowledge, specific recommendations, and a natural voice. Fewer words, more casual language, or the removal of certain phrases does not by itself make a better edit.

The [Chinese edition](SKILL.md) contains the same guidance. Choose the output language for the task. A request to edit or translate the skill concerns the skill files, not the article or website most recently discussed.

## Establish the task

Work within the current request and existing authorization. Carry forward the agreed audience, purpose, brand, and tone. Ask only when missing information would materially affect the result. Ordinary editing does not automatically expand into a site redesign, image generation, or publication.

- **Writing and narrative:** read the full draft and the user's accepted and rejected examples, then [before-after.en.md](references/before-after.en.md). Titles, introductions, paragraph order, and resource placement can be revised.
- **Visuals and presentation:** read [presentation.en.md](references/presentation.en.md). Presentation includes the visual treatment of pages and articles; make a slide deck only when requested.
- **WeChat articles:** use the WeChat section of the presentation reference. Retain editable text, produce readable and reusable HTML, and inspect it at mobile width.
- **External tools:** read [github-references.en.md](references/github-references.en.md) when choosing tools. These are references, not dependencies to install or invoke on every task.

If the user wants a draft, deliver the draft. If they request file edits, update the source. With existing publication authorization, complete publication and verification. The skill neither grants permission to send messages, upload drafts, or publish, nor requires reconfirmation for actions already authorized.

## Editorial judgment

### Establish the throughline and purpose

After reading the whole piece, be able to explain privately: Who is it for? Why discuss this topic here? What should the piece ultimately communicate? What does the reader need to understand or judge? Use that purpose to decide what belongs. Do not automatically turn it into a “what you will gain” opening or give every resource page a set of learning objectives.

For each section and paragraph, ask: **Why say this here? What am I trying to communicate? What does it add to what came before, and how does it lead into what follows?** A paragraph may establish context, explain a problem, offer an example, advance an argument, or make a transition. It need not perform the same job as every other paragraph. Put groundwork before the point it prepares, examples next to the claim they explain, and tools or resources after their purpose becomes clear. A sentence being true is not sufficient reason to include it.

Review substance and proportion across the piece. Are the central question, explanations, and examples developed enough? Have ancillary reminders crowded out the main content? Does one section repeat another? Has a judgment that needs explanation been reduced to a platitude? Maximum density is not the goal. Retain enough context and experience for readers to follow; do not flatten an article into an outline of conclusions. Let content determine section length rather than making equal-length paragraphs or adding a Tip to every section.

### Start from the author's reasoning

Understand what the author means to tell the reader. An introduction should establish the actual reason for the piece and lead naturally into it. “Research can proceed from a project down to its prerequisites, while foundational understanding still develops from simple ideas to deeper ones” expresses a useful relationship. Replacing it with “There are two learning methods, and they can be combined” removes the point.

Allow varied sentence lengths, parentheses, mixed-language terminology where appropriate, and the author's own judgments. Do not standardize every paragraph's length or syntax. Do not invent personal experiences, emotions, jokes, or slang to simulate warmth.

### Make paragraphs contribute

Keep definitions, examples, reasoning, and transitions that add something. Remove summaries that merely repeat, descriptions of an already-visible interface, and explanations of why the article is organized as it is. Edit sentences in context rather than applying a blacklist of supposed AI words.

“These cards include images, descriptions, and links” can disappear when the cards are in view. Explaining how probability and expectation enter a reinforcement-learning objective conveys a substantive relationship. Do not treat both as overexplaining.

### Use advice and qualifications proportionately

Describe what a resource contains and actually discusses. Do not invent a reader situation for every link or impose a “read one → do one → save a record” workflow on open exploration.

Keep necessary installation order, established course sequences, and exercises the user requested. A homepage table that routes readers by question can also be useful: navigation has a different role from repeated instructions embedded in prose.

Ask whether a reminder changes the reader's immediate action, conclusion, or choice. Keep real failure conditions, scientific qualifications, and relevant risks. Remove or relocate disclaimers aimed at objections nobody has raised.

Watch for defensive writing: anticipating an irrelevant criticism, repeatedly stating “this is not to say…,” diminishing a claim without a concrete reason, or substituting explanations for a direct statement. State the actual conditions when a qualification is needed. Generic modesty and disclaimers should not dilute a supported judgment. Removing defensive prose should not remove useful reflections from experience.

A small-project introduction can show an appealing result without promising that it will produce a research topic. A course description can explain its content and character without ending every paragraph with “build understanding” or “develop skills.” These phrases are not forbidden; ask whether they are supported and informative.

### Respect the reader and preserve the author

Use titles that identify the content. On resource pages, organize headings by subject; link the author's public handle to their blog and article titles to the actual articles. Reputation is not a substitute for explaining a resource. Give the author's own projects an appropriate place when they serve a different role from outside recommendations.

Preserve paragraphs, figures, and structures the user has deliberately polished. Do not rewrite them solely for stylistic uniformity. Explain a technical term where first needed or where it answers a concrete question. Neither assume the reader knows nothing nor remove necessary definitions merely to appear concise.

### Proposals and descriptions: state the substance

Determine whether the document is for review and collaboration or for instruction. Material for colleagues, senior students, or organizers should state facts, arrangements, and open decisions. Do not automatically use the greetings, encouragement, and guided-tour voice of a beginner tutorial. Clear information and usable structure can be friendly without extra informality.

For such documents, prefer neutral content headings: “Eligibility,” “Expected benefits,” “Publication schedule,” or “Website features.” “What does the website do?” and “First join the group and register” add a layer of guidance before the reader reaches the information. When the user requests neutral headings, check both subheadings and bold list labels. Preserve genuine questions and steps in FAQs, tutorials, and arguments built around questions.

State who does what, when, and what is provided. “The AI Club will publish the announcement, task briefs, and registration form on October 13” gives more useful information in an organizational proposal than “Help students find it, understand it, and join in.” Preserve concrete value the user cares about—mentorship, collaboration, research experience—instead of replacing it with generic promises of growth.

Examine phrases such as “how,” “first/then,” “one/two,” and “try a little.” Do they express a real question, dependency, or quantity, or merely imitate instruction and encouragement? Remove guidance with no informational role, while retaining actual timing, steps, and numbers. Do not blacklist the words or call a change from “a little project” to “project practice” a complete edit; revise the paragraph's stance and organization.

Formal prose can use ordinary, specific words. “Publish the materials, register teams, check the scores” is clearer than “build an ecosystem and enable growth.” See the [event-proposal example](references/before-after.en.md#7-event-proposals).

## From paragraphs to pages

Fix order where it affects comprehension before polishing sentences. Introduce material before presenting it, keep examples beside what they explain, and place comparable material together.

When editing an existing site, inspect source and rendered output. A builder may insert cards, navigation, resource lists, or tips outside the Markdown. Do not miss that injected copy. When changing a title, align navigation, search, and entry labels. Preserve link targets, anchors, and interactions unless the task requires changes.

Merge repeated introductions of the same resource while keeping unique links. Do not silently discard useful content just to shorten a page or retain two near-identical recommendation lists in the name of completeness.

Choose subjects, placement, size, and captions to suit the content. Factual screenshots, paper figures, project outputs, relationship diagrams, and original illustrations serve different purposes. An article's visual rhythm should come from its material and paragraphs, not a box around every paragraph or bold type in every sentence.

## Two editorial checks

**First: content and structure.** Follow the throughline and examine the ultimate purpose, the role of every section and paragraph, order, added information, and allocation of space. Find abrupt topic changes, missing groundwork, repetition, tools introduced before the problem, and important ideas left unexplained. Resolve content arrangement before sentence polish; smooth sentences do not rescue an unclear piece.

**Second: expression and continuity.** Read in the reader's order. Check whether sentences and paragraphs connect naturally; whether the draft overteaches or assumes the reader lacks judgment; and whether it includes true-but-unhelpful statements, purposeless instructions, defensive declarations, or unsupported self-deprecation. Also check that trimming has not made it dry or removed experience, examples, or authorial judgment. Compare against the source for facts, qualifications, citations, and unique links. For bilingual work, align intent, substance, and tone without mechanically copying the other language's syntax.

These are editing perspectives, not two reports to show the user. For a local edit, apply them to the affected passage and necessary context. Leave good wording alone once the checks pass; do not keep rewriting to make it “more human.” See the [writing-page example](references/before-after.en.md#8-a-writing-page-and-the-two-checks) for an application.

## Completion and delivery

- **Ordinary editing:** deliver one complete version. If asked for before/after, show meaningful differences rather than multiple rounds of self-evaluation.
- **Page edits:** provide the result and a brief account of changes; verify the relevant pages, links, or build.
- **WeChat layout:** deliver editable text, HTML, and the actual images. State the scope of preview checks. A browser preview is not verification inside the WeChat editor.

Do not produce an “AI flavor score” or infer authorship from style. Explain a problem in its specific context rather than claiming “humans never write like this.”
