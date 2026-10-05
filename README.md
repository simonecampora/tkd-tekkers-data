# tkd-tekkers-data

Tournament data for the TKD Tekkers event-search widget: for each event, its
schedule (`<slug>-timetable.json`), entries (`-entries.json`), live-stream links
(`-streams.json`) and medal results (`-results.json`), plus `index.json`
listing the events.

The widget loads these files at runtime from
`https://raw.githubusercontent.com/simonecampora/tkd-tekkers-data/main/`.
Files are machine-generated and minified - don't edit them by hand.

Source: public SportData event pages.
