# SchedulAI Interactive Demo

This version follows the supplied demo’s page structure and blue palette, expanded to use all 19 supplied template designs.

## User flow

1. Choose Academic, Professional, Personal, or Fitness.
2. Search and select a template design.
3. Enter information using the fields shown for that template.
4. Edit the visual map. For the Student Assignment Tracker, the live preview uses the template’s Name, Week, Class, Assignment, Due Date, and completion fields.
5. Review the composed planner and approve it.
6. Download the approved design as PDF or PNG, print it, or start another plan.

## Template behavior

The selected template is the canvas. Its own labels and categories define where information goes. The layout may add or resize rows and wrap text to fit, while preserving the template’s visual style. The original template images remain as design references; they are not used as backdrops beneath a separate schedule. The preview, PDF, PNG, and print output use the composed layout.

For the Student Assignment Tracker, enter one row per line as `Class | Assignment | Due date | Optional notes`. The Name and Week fields are separate. The visual editing map lets you update every value and mark assignments complete.

The demo uses local, template-aware parsing; it does not connect to a live AI service or database. To run it, open `index.html` in a modern browser. If the browser restricts local files, start a local static server from this folder and open its page URL.
