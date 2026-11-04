# Moonlabor releases

The downloads and update feeds of Moonlabor's Mac apps. One folder per product; each holds its appcast (the feed the
app checks for updates) and a short page. The disk images are release assets, tagged `<product>-v<version>`.

| Product | Page | Feed |
|---|---|---|
| saltAMP | [saltamp/](saltamp/README.md) | [saltamp/appcast.xml](saltamp/appcast.xml) |

There is no source here. Each release published here is signed with its product's own update key, as is each feed,
and notarised by Apple. A feed item marked DRY RUN is a rehearsal, signed with a throwaway key and never published.
