# Hyperpaper Planner

Linked dayplanner pdf for large e-readers (reMarkable 1 & 2, Supernote, Boox, etc)

I'm building a customizable full-year 2022 version! You can [order it here](https://hyperpaper.me) and customize:
* Header layouts that leave space for your device's on-screen menus (reMarkable, Supernote, Boox Max Lumi)
* Day templates (lined or dotted, shaded working hours)
* Weekly tasks template (lined, dotted, kanban board)
* Quarterly template (lined, dotted)
* Extra linked collections of pages (Notes, Projects, custom sections of your choosing)

## Download 
The current late-2021 version can be downloaded on the [Releases page](https://github.com/af/planner-pdf/releases)

## FAQ
See the [discussions](https://github.com/af/hyperpaper-planner/discussions)

A video of the initial release in action: https://www.reddit.com/r/RemarkableTablet/comments/r5xj85/working_on_a_planner_pdf_for_my_rm2_any_feedback/

![IMG_2714](https://user-images.githubusercontent.com/25241/147267090-75ecabc5-cd73-4806-ae9c-99c860e67951.jpeg)


## Changelog

#### v0.8.1

- First pass at support for the Supernote (space above the header)
- Move Day template's `AGENDA` label to the right to allow 6am entries
- Add faint lines to the dotted Day template's agenda section
- Various font-size and spacing tweaks

#### v0.8.0

- Redesigned title page
- New quarterly pages for planning month goals
- Various styling updates throughout
- New template for reviews (added a Books section using this)
- Added support for blank pages, and Sketches pages using them
- Improved link/index pages for Notes/Projects
- Custom collection sections are now possible (eg multiple Notes/Projects sections

#### v0.7.0

- Weekly task pages, linked from each Day's TODO section
- Link to Notes index from Day pages
- Full year mini calendar for the next year (currently has broken links, will fix)
- Show holidays on monthly calendar (US holidays for now, will support others)
- Slightly darken and increase size of the more subtle text elements

#### v0.6.0
- First release of lined templates (for day pages and notes)
- Increase number of notes pages from 20 to 80
  - this is a test for having multiple notes index page. Eventually the page count here will be
    configurable
- Day page
  - Use a lined template for now
  - Have agenda part of day page take the full height of the content area
  - Added shading for working hours during the day (experiment)

#### v0.5.0
 - Initial release
