# Markers

A LUNA Add On that lists the open session's markers beside the Timeline, where you can add,
name, color, recall and organize them, and select the time between them.

Requires LUNA 3.1.1 or later.

## Install

1. Download `markers.lunaaddon` from the latest release on this repository's **Releases**
   page.
2. Double-click the file. LUNA installs it into its Add Ons folder.

To update, install the newer `.lunaaddon` the same way.

## Use

Choose **Add Ons > Browsers > Markers**. It opens as a panel in LUNA's secondary browser. With
no session open, it says so; open one in LUNA and the list fills in.

Each row shows the marker's number, color, name and comment, location, and the length to the
next marker. The marker the playhead is in is marked in amber.

### Add and move around

- **+ Marker** or **M** adds a marker at the playhead and opens its name for typing.
- **◀** and **▶**, or **[** and **]**, move to the previous or next marker.
- Type **.**, a number and **.** again to go to that marker: **. 1 2 .** goes to marker 12.

### Select

- **Click** a marker to select it and put LUNA's edit selection on it. With **Click to
  locate** on (in the **…** menu), the playhead moves there too.
- **Shift+click** a marker to extend the selection through it to the next marker. Click a
  marker and Shift+click it again to select from it to the next one; Shift+click a later
  marker to select through that one.
- **Cmd+click** (Ctrl+click on Windows) adds a marker to the selection or takes it out.
- **↑** and **↓** move the selection; **Enter** moves the playhead to the selected marker.

### Edit

**Double-click** a marker to open its details: name, location, comments, color and nudge
(by a bar, a beat, a 1/16 or a tick). Type locations as bar|beat|tick (`5|3|240`) or
minutes:seconds (`1:30.5`). The details stay open and follow the selection, so you can select
several markers and recolor, nudge, duplicate or delete them together. Close them with the
**×** or **Esc**.

The details also have **Select between** and **Loop**, which select or loop from the marker
to the next one, and **Set to playhead**, which moves the marker to the playhead.

Colors are LUNA's own 16 marker colors, and new markers take the next color the way LUNA's
do. Each edit is one undo step in LUNA, including changes to several markers at once.

### Organize

- Filter the list by name, comment or number.
- **Bars** / **Time** shows locations in bars and beats or in minutes and seconds.
- **Pos** / **A–Z** sorts by position or by name.
- The **…** menu has **Follow playhead** (keeps the current marker in view during playback),
  **Add at selection start**, **Renumber auto-named markers**, **Select all** and **Clear all
  markers…**.
- **Delete** removes the selected markers and **Cmd+D** (Ctrl+D) duplicates them.

**?** shows the keyboard shortcuts.
