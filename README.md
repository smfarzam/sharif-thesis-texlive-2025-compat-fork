# Sharif Thesis - TeXLive 2025 Compatibility Fork

This is a temporary fork of [sharif-thesis](https://github.com/momeni/sharif-thesis) intended to address compatibility issues with TeX Live 2025. I will make a pull request from the upstream repository upon completion. The repo will be archived if changes merged.

### Changes
- Updated deprecated commands with the help of AI agents
- Integrated fonts inside the repo
- Changed main text font to XB Niloofar

### Why This Template
Generally, [thesis-template](https://github.com/zarrabi/thesis-template) is preferred over [sharif-thesis](https://github.com/momeni/sharif-thesis); It is more popular, simpler and easier to use. However when considering the glossary part, [sharif-thesis](https://github.com/momeni/sharif-thesis) is preferred.

With [sharif-thesis](https://github.com/momeni/sharif-thesis), you can easily manage terms that need to be included in the glossary. Simply enclose each new term in a \term{} command, and the template will automatically detect its first occurrence, place a footnote, and add it to the glossary in alphabetical order.

On the other hand, with [thesis-template](https://github.com/zarrabi/thesis-template), you need to manually identify the first occurrence of each term, insert the footnote, and ensure that the glossary entries are sorted alphabetically. This approach can lead to potential issues, such as missing a term, adding a term that isn't actually used in the text, or placing the footnote on an occurrence other than the first one.
