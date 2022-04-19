# Translate with Find and Replace

The table below provides examples of syntax to find and replace to translate your search from one database or platform to another.

| From  | To | Find | Replace |
| ---- | -- | ---- | ------- |
| PubMed | Embase.com  | [tw] | :ti,ab,kw *or* :ti,ab,kf |
| PubMed | Embase.com  | [tiab] | :ti,ab |
| PubMed | Embase.com  | [mesh] | /exp |
| PubMed | Embase.com  | [mesh:noexp] | /de |
| PubMed | Embase.com  | " | ' |
| PubMed | Cochrane Library  | [tw] | :ti,ab,kw |
| PubMed | Cochrane Library  | [tiab] | :ti,ab |
| PubMed | Cochrane Library | term [mesh] | [mh term] |
| PubMed | Cochrane Library  | term [mesh:noexp] | [mh ^term]|
| PubMed | MEDLINE (Ovid) | [tw] | .mp. |
| PubMed | Embase (Ovid) | [tw] | .mp. |
| Any | Scopus | ( | TITLE-ABS-KEY( |
| Any | Scopus, no truncation | ") | }) |
| Any | Scopus, no truncation | (" | ({ |
| Any | Scopus, no truncation | " OR " | } OR { |
| Scopus | Web of Science | TITLE-ABS-KEY( | TS=( |
| Any | Web of Science | ( | TS=( |




