# Art Alive | Programme Selection Portal

A minimalist, high-contrast web application for event programme interest registration and admin management.

## Features

- **Participant Portal:** Search participant by Name or Roll Number, view pre-assigned batch, filter programmes by Section (Junior, Senior, General) and Stage Type (Onstage, Off stage), and select unlimited programmes.
- **All Selections View:** Public directory where participants can view interested participants across programmes (by Programme and by Participant).
- **Admin Dashboard:** Real-time KPI summary (Total Participants, Submitted Count, Pending Count, Total Selections), searchable participant table, dynamic participant creation, and **UTF-8 CSV export with BOM** (compatible with Excel for Malayalam text).
- **Security:** Admin access protected by a secure PIN.
- **Bilingual Display:** Every programme card, tag, and table entry displays both Malayalam and English titles.
- **Persistence:** Local client-side persistence via `localStorage` (`artalive_selections_v1`).
- **Responsive:** Pure CSS3 styling optimized for desktop and mobile viewports.

## Tech Stack

- **HTML5**
- **Pure CSS3** (No external CSS frameworks)
- **Vanilla JavaScript** (Zero external libraries)
- **Fonts:** Google Fonts (`Plus Jakarta Sans` & `Noto Sans Malayalam`)
