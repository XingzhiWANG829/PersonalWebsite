# Academic profile maintenance

The homepage is a static page: edit `index.html` and `assets/css/academic.css`.
No build step, JavaScript, remote fonts or external service is required. The original
Massively resources and licence are retained. The original demo routes now lead to
the academic profile instead of publishing template content.

## Content basis

- Current appointment, PhD supervision, research areas, 26 papers in the past five
  years, 800+ citations, scholarship and service information: user-confirmed
  October 2026 biography supplied in the conversation.
- Melbourne postdoctoral appointment (2024–2025), UNSW PhD subject, earlier roles,
  Springer monograph title and additional honours: prior user profile provided in
  the conversation.
- Exact dates for earlier roles and PhD, full publication citations, DOI/ISBN,
  institutional email, telephone and personal photograph are not available in the
  confirmed material and have therefore been omitted.
- Manuscripts under preparation/review and planned projects are not represented
  as published research or completed funded projects. No project budgets or
  unpublished technical results are included.

Before adding individual papers, supply verified bibliographic records. Update
publication metrics with an explicit reference date. Earlier roles are grouped
without implying a chronology that has not been confirmed.

## Review

Open `index.html` directly or run `python -m http.server 8000` from the repository.
Check desktop and narrow mobile widths, anchor navigation, keyboard focus, local
stylesheet loading, print layout, and both legacy routes. Merge the PR into
`gh-pages` only after reviewing the profile text and visual appearance.

## Three-page structure

- index.html: lab overview, dated activities and research themes. The site uses a descriptive research heading, not an invented official laboratory name.
- profile.html: confirmed biography, appointments, education, honours and service.
- highlights.html: monograph, dated publication summary and explicitly labelled research themes (not invented published papers). The book panel is typographic artwork, not an official cover.
- assets/css/lab.css: shared responsive styling; all links are relative for project Pages hosting.

The only activity currently listed is the user-confirmed 12 October 2026 exchange with Professor Sami Kara in Chongqing. No fictional students, laboratory events, photographs or news are included. Add new dated articles to the news section once confirmed. Full publication records, official laboratory name and photographs can be added when provided.
