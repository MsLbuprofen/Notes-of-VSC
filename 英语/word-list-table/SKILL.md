---
name: word-list-table
description: "Use when converting English vocabulary notes or word lists into a four-column Markdown table, pairing two entries per row, adding parts of speech and Chinese definitions, or completing an incomplete vocabulary list."
---

# Vocabulary Notes to Table

Convert the provided vocabulary notes into a concise four-column Markdown table. When the source is organized into sections or chapters, preserve that structure and format each section's entries in its own table.

## Procedure

1. Read all the supplied note content and preserve the original section structure and entry order. Keep section headings and other non-vocabulary structure such as quotations unless the user asks to remove them.
2. Keep each English word or phrase as an entry. Include listed variants, derivatives, and sub-phrases as separate entries when the notes distinguish them.
3. Preserve all source bolding. Bold entries indicate special or less-common meanings of familiar words; do not remove the bold formatting. When a bold entry has a parenthetical meaning, prioritize that meaning in the definition and retain any relevant additional meanings only when useful.
4. Preserve verb-form sequences and other explicit inflection patterns exactly as listed (for example, `forbid, forbade, forbidden`). Add explanations of the base, past, or past participle forms if helpful, but never delete or collapse the sequence.
5. Correct clear spelling errors in vocabulary entries (for example, `likehood` to `likelihood` or `benefic from` to `benefit from`) without dropping or silently changing the intended entry. If an entry is incomplete or ambiguous, do not guess; flag the uncertainty or ask for clarification.
6. Complete missing parts of speech and Chinese definitions using the surrounding context. Add a missing form or common collocation only when it is clearly implied by the source notes; do not invent uncertain entries.
7. Format the entries in a four-column table, placing two entries side by side in each row:

   | 单词/短语 | 词性/释义 | 单词/短语 | 词性/释义 |
   |---|---|---|---|
   | comprehend | vt. 理解 | essay | n. 短文；小品文 |
   | tend to do | 倾向于做；往往会做 | tendency | n. 倾向；趋势 |

8. For a single word, put its part of speech and concise Chinese definition together in the corresponding definition cell, such as `vt. 理解`, `n. 主题`, or `adj. 系统的`.
9. For every verb sense, specify transitivity: use `vt.` for transitive verbs, `vi.` for intransitive verbs, and `vt./vi.` when both uses apply. Never use the generic label `v.` (including within combined labels such as `v./n.`); retain other applicable parts of speech separately, for example `vt./n.` or `vi./n.`.
10. For a phrase or collocation, give only its Chinese meaning; do not label it with a part of speech.
11. If the number of entries in a section is odd, leave that section's final pair's unused cells empty.
12. Output only the table within each section, without an introduction, conclusion, examples, or other commentary. Preserve requested headings and source structure; do not add a title unless the user explicitly requests one.
