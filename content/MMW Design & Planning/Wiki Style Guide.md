---
tags:
  - MMW-Policy/Style
  - MMW-Development
description: WIP - Part of an 'MMW Policies and Guidelines' document in development.
---
## About

Work-in-progress: Part of an 'MMW Policies and Guidelines' document in development.

---

## Bold

- Use **bold** when defining terms and concepts. This includes:
	- The first mention of the article name in that articles introductory sentence.
		- Any alternative names in the introductory sentence should also be bolded. (e.g. "**Mlox** is a tool for sorting plugin load order.")
	- Phrases that are being defined in ordered and unordered lists.
- Use \*\***double Asterisks**\*\* instead of \_\___double underscores__\_\_ when writing bold words/characters. This makes it easier to differentiate them from \__italic_\_ words/characters at a glance when editing.

> [!example]-
> 
> ### Mlox
> 
> - **Sorting plugin load order** is the main use of Mlox.
> - **Mod conflicts** can be identified by mlox through the use of `[conflict]` rules.
> - **Requirements** can be stipulated by Mlox by way of `[requires]` rules to notify users if they are missing plugins required by others 

---

## Italics

* Use italics when writing the titles of books, games, game franchises, and offsite modding guides (e.g. _Notes for Modmakers_).
	- For example, _The Elder Scrolls_ should be italicized when discussing the game franchise. _Oblivion_ should be italicized when referring to _The Elder Scrolls IV: Oblivion_.
- Initialisms, most notably ESO, should not be italicized.
- Italics can be used for general emphasis, but should be used sparingly (see [[Wiki Style Guide#Emphasis]]).
- Use \__underscores_\_ instead of \**asterisks*\* to define italics. This makes it easier to differentiate them from \*\***bold**\*\* words/characters at a glance when editing.

> [!note]
> 
> By default, Obsidian uses asterisks to denote italics when using the `Toggle italic` hotkey. Instead, use `shift + _` to denote italics.
> 
> This behavior can be changed by installing one of several third-party community plugins that modifies this behavior.
>> [!warning]- Warning - Community Plugins
>>
>> Take care when installing community plugins, as these could potentially make unintended or format-breaking edits to the wiki content. 
>> 
>> Be sure to check whether the community plugin is listed in [[recommended community plugins]] before installing.

- 

---

## Emphasis

- Use _italics_ to emphasize important words and phrases. 
- **Bold** may be used to add emphasis, but _only_ for crucial warnings. 
	- However, in most circumstances, crucial warnings should instead be written in a `> [!warning]` or `> [!danger]` callout.
- Do not overemphasize: if everything is emphasized, nothing is.


> [!info]- Practices to Avoid When Emphasizing
> 
> #### Do not do the following:
> 
> - Add emphasis with 'single' or "double" quotation marks
> - Use ALL CAPS for emphasis. 
> - Use _**double emphasis**_ by both holding and italicizing a word or phrase.
> - Do not overemphasize, as each emphasis added will lessen the effect of other emphases and detract from the appearance of the article

---

## Headers

| Markdown            | HTML Header Tag Equivalent | Use                                               |
| ------------------- | -------------------------- | ------------------------------------------------- |
| \#                  | `<h1>`                     | Unused, as Quartz uses the filename as h1         |
| \#\#                | `<h2>`                     | Main section divider                              |
| \#\#\# and \#\#\#\# | `<h3>` and `<h4>`          | For use in article subsections                    |
| \#\#\#\#\#          | `<h5>`                     | For labeling _'Example'_ above fenced code blocks |


> [!example]-
> 
> ## \#\# This is a main subject (h2)
> 
> ### \#\#\# This subject has several important sub-subjects (h3)
> 
> #### \#\#\#\# Sub-subjects can benefit from subheadings (h4)
> 
> ##### \#\#\#\#\# Example (h5)
> 
> ``` 
> [example code block]
> ``` 

---

## Line-Wrapping

Do not 'hard-wrap' lines. This is unneeded in Obsidian which renders line-wrapping automatically according to window size, as does Quartz.

'Hard-wrapping' is intentionally adding a line-break after a certain amount of characters, e.g., after 80 characters.

---

## Links

> [!info]+ Internal Link to Another Article Within the Wiki
> 
> An 'internal link' is a link from one page in MMW to another page in MMW.
> 
> These should be rendered using \[\[Wikilink\]\] format as detailed on [Internal Links - Obsidian Help](https://help.obsidian.md/Linking+notes+and+files/Internal+links)

> [!info]+ External Link to Another Website
> 
> Use Markdown to link to another site: 
> 
> ```
> [insert link display text](https://websiteurl.com)
> ```

---

## Page Breaks

Use `---` to define a page break.

Page breaks should only be added at the end of an \#\# H2 heading section, not after \#\#\# H3 or more subheading sections.

> [!example]-
> 
>> [!success]+ Correct
>> 
>> ## H2 Heading
>> 
>> \[content\]
>> 
>> ### H3 Subheading
>> 
>> \[content\]
>> 
>> #### H4 Subheading
>>
>> \[content\]
>> 
>> ---
>> 
>> ## H2 Heading
> 
>> [!failure]+ Incorrect
>> 
>> ## H2 Heading
>> 
>> \[content\]
>> 
>> ---
>> 
>> ### H3 Subheading
>> 
>> \[content\]
>> 
>> ---
>> 
>> #### H4 Subheading
>>
>> \[content\]
>> 
>> ---
>> 
>> ## H2 Heading


---

## Syntax Highlighting

_Revisit this - check with G7 and S3ctor - refer to_ https://quartz.jzhao.xyz/features/syntax-highlighting

---

## Tables

Tables are easy to read; please use these whenever possible for listing data such as script functions (e.g., MWSE-Lua), modding tool commands (e.g., Tes3cmd commands), or in-game statistics.

> [!tip] Tip: Use 'Live Preview' Mode for Editing Tables
> 
> Obsidian will proportionally spaces vertical bars (`|`) and hyphens (`-`) for you while editing tables in Live Preview.
> 
> This won't affect how it renders in Obsidian or Quartz, but it makes the table easier to read as plain-text Markdown.


---

## Lists

Lists are particularly useful for guides and tutorials, which make up the majority of content on the wiki. Unnumbered lists or 'bullet points' help to organize and emphasize information quickly and effectively, while ordered lists (i.e., numbered lists) are useful for useful for step-by-step sections of tutorials.

### Unnumbered Lists

Use hyphens `-` for defining unnumbered lists and sub-lists, instead of asterisks `*`. This is to differentiate unnumbered lists from \*\***bold**\*\* words/characters.

### Ordered Lists







