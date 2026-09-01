# Transit cards

Public image host for the transit infographics 

These are the same cards that appear in the posted threads. This repository
exists only because Buffer's API fetches post images over the public internet —
`assets[].image.url` must resolve anonymously, so the images cannot be served
from a private repository.

**This repository contains images only.** No source code, no ephemeris data, no
interpretation logic, no databases.

Cards are referenced from
`https://raw.githubusercontent.com/<owner>/<repo>/main/cards/<name>.png`.

## Naming

```
cards/<aspect_type>_<planet1>_<planet2>_<YYYY-MM-DD>.png
cards/<aspect_type>_<planet>_<YYYY-MM-DD>.png        # ingresses, stations
```
