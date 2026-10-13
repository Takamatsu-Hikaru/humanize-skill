# humanize

[中文](README.md) · [English skill](humanize/SKILL.en.md) · [Chinese skill](humanize/SKILL.md)

**Writing that says something.**

A colleague sends you an AI-written report. The heading is “What should we do next?” The body promises to “build awareness and explore possibilities.” The conclusion pledges to “create a complete ecosystem for growth.”

Three pages later, you still do not know what they did.

Perhaps you asked AI to write it yourself. You say “more natural,” and it adds “try something fun.” You say “more formal,” and it starts enabling, empowering, and leveraging. You say “more direct,” and it spends two paragraphs explaining how direct it is about to be.

`humanize` is a Chinese and English writing skill developed through actual revisions of guides, event proposals, and resource pages. It helps an agent organize a piece around its audience and purpose, retain the author's judgment, and remove unnecessary instruction and self-explanation.

[English package](https://github.com/Takamatsu-Hikaru/humanize-skill/releases/latest/download/humanize-en.zip) · [Chinese package](https://github.com/Takamatsu-Hikaru/humanize-skill/releases/latest/download/humanize.zip) · [Editing examples](humanize/references/before-after.en.md)

## What changes

These examples concern proposals, reports, and resource descriptions. The right-hand side preserves the relevant facts and purpose.

| Draft | Revision |
|---|---|
| What does the website do? | Website features |
| First join the group and register | Registration |
| Publish the files in this order | Publication schedule |
| Try something fun | AI application experience, followed by actual examples: action recognition, exploration, and robot manipulation. |
| Make sure students can find it, understand it, and join in. | The AI Club will publish the announcement, three task briefs, and registration form on October 13, and establish the main competition group. |
| This guide cannot cover every situation or guarantee that it suits every reader… | This guide introduces resources for Python, model training, and agent development. |

The last example removes a generic disclaimer. A real version requirement, failure condition, or limitation still belongs beside the material it qualifies.

## Two editorial checks

**First, content.** What should the whole piece communicate? Why does each section and paragraph appear here? What does it add, and how does it lead into the next part? Check the throughline, groundwork, examples, resources, and allocation of space. Important explanations should not be crowded out by reminders or reduced to empty generalities.

**Then, expression.** Does it read naturally? Does it overteach, state the obvious, anticipate irrelevant criticism, or weaken a claim without saying why? Has trimming made it dry or removed useful experience and judgment? Preserve facts, conditions, citations, and unique links. For bilingual work, align meaning and tone without copying syntax mechanically.

The checks happen during editing; they need not become two reports delivered with every draft. A small edit needs only the relevant context. Good passages can stay as they are.

## The editorial approach

**Headings identify content.** “Website features” helps someone reviewing a proposal find information. A question heading can be appropriate in a real FAQ, but every section does not need to simulate a conversation.

**The body supplies information a reader can judge.** Actors, dates, materials, reasoning, and examples carry more than promises of understanding and growth. Missing facts must remain identifiable; polishing is not permission to invent arrangements.

**Readers can interpret clear material.** Do not keep telling them where to look or assigning a task at the end of each resource description. Preserve necessary steps in actual tutorials.

**Natural writing has more than one voice.** Recruitment copy can be lively, review material formal, and a technical article precise. Formal prose can use ordinary words. Adding casual filler does not create a human voice.

“First,” “then,” and numbers are not forbidden. “Ten days after evaluation” expresses timing; “three task briefs” expresses a quantity. What matters is whether the language contributes.

## Use

Download [humanize-en.zip](https://github.com/Takamatsu-Hikaru/humanize-skill/releases/latest/download/humanize-en.zip) and place the extracted `humanize` folder in your agent's skills directory, retaining its subdirectories. The English package uses English instructions and UI metadata and includes English examples, visual guidance, and tool references.

The [Chinese package](https://github.com/Takamatsu-Hikaru/humanize-skill/releases/latest/download/humanize.zip) uses the same skill name, `humanize`; install one package, not both. The instruction language does not restrict the language of the work.

For a tool that supports explicit skill invocation:

```text
Use $humanize to edit this proposal.
The audience is the organizers reviewing it; use a direct, formal tone.
Check the overall purpose, each paragraph's role, and information density,
then check expression and continuity.
Keep the facts, figures, links, and passages I have already revised.
```

You can also provide the [English skill](humanize/SKILL.en.md) and relevant references with a draft. An example of wording you like is often more useful than repeatedly requesting “less AI-sounding” prose.

If you only want an edit, the skill delivers the edited text. Specify file updates, page layout, or a WeChat version when those are part of the task.

## Files

- `humanize/SKILL.md`: Chinese instructions.
- `humanize/SKILL.en.md`: complete English instructions.
- `humanize/agents/`: Chinese and English UI metadata.
- `humanize/references/before-after.en.md`: editorial examples and reasons.
- `humanize/references/presentation.en.md`: images, pages, and WeChat layout.
- `humanize/references/github-references.en.md`: sources and optional tools.
- `humanize/assets/wechat-base.css`: a starting stylesheet.

Each English reference has a Chinese counterpart. The English installation package puts the English instructions in `SKILL.md` and retains the Chinese version as `SKILL.zh.md`.

Text editing needs no additional dependencies. Visual and layout tasks use tools appropriate to the task and environment.

## Examples and contributions

Contributions are welcome, especially awkward drafts accompanied by the audience, purpose, and a preferred revision. Remove private information before submitting.

Useful examples show what meaning was lost, what wording was unnecessary, or why guidance was unsuitable for that reader. A list of common AI words can just as easily remove good sentences.

## References and license

The skill draws on ideas from [blader/humanizer](https://github.com/blader/humanizer), [baoyu-skills](https://github.com/JimLiu/baoyu-skills), and [doocs/md](https://github.com/doocs/md). See the [reference notes](humanize/references/github-references.en.md) for scope. The editorial guidance and calibration examples were developed from actual editing discussions.

[MIT License](LICENSE).
