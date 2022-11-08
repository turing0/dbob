---
title: Round G 2022 - Kick Start 
layout: page
tags: dp tree
published: true
---

## Walktober

### Problem

  John participates in an annual walking competition called *Walktober*. The competition  runs for a total of **N**

 days and tracks the daily steps of the participants  for all the **N** days. Each participant will be assigned a unique ID ranging from  1 to **M** where **M**

 is the total number of registered participants. A global scoreboard  is maintained tracking the daily steps of each participant.

  John is determined to win Walktober this year and his goal is to  score the maximum daily steps on each of the **N**

 days among all the participants.  Having participated in Walktober last year as well, he wanted to know how many steps  he fell short of in achieving his goal. Given the previous year scoreboard,  calculate the minimum additional steps he needed over his last year score in order  to achieve his goal of scoring the maximum daily steps every day.

### Input

  The first line of the input gives the number of test cases, **T**

. **T** test  cases follow.  
  The first line of each test case contains three integers **M**, **N**, and **P**  denoting the total number of participants, the total number of days the  competition runs, and the last year participant ID of John.  
  The next **M** lines describe the scoreboard of the previous year and contains  **N** integers each. The *j*-th integer of the *i*-th line  denotes the step count **S****i****,****j** of the participant with ID *i* on the  *j*

-th day of the competition.

### Output

  For each test case, output one line containing  `Case #x`

`: y```, where *x* is the test case number  (starting from 1) and *y* is the minimum total additional steps needed by  John to achieve his goal.

## Curling

To link to another note, you can use multiple syntaxes. The following four use the "double-bracket" notation ([view the Markdown source file](https://github.com/maximevaillancourt/digital-garden-jekyll-template/blob/master/_notes/your-first-note.md#link-syntax) to see the underlying syntax).

- Using the note title: [[a note about cats]]
- Using the note's filename: [[cats]]
- Using the note's title, with a label: [[A note about cats|link to the note about cats using the note title]]
- Using the note's filename, with a label: [[cats|link to the note about cats using the note's filename]]

You can organize notes in subdirectories and link them normally. For example, the links above all point to the `_notes/animals/cats.md` file. Here's another example: [[tigers]].

Non-latin languages are supported too: [[안녕하세요]].

Dashes and underscores in file names are supported, and may be omitted in the bracket link syntax. As an example, the `your-first-note.md` file can be linked to with [[your first note]] or [[your-first-note]], or even [[yOuR-FiRsT Note]].

In all cases, if the double-bracket link does not point to a valid note, the double brackets will still be shown, like this: [[there is no note that matches this link]].

Alternatively, you can use regular [Markdown syntax](https://www.markdownguide.org/getting-started/) for links, with a relative link to the other note, like this: [this is a Markdown link to the note about cats](/cats){: .internal-link}. Don't forget to use the `.internal-link` class to make sure the link is styled as an internal link (without the little arrow).

Since the Web is all about HTML, you can always use plain HTML if you want, like this: <a class="internal-link" href="/cats">This is a link to the note about cats with HTML</a>.

Of course, you can also link to external websites, like this: [this is a link to Wikipedia](https://wikipedia.org/). Again, you can use plain HTML if you prefer. Footnotes are also supported and will be treated like internal links.[^1] You can point to other notes in your footnotes.[^2]

[^1]: This is a footnote. For more information about using footnotes, check out the [Markdown Guide](https://www.markdownguide.org/extended-syntax/#footnotes).
[^2]: This is another footnote that links to the note about [[cats]]. You may also point to [[notes that do not exist]] if you wish.

### 


### Site configuration

Some behavior is configurable by tweaking the `_config.yml` file.

**`use_html_extension`**: if you use a static host that doesn't support URLs that don't end with `.html` (such as Neocities), try changing the `use_html_extension` value to `true` in the `_config.yml` file and restart the Jekyll server (or re-build the site). This adds a `.html` extension to note URLs and may resolve issues with links. If you're still having trouble, I recommend using Netlify to host your digital garden: it's free, easy to use, and fully supports this template's features out of the box.

**`open_external_links_in_new_tab`**: when set to `true`, this makes external links open in new tabs. Set to `false` to open all links in the current tab.

**`embed_tweets`**: when set to `true`, tweet URLs on their own lines will be replaced with a Twitter embed. Default value is `false`.

