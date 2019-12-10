# Style Guide

## Text, Tone, and Grammar

### General Do's and Don'ts

#### Yes

- Run all final drafts through Grammarly or a similar tool.
- Use short, concise sentences. People have little time to browse.
- Use basic language. Remove unnecessary words.
- Assume users are unfamiliar with the Bloom protocol. Link to basic terms when necessary.
- Use [pluralized, gender-neutral pronouns](https://en.wikipedia.org/wiki/Singular_they). Use “they/their” instead of “he/she/his/hers.” (e.g., “When they…” or “If users choose to X, then their…”)
- Use [oxford commas](https://en.wikipedia.org/wiki/Serial_comma).
- Remain open and objective.
- Provide examples when possible. Do not complicate them with complex numbers.
- Explain with examples when needed; otherwise, keep it simple.
- Do not spell out "percent.” Use the symbol (e.g., "15%" instead of "15 percent").
- Use double quotes " " for phrases, quotes, etc.,  not ' '.

#### No

- Exclamation points.
- [Second person language](https://en.wikipedia.org/wiki/Grammatical_person) in tutorials or FAQs.
(i.e., "You then..." or "Now you should...")
- Em or en dashes `—`.
- References to Purple Paper names (flip, flap, flop, etc.) in the documentation.
- Footnotes.
- Curly quotes `“`. Use the plaintext version: `"`.

### Numbers

- Spell out numbers below 10 (e.g., one, two, three...).
- Use numerals for numbers above 10, except when starting a sentence.
- Use figures with million, billion, and trillion in all except casual uses.
(e.g., "I'd like to make a billion dollars." vs. "The nation has 1 million citizens.")

### Currencies

- Dollars: Use lowercase except when writing "US Dollar.”:
  - Use figures and the \"$" sign in all except casual references or amounts without a figure. (e.g., "The book cost \$4." vs. "Please give me a dollar.")
  - For amounts less than \$1 million: \$4, \$25, \$500, \$1,000, \$650,000.
  - For amounts over \$1 million, use the word, not numerals. (e.g., "He is worth \$4 million" instead of "He is worth \$4,000,000.")
- Apply the same rules to other foreign currencies.

### Acronyms

- When making acronyms plural, simply add an "s" (e.g., "CDPs").

### Decades

- Do not use apostrophes to indicate decades (e.g., "the 1990s" instead of "1990’s").

## Markdown

> :exclamation: Save yourself some trouble. Use VSCode and install the Prettier extension. It auto-corrects 90% of your markdown mistakes.

### Lists

When bulleted and numbered lists contain complete sentences, capitalize the first word, and follow each with a period. If list items are phrases, no capitalization or punctuation is required. Also:

- Use [parallel construction](https://en.wikipedia.org/wiki/Parallelism_\(grammar\)) for each item in a list.
- Start with the same [part of speech](https://en.wikipedia.org/wiki/Part_of_speech) for each item (in this example, a verb).
- Use the same verb tense for each item.
- Use the same [voice](https://en.wikipedia.org/wiki/Voice_\(grammar\)) for each item.
- Use the same sentence type (statement, question, exclamation) for each item.
- Alphabetize all lists of names unless there is a clear priority at work.
- Use dashes rather than asterisks for unordered lists (i.e. `-` not `*`).
- Do not use ordered (numbered) lists unless order matters.
- Ordered list items should use the #1 repeated:

  ```markdown
  1. Item 1
  1. Item 2
  1. Item 3
     1. Item 3a
     1. Item 3b
  ```

### General

- Consider using Visual Studio Code and install:
  - `Markdown Preview Enhanced`, `Markdown Linter`, `Code Spell Checker`, `Prettier`, `GitLens`
- Include line breaks above and below headings.
- Do not make multiple top-level headings. Only use `#` once per document.
- Do not use the same heading twice. It breaks auto-generated navigation.
- Do not leave trailing spaces.
- Ensure there is a single hard return at the end of the file.
- **Ensure the [SUMMARY.md](../SUMMARY.md) file is updated for every document that should show up in GitBook.**

### File Names

- Filenames contain information specific to the contents of the file. Context is provided from the directory or through the presentation layer:
  `meeting-summary-ep-01.md`, not `scientific-governance-and-risk-meeting-summary-ep-01.md`
- Filenames are to be lowercase and words separated with `-`.

  > Example: `meeting-transcript-ep-01.md`

## GitHub

- Ensure repositories are up to date.
- **Commit early and commit often.** Submit changes before large merges.
- Discuss efforts in [#community-development](https://chat.bloom.co/channel/community-development).
- Ask for feedback before starting long projects.
- Make descriptive commit messages:
  - Incorrect: "Fixed something"
  - Correct: "Fixed spelling mistakes in filename.md"

## Links

- Use descriptive hyperlinks. Avoid generic terms:
  - **No:** Learn more [here](#).
  - **Yes:** Learn more at [awesome-bloom](#).
- When creating links for parallel translated documents, ensure relative links are updated to reflect the correct heading:

  ```text
  en: faqs/glossary.md#bloomid
  es: faqs/es/glossary.md#bloomid
  zh: faqs/zh/glossary.md#bloomid
  ```

## FAQ Style Guide

- Always use relative links.
- Look for terms to add to the [Glossary](../faqs/glossary.md).
- Important numbers should be bold: "A BloomID can achieve up to **125** profile strength score."
- List items that include definitions should look like this:
  - **Team:** Core team and advisors are critical to Bloom's success.
  - **Community**: Sentiment analysis is invaluable.
- Wrap examples, tips, tricks, and notes in code fencing when formatting needs to be preserved or color-coding is useful.

  ```markdown
  Note: Being a bad actor is bad. Don't be a bad actor.
  ```

  Otherwise:

  > use a quote

## Naming Conventions and Proper Nouns

### Tokens

- If referring to the usage or transfer of the token (particularly as it relates to transactions), use the capitalized acronym: `BLT`.
- If referring to then token in any other way, you may use the full name: `Bloom Token`.
