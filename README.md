# Clerk checks

Checks for [Clerk](https://github.com/jeff-bruemmer/clerk) to perform on a text, Markdown, TEX, or Org file.

## Checks

[Default checks](#default-checks) | [Customize checks](#customize-checks) | [Acknowledgments](#acknowledgments)

### Default checks

| **Check**              | **Description**                                                                                                  |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **Not the negative.**  | Prefer the word to the negation of the word's opposite.                                                          |
| **Phrasal adjectives** | Avoid hyphenating phrasal adjectives with an adverb ending in -ly, unless the adverb is part of a longer phrase. |
| **Annotations**        | Typical markers used to signal problem sites in the text.                                                        |
| **Archaisms**          | Outmoded word or phrase.                                                                                         |
| **Clichés**            | An overused phrase or opinion that betrays a lack of original thought.                                           |
| **Compression**        | Compressing common phrases. From Style: Toward Clarity and Grace by Joseph M. Williams.                          |
| **Corporate-speak**    | Words and phrases that make you sound like an automaton.                                                         |
| **Hedging**            | Say, or say not. There is no hedging.                                                                            |
| **Jargon**             | Phrases infected with bureaucracy.                                                                               |
| **Links**              | The Markdown/Org link should return a status code in the 200-299.                                                |
| **Needless-variant**   | Prefer the more common term.                                                                                     |
| **Non-words**          | Identifies sequences of letters masquerading as words, and suggests an actual word.                              |
| **Oxymorons**          | Avoid contradictory terms (that aren't funny).                                                                   |
| **Pompous-diction**    | Pompous diction: use simpler words. From Style: Toward Clarity and Grace by Joseph M. Williams.                  |
| **Redundancies**       | Avoid phrases that say the same thing more than once.                                                            |
| **Repetition**         | Catches consecutive repetition of words, like _the the_.                                                         |
| **Sexism**             | Sexist or ridiculous terms (like _mail person_ instead of _mail carrier_).                                       |
| **Skunked-terms**      | Words with controversial correct usage that are best avoided.                                                    |

### Customize checks

See [Clerk's README](https://github.com/jeff-bruemmer/clerk) for how to customize these checks, or create your own checks. This repository contains an example Existence check `custom/example.edn` to get you started.

### Acknowledgments

Some elements of these checks are borrowed from the excellent [Proselint](https://github.com/amperser/proselint).

