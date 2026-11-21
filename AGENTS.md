<!-- TODO: feed AI the file with interview questions https://github.com/rolling-scopes-school/ai-native/blob/ai-native-2-0/ru/interview/how-it-goes.md -->

## The goal of this guide

Teach the reader the basics of agentic engineering. After reading the guide, the reader is not expected to become an expert. The reader should be able to pass an interview for a junior position on this topic, answering questions like "How do we make ...", "Why should we use ...", "Why shouldn't we do ...".

## The outcome

The reader should understand all existing tools (for example: subagents, skills, specs, MCP), concepts (context window, critic, and so on), and the basic workflow (e.g. context management, commands for topics already covered like `/compact`, `/btw`, and so on).

## Notes style

- The first line of a bullet in a list should tell what to do or what not to do. Only then can the explanation follow.
- When there is a command for an agent, teach OpenCode commands. Only when another agent has a useful command OpenCode lacks, mention it and say how to do the same thing in OpenCode.
- When rewriting commands (e.g. Kimi/Claude → OpenCode): change only existing agent commands, CLI names, paths, and doc links. Do not add new tool-specific facts to conceptual lines that did not name a tool. Example: a sentence about what a sandbox is must stay tool-agnostic — do not append "OpenCode has no built-in sandbox" there. Put product-specific caveats only in a subsection that already names that product (e.g. "### OpenCode").
- When rewriting text, only rewrite what the user asked. DON'T add information that was not there before the edit.
  For example: I asked to replace Kimi Code commands with OpenCode commands. The agent added "OpenCode doesn't have the functionality" to the line that didn't even talk about agents. No models or agents were mentioned in the initial sentence.
- The notes should be as short as possible, but DON'T sacrifice conciseness for shortness.
- Prefer lists instead of writing multiple group elements separated by commas.
- Group similar concepts. E.g. guardrails include contracts, hooks, and so on. They should be grouped under the "Guardrails" section.
- If a section mentions another section of this guide (e.g. "Same loops as **eval automation**" — and that section was already covered), the section that is mentioned should come before the section that mentions it.

## Notes formatting

- DON'T use bold text too much. DON'T try to highlight a word in every sentence. Only highlight text if this is the key part of the idea you are describing.

## Workflow

### Constraints

- Don't use superpowers. It's too much. We are just writing a markdown file and there is no need for planning and brainstorming.
