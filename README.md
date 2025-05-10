# IOC Matcher Report
Scanned directory: `./javascript-backdoor-main` with `8` threads

- **Total unique IOCs:** 43
> [!NOTE]
## [!CAUTION] Match found (file: `./javascript-backdoor-main\malware.txt`)

- **IOC Value:** `Protokoll-0159057142.doc|d95f360cfa3bb3c38623954a03d46417a5cc89775770880d2f826b9e8fa515a5`
- **IOC Type:** filename|sha256
- **Category:** Payload delivery
- **To IDS:** True
- **Comment:**
- **Attribute Tags:** None

### Event Details
- **Event ID:** 15
- **Info:** Dridex (2016-03-07)
- **Date:** 2016-03-07
- **Event Tags:** `circl:incident-classification="malware"`, `tlp:white`
- **Threat Level:** 3
- **Analysis:** 0
- **Distribution:** 3
- **Organization:** CIRCL

## [!CAUTION] Match found (file: `./javascript-backdoor-main\server.js`)

- **IOC Value:** `brozblagrom-c2.com`
- **IOC Type:** domain
- **Category:** Network activity
- **To IDS:** True
- **Comment:** Domains registered by jgou.veia@gmail.com
- **Attribute Tags:** None

### Event Details
- **Event ID:** 14
- **Info:** OSINT - LOCKY DGA THREAT ACTOR(S)
- **Date:** 2016-03-07
- **Event Tags:** `tlp:white`, `type:OSINT`
- **Threat Level:** 3
- **Analysis:** 2
- **Distribution:** 3
- **Organization:** CIRCL

## [!CAUTION] Match found (file: `./javascript-backdoor-main\server.js`)

- **IOC Value:** `0.0.0.0`
- **IOC Type:** ip-dst
- **Category:** Network activity
- **To IDS:** False
- **Comment:** Just to replace actual "0.0.0.0" attribute and disable IDS flag
- **Attribute Tags:** None

### Event Details
- **Event ID:** 193
- **Info:** Import of CitizenLab public DB of malware indicators
- **Date:** 2014-11-20
- **Event Tags:** `type:OSINT`, `tlp:green`
- **Threat Level:** 4
- **Analysis:** 2
- **Distribution:** 3
- **Organization:** CthulhuSPRL.be

## [!CAUTION] Match found (file: `./javascript-backdoor-main\server.js`)

- **IOC Value:** `0.0.0.0`
- **IOC Type:** ip-dst
- **Category:** Network activity
- **To IDS:** False
- **Comment:**
- **Attribute Tags:** None

### Event Details
- **Event ID:** 201
- **Info:** OSINT Expansion on Systematic cyber attacks against Israeli and Palestinian targets going on for a year by Norman
- **Date:** 2015-11-05
- **Event Tags:** `tlp:green`, `admiralty-scale:information-credibility="6"`, `type:OSINT`
- **Threat Level:** 4
- **Analysis:** 2
- **Distribution:** 3
- **Organization:** CthulhuSPRL.be
