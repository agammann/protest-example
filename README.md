# Protest — fictional example

This is the generated demonstration site for [Protest](https://github.com/agammann/protest), a local tool for creating event fliers, share images, calendar files and a GitHub Pages website.

**There is no actual event.** The names, location and gathering are fictional. The example is deliberately marked **cancelled** to show how public updates work.

[Open the demonstration](https://agammann.github.io/protest-example/).

## Explore the output

- `index.html`: the public event page, with fictional and cancellation notices.
- `flier.pdf` and `flier.svg`: printable and editable fliers.
- `social.png` and `story.png`: square and story images.
- `event.ics`: a calendar file carrying `STATUS:CANCELLED`. Calendar imports do not automatically receive later updates.
- `protest-public.json`: the public event details. Private planning notes and editor checklist state are excluded.
- `webmcp.js`: two read-only tools, `get_protest_details` and `get_participant_instructions`. Both flag organizer-provided text as untrusted. They require a browser with native WebMCP support. The page and downloads also work in ordinary browsers.

## Preview a local copy

Clone or download this repository. If you have Python 3, run this command from the extracted directory and open `http://127.0.0.1:8000/`.

```sh
python -m http.server 8000 --bind 127.0.0.1
```

The files are ready to serve. The existing GitHub Pages site serves the files from the root of `main`. A new publication from the Protest editor replaces the generated artifacts.

To create your own event materials, use the [Windows download](https://github.com/agammann/protest#start-on-windows) or [source setup](https://github.com/agammann/protest#build-from-source). Replace the fictional details, review the public files, and publish to your own GitHub account.

The QR code points to this demonstration's stable Pages address. It is for inspecting the example, not an invitation to attend.
