---
layout: page
title: User Defined Shortcuts
include_in_header: false
---

Click the cog icon on the top right (or using shortcut cmd + ,) to open the editor options view.
Then in the "Text insertion shortcust" text box, we can edit the content to define shortcuts.
Rules:
- Each shortcut defintion will be one line of text;
- Each shortcut should be in the format below:

```
{number}, {text to insert before the cursor}, {optional text to insert after the cursor}, {name of the shortcut}
```
for example, 

```
1, aaa, bbb, test
```
will define a shortcut triggered by `CTRL + 1` (pressing the `CTRL` key and `1` key together), and it will insert `aaa` before selected text and `bbb` after the selected text
- The following variables can be used in the shortcut defintions:
   - {% raw %}{{filename}} {% endraw %}, currnet file name;
   - {% raw %}{{date}}{% endraw %}, current date;




