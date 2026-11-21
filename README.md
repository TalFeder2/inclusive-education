# Info portal — Where we are now

Information portal for the International M.Ed. in Inclusive Education for At-Risk
Children and Youth, Oranim Academic College.

The page shows, for each course: the unit it has reached, what to do now, the next
thing due, and when the next update is expected. Below that is a media section for
articles and videos, with one piece featured each week.

Live at **https://talfeder2.github.io/inclusive-education/**

## How to update it

Everything on the page comes from **`status.json`**. Nothing else needs touching.

1. Open `status.json` on GitHub.
2. Click the pencil icon (Edit this file).
3. Change the text between the quotation marks.
4. Click **Commit changes**.

The live page updates within about a minute.

### Course fields

| Field | What goes in it |
|:--|:--|
| `en` | The course name. |
| `who` | The lecturer, and the teaching assistant if there is one. |
| `unit` | The unit the course is on, e.g. `Unit 5`. Leave empty if not known. |
| `now` | One or two sentences on what students should be doing. |
| `due` | The next thing due, e.g. `Assignment 2, 30 November`. |
| `next` | When the next update is expected, as `YYYY-MM-DD`. |
| `updated` | The date you confirmed this card, as `YYYY-MM-DD`. **Change this every time you change anything else**, or the card will keep saying it was updated days ago. |

### Media fields

Each entry in `media` is one article or video. The first one in the list is the
featured piece and is marked "This week", so to change the feature, put the new
entry first.

| Field | What goes in it |
|:--|:--|
| `title` | The headline, as the outlet wrote it. |
| `source` | The outlet, e.g. `Chalkbeat New York`. |
| `byline` | The author. Leave empty if there is none. |
| `date` | The publication date, written however you like, e.g. `12 November 2026`. |
| `url` | The link. It must start with `http://` or `https://`, or it will not appear as a link. |
| `note` | One or two sentences on what the piece reports. |

Strip tracking text from a link before pasting it — anything after a `?`, such as
`?utm_source=...`, can be deleted.

## If the page stops loading

The usual cause is a missing comma or quotation mark in `status.json`. Dates in
`next` and `updated` must be written year first (`2026-12-03`); any other format
shows as not set.
