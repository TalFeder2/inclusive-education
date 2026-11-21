# Where we are now

Status board for Semester 1 of the International M.Ed. in Inclusive Education for
At-Risk Children and Youth, Oranim Academic College.

The page shows, for each course: the unit it has reached, what to do now, the next
thing due, and when the next update is expected. Each card also shows its own age,
so an out-of-date card says so instead of looking current.

## How to update it

Everything on the page comes from **`status.json`**. Nothing else needs touching.

1. Open `status.json` on GitHub.
2. Click the pencil icon (Edit this file).
3. Change the text between the quotation marks.
4. Click **Commit changes**.

The live page updates within about a minute.

### The fields

| Field | What goes in it |
|:--|:--|
| `unit` | The unit the course is on, e.g. `Unit 5`. Leave empty if not known. |
| `now` | One or two sentences on what students should be doing. |
| `due` | The next thing due, e.g. `Assignment 2, 30 November`. |
| `next` | When the next update is expected, as `YYYY-MM-DD`. |
| `updated` | The date you confirmed this card, as `YYYY-MM-DD`. **Change this every time you change anything else**, or the card will keep showing as old. |

Dates must be written `2026-12-03`, year first. Any other format shows as
"No information yet".

Keep the double quotation marks, the commas and the brackets exactly as they are.
If the page stops loading after an edit, the usual cause is a missing comma or
quotation mark in `status.json`.
