# Weekly Planner Blueprint

Use this as a configurable starting point. It is inspired by the Discovery Day example, not a mandatory design.

## Task logic

A useful weekly planner can:

1. determine the upcoming workweek in the attendee's personal timezone;
2. inspect selected calendar events and absence blocks;
3. retrieve related email context from attendee-approved folders;
4. review available prior-week call summaries or transcripts;
5. retrieve relevant project files or pages from approved locations;
6. identify preparation, conflicts, decisions, follow-ups, people, and useful focus time;
7. generate a Weekly Preparation Planner without changing any source; and
8. skip or reduce the briefing according to the attendee's approved absence rule.

Always distinguish retrieved facts from recommendations. If a transcript, file, email, link, attendee, or task state is unavailable, omit it or label the gap.

## Suggested Weekly Preparation Planner structure

- Week overview
- Top priorities
- Conflicts and risks
- Before the week starts
- People this week
- Day-by-day timeline
- Recommended planning blocks
- Detail area with preparation, context, follow-ups, and source links
- Source coverage and limitations

## Optional interaction pattern

For attendees who want a richer HTML Weekly Preparation Planner:

- make summary sections and each day collapsible;
- place People This Week immediately above the timeline;
- sort person chips by number of meetings;
- allow multiple selected people;
- assign each selected person a stable color;
- show compact colored squares inside meetings attended by selected people;
- provide labels or a legend so color is not the only cue;
- open a persistent bottom detail panel when a timeline item is selected;
- update the panel in place for the newly selected item; and
- provide a visible separator that resizes the panel with pointer and keyboard input.

These are refinement options. Include them only when the attendee approves them.

## Example source roles

- **Calendar:** schedule, attendees, conflicts, locations, conferencing, out-of-office
- **Email:** context, decisions, commitments, follow-ups
- **Zoom or another call platform:** summaries, transcripts, recordings, and shared meeting materials
- **SharePoint or another team repository:** project pages and shared documents
- **OneDrive or another file store:** working files and personal project material

## Safe task wording

A published task should say that it may search selected sources but must not:

- send, forward, delete, categorize, or mark email read;
- change calendar events or attendance;
- edit, move, share, or delete files;
- alter meeting recordings or transcripts; or
- invent evidence when a source is unavailable.

The task should name the exact recipient and delivery mode if it creates a draft or message. Keep sending separate from drafting.
