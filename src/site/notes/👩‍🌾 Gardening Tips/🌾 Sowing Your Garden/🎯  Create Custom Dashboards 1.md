---
{"aliases":"🎯 Create Custom Dashboards,dashboards","type":"dashboard","dg-publish":true,"dg-home":true,"permalink":"/gardening-tips/sowing-your-garden/create-custom-dashboards-1/","tags":["gardenEntry"],"dgPassFrontmatter":true}
---


## Custom dashboards with dataview
The [Dataview](https://blacksmithgu.github.io/obsidian-dataview/) plugin for [[📇 Terms/🪨 Obsidian/🪨 Obsidian\|📇 Terms/🪨 Obsidian/🪨 Obsidian]] allows for the creation of 3 basic types of view using a SQL-like language, as well as JavaScript functions too.

Full documentation is available on the site, but to help you along here are some basic examples - if you see the `dataview` code, switch to preview mode.

### Last 5 edited files
Using the `file` object you can query properties and use functions to do things like date comparsion:
- [[👩‍🌾 Gardening Tips/🌾 Sowing Your Garden/🎯  Create Custom Dashboards 1\|🎯  Create Custom Dashboards 1]]: 8:41 PM - March 23, 2023
- [[⏣ Templates/📰 New Dashboard\|📰 New Dashboard]]: 8:39 PM - March 23, 2023
- [[👩‍🌾 Gardening Tips/🪴 Sowing Your Garden/🎯  Create Custom Dashboards\|🎯  Create Custom Dashboards]]: 8:38 PM - March 23, 2023
- [[🗂 Projects/Old_Man_Yells_at_Cloud/Rants_and_Musings\|Rants_and_Musings]]: 6:05 PM - March 23, 2023
- [[🗂 Projects/My New Garden/How Did I Get Here\|How Did I Get Here]]: 5:32 PM - March 23, 2023


### Show all tutorials
You can be more specific with queries, for example lets find all the pages that contain the `tutorial` type in [[📇 Terms/🪨 Obsidian/Front Matter\|Front Matter]]:
- [[👩‍🌾 Gardening Tips/🌾 Sowing Your Garden/⚠️ Statuses\|⚠️ Statuses]]
- [[👩‍🌾 Gardening Tips/🌾 Sowing Your Garden/🌱 Planting Seeds\|🌱 Planting Seeds]]
- [[👩‍🌾 Gardening Tips/🌾 Sowing Your Garden/🎯  Create Custom Dashboards\|🎯  Create Custom Dashboards]]
- [[👩‍🌾 Gardening Tips/🌾 Sowing Your Garden/🏭  Project Stucture\|🏭  Project Stucture]]
- [[👩‍🌾 Gardening Tips/🌾 Sowing Your Garden/🏷 Using Tags\|🏷 Using Tags]]
- [[👩‍🌾 Gardening Tips/💎 Obsidian/🔌 Plugins & 🌈 Theme\|🔌 Plugins & 🌈 Theme]]
- [[👩‍🌾 Gardening Tips/💎 Obsidian/🗂 Obsidian File Struture\|🗂 Obsidian File Struture]]
- [[👩‍🌾 Gardening Tips/💎🌳 Obsidian Garden\|💎🌳 Obsidian Garden]]
- [[👩‍🌾 Your Knowledge Garden\|👩‍🌾 Your Knowledge Garden]]


### Show all 🌱 Seed templates
As well as lists, you can also render tables - when doing this, you can use file and [[📇 Terms/🪨 Obsidian/Front Matter\|📇 Terms/🪨 Obsidian/Front Matter]] properties and provide them a label.

Querying can be done in a specific folder
| File                                                        | Description                                                                                                              |
| ----------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| [[⏣ Templates/▶️ Basic Kanban\|▶️ Basic Kanban]]         | A basic stucture for creating Kanban boards for your projects                                                            |
| [[⏣ Templates/👤 New Person\|👤 New Person]]             | A basic structure for capturing the details of a person, they could be a contact or a research subject                   |
| [[⏣ Templates/📙 New Reading Item\|📙 New Reading Item]] | A basic structure for a reading source such as a book or article                                                         |
| [[⏣ Templates/📝 Todo List\|📝 Todo List]]               | A basic structure for a todo list - inside the list create headers and sets of tasks - you can also add additional notes |
| [[⏣ Templates/📰 New Dashboard\|📰 New Dashboard]]       | A basic structure file that can be used to create dashboards                                                             |
| [[⏣ Templates/🔖 New Term\|🔖 New Term]]                 | A basic structure for a term, these are used to build up your glossary of terms across the knowledge base                |
| [[⏣ Templates/🔗 New Link\|🔗 New Link]]                 | A basic structure for a link that you want to collect                                                                    |
| [[⏣ Templates/🔬 New Research\|🔬 New Research]]         | A basic structure for carrying out a research topic with hypothesis, goals and conclusions                               |
| [[⏣ Templates/🗒 Basic Note\|🗒 Basic Note]]             | A basic note structure with no additional properties other than status and tags and links                                |
| [[⏣ Templates/🗓 Daily Note\|🗓 Daily Note]]             | A basic structure for a daily note that evolves over the day                                                             |


### People table
As well as folders we can also query `#tags` - when doing this it's good to exclude template files from the query
| File                                                          | Connection |
| ------------------------------------------------------------- | ---------- |
| [[👨‍👧‍👦 People/👤 Alexis Rondeau\|👤 Alexis Rondeau]]   | \-         |
| [[👨‍👧‍👦 People/👨🏻‍🌾 Bob\|👨🏻‍🌾 Bob]]               | \-         |
| [[👨‍👧‍👦 People/🧑🏻‍💻 Tane Piper\|🧑🏻‍💻 Tane Piper]] | \-         |

