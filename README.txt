Geoffrey's Golf Caddie — PWA v1.0

Dit pakket is de installeerbare web-appversie.
Belangrijk: voor installatie als PWA moet deze map via HTTPS worden gepubliceerd.
Het rechtstreeks openen van index.html blijft bruikbaar om de interface te testen, maar service worker/offline installatie werkt niet via file://.

Data:
- Bestaande opslagkey blijft: geoffrey-golf-v1
- Updates zijn ontworpen om bestaande rondes te behouden.
- Nieuwe rondes krijgen playedDate + createdAt; oude rondes worden compatibel ingelezen.
- Gebruik Back-up exporteren voor extra zekerheid voor updates/apparaatwissel.
